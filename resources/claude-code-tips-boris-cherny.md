# Claude Code Tips from Boris Cherny

> Boris Cherny is the creator of Claude Code at Anthropic. He created it as a side project in September 2024, and it has since become a core development tool for engineers worldwide. In the last 30 days, Boris landed **259 PRs** — 497 commits, 40k lines added, and 38k lines removed. Every single line was written by Claude.

**Twitter/X:** [@bcherny](https://x.com/bcherny)

---

## Table of Contents

1. [Philosophy](#philosophy)
2. [Parallel Session Management](#parallel-session-management)
3. [Model Selection](#model-selection)
4. [CLAUDE.md - Team Knowledge Management](#claudemd---team-knowledge-management)
5. [Plan Mode Workflow](#plan-mode-workflow)
6. [Slash Commands](#slash-commands)
7. [Subagents](#subagents)
8. [Verification - The Most Important Tip](#verification---the-most-important-tip)
9. [Permission Management](#permission-management)
10. [Tool Integrations (MCP Servers)](#tool-integrations-mcp-servers)
11. [PostToolUse Hooks](#posttooluse-hooks)
12. [Long-Running Tasks](#long-running-tasks)
13. [Code Review Integration](#code-review-integration)

---

## Philosophy

> "There is no one correct way to use Claude Code: we intentionally build it in a way that you can use it, customize it, and hack it however you like. Each person on the Claude Code team uses it very differently."

Boris notes his setup is "surprisingly vanilla" — Claude Code works great out of the box, so he personally doesn't customize it much.

---

## Parallel Session Management

Boris treats AI as **distributed compute capacity** rather than a single tool, running 10-15+ concurrent Claude Code sessions:

### Terminal Sessions
- Runs **5 Claude instances in parallel** in his terminal
- Numbers tabs 1-5 and uses **system notifications** to know when a Claude needs input
- Each local session uses its own **dedicated git checkout** (not branches or worktrees) to prevent conflicts

### Web Sessions
- Runs **5-10 additional sessions** on claude.ai/code in the browser
- Uses the `&` command to background a session
- Uses `--teleport` flag to hand off sessions between web and local machine

### Mobile Sessions
- Kicks off sessions from his phone via the **Claude iOS app** in the morning
- Picks them up on his computer later

> Note: Approximately 10-20% of remote sessions are ultimately abandoned due to unexpected complications.

---

## Model Selection

Boris exclusively uses **Opus 4.5 with thinking mode** for all coding tasks:

> "I use Opus 4.5 with thinking for everything. It's the best coding model I've ever used, and even though it's bigger & slower than Sonnet, since you have to steer it less and it's better at tool use, it is almost always faster than using a smaller model in the end."

His philosophy: **"A wrong fast answer is slower than a right slow answer."**

He optimizes for total iteration cost rather than per-token expenses.

---

## CLAUDE.md - Team Knowledge Management

Boris's team maintains a shared **CLAUDE.md** file checked into git:

> "Anytime we see Claude do something incorrectly we add it to the CLAUDE.md, so Claude knows not to do it next time."

### Key Details:
- The whole team contributes **multiple times a week**
- Current file size: approximately **2.5k tokens**
- Contains: style conventions, design guidelines, PR templates, and documented mistakes
- Creates a **continuously improving instruction set**

This practice transforms the codebase into a **self-correcting organism**.

---

## Plan Mode Workflow

Most of Boris's sessions start in **Plan Mode**:

> "If my goal is to write a Pull Request, I will use Plan mode, and go back and forth with Claude until I like its plan. From there, I switch into auto-accept edits mode and Claude can usually 1-shot it. A good plan is really important!"

### How to Use:
1. Press **Shift+Tab twice** to enter Plan mode
2. Iterate on the plan with Claude until satisfied
3. Switch to **auto-accept edits mode** for implementation
4. Claude can usually execute the plan in one shot

This prevents unwanted sweeping changes and ensures strategic alignment.

---

## Slash Commands

Boris uses slash commands for every **"inner loop" workflow** that he does many times a day:

> "This saves from repeated prompting, and makes it so Claude can use these workflows, too."

### Key Details:
- Commands are **checked into git** and live in `.claude/commands/`
- Commands can include **inline Bash** for pre-computing information (like git status)
- The `/commit-push-pr` slash command is used **dozens of times every day**

### Example Use Cases:
- Committing, pushing, and creating PRs
- Code simplification workflows
- Verification routines

---

## Subagents

Boris uses subagents as **reusable workflow components** with specialized roles:

> "Similar to slash commands, I think of subagents as automating the most common workflows for most PRs."

### His Regular Subagents:
- **code-simplifier** - Simplifies the code after Claude is done working
- **verify-app** - Has detailed instructions for testing Claude Code end to end
- **build-validator** - Validates builds
- **oncall-guide** - Guides oncall workflows

He builds **pipelines across spec, draft, simplify, and verify phases**.

---

## Verification - The Most Important Tip

> "Probably the most important thing to get great results out of Claude Code: give Claude a way to verify its work. If Claude has that feedback loop, it will 2-3x the quality of the final result."

### Verification Methods:
- Running **bash commands**
- Running **test suites**
- Testing the app through the **browser** (using Claude Chrome extension)
- Testing through a **simulator**
- Domain-specific testing appropriate to your project

Boris uses the Claude Chrome extension to test UI changes across his projects, iterating until functionality and UX meet standards.

---

## Permission Management

Boris's approach to security:

> "I almost never use `--dangerously-skip-permissions`. Instead, I enable commonly used bash commands that are safe in my environment via `/permissions`."

### How to Set Up:
- Use `/permissions` command to pre-allow safe commands
- Common pre-allowed commands: `bun run build:*`, `bun run test:*`, etc.
- Settings are **checked into `.claude/settings.json`** and shared with the team
- This avoids unnecessary permission prompts while maintaining security

Reserve `--dangerously-skip-permissions` only for long-running sandbox tasks.

---

## Tool Integrations (MCP Servers)

Claude Code uses all of Boris's tools for him:

> "It often searches and posts to Slack (via the MCP server), runs BigQuery queries to answer analytics questions (using bq CLI), grabs error logs from Sentry, etc."

### Key Details:
- The Slack MCP configuration is **checked into `.mcp.json`** and shared with the team
- **On-demand tool loading** makes this practical: tools are available without consuming context until invoked

### Example MCP Configuration:
```json
{
  "mcpServers": {
    "slack": {
      "type": "http",
      "url": "https://slack.mcp.anthropic.com/mcp"
    }
  }
}
```

---

## PostToolUse Hooks

Boris implements **automatic formatting** to prevent CI failures:

> "Post-tool formatting prevents CI failures through a PostToolUse hook."

### Example Hook:
```bash
bun run format || true
```

This addresses the remaining edge cases in Claude's output, ensuring code meets formatting standards automatically.

---

## Long-Running Tasks

For very long-running tasks, Boris uses several strategies:

1. **Prompt Claude to verify its work** with a background agent when done
2. Use an **agent Stop hook** for deterministic checks
3. Use the **ralph-wiggum plugin** (originally dreamt up by Geoffrey Huntley)
4. Use `--permission-mode=dontAsk` or `--dangerously-skip-permissions` in a sandbox to avoid permission prompts

---

## Code Review Integration

Boris integrates Claude into PR workflows:

> "Use @.claude tags in PRs with the GitHub Action to automatically update CLAUDE.md with learnings during review."

He calls this **"Compounding Engineering"** — treating agents as collaborative team members and using reviews to update system guidelines rather than just approving code.

---

## Summary of Key Numbers

| Metric | Value |
|--------|-------|
| Terminal sessions | 5 parallel |
| Web sessions | 5-10 additional |
| CLAUDE.md size | ~2.5k tokens |
| PRs landed (30 days) | 259 |
| Commits (30 days) | 497 |
| Lines added (30 days) | 40,000 |
| Lines removed (30 days) | 38,000 |

---

## Sources

- [Boris Cherny's Twitter Thread on Claude Code Setup](https://x.com/bcherny/status/2007179832300581177)
- [Twitter Thread Reader - Full Thread](https://twitter-thread.com/t/2007179832300581177)
- [VentureBeat - Creator of Claude Code Reveals Workflow](https://venturebeat.com/technology/the-creator-of-claude-code-just-revealed-his-workflow-and-developers-are)
- [InfoQ - Inside the Development Workflow of Claude Code's Creator](https://www.infoq.com/news/2026/01/claude-code-creator-workflow/)
- [Karo Zieminski's Substack - How Boris Cherny Uses Claude Code](https://karozieminski.substack.com/p/boris-cherny-claude-code-workflow)
- [How Boris Uses Claude Code](https://howborisusesclaudecode.com/)
- [Boris Cherny's Threads Post](https://www.threads.com/@boris_cherny/post/DTBVlMIkpcm)
- [Boris Cherny on X (@bcherny)](https://x.com/bcherny)

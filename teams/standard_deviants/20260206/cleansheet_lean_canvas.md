# CleanSheet — Lean Canvas

> *"I need to clean this dataset but I don't code"*

---

## 01 · Problem

**Messy data, no way to fix it.** CSV and Excel files riddled with inconsistent date formats, duplicates, blank rows, and mixed N/A values.

Manual cleaning is tedious, error-prone, and eats entire workdays — a script could do it in seconds, but they don't code.

Existing tools (OpenRefine, pandas) have steep learning curves. Excel find & replace doesn't scale.

**Pain: 9 / 10**

---

## 02 · Solution

**Smart scan & checklist.** Upload a file — the tool surfaces every issue as an actionable checklist ("47 rows have inconsistent dates — standardize to MM/DD/YYYY?").

**One-click approve/reject** for each fix category with live preview of changes before they apply.

**Full undo history.** Every change is reversible — building trust with non-technical users who fear breaking their data.

---

## 03 · Unique Value Proposition

**"Feels like Excel. Thinks like a data engineer."**

Upload messy data. Get a smart checklist of every issue. Fix everything in one click — no code, no guessing, full undo.

*High-level concept: Grammarly for spreadsheets.*

---

## 04 · Unfair Advantage

**Growing rule library:** cleaning patterns learned from anonymized fix decisions across all users compound over time.

**Trust moat:** undo history + preview before apply = zero-anxiety adoption that competitors skip.

**Network effect:** shared cleaning templates within teams create organic lock-in.

---

## 05 · Customer Segments

**Primary:** Business analysts & ops managers who work with data daily but don't code.

**Secondary:** Researchers & academics preparing datasets for analysis or publication.

**Early adopters:** Analysts at 50–500 person companies currently wasting 4+ hours/week cleaning spreadsheets by hand.

*B2B → prosumer*

---

## 06 · Key Metrics

- **Activation:** First file cleaned within 5 minutes of signup
- **Quality signal:** % of suggested fixes accepted (measures solution accuracy)
- **Value metric:** Time saved vs. manual cleaning per session
- **Retention:** Weekly active users uploading files at Day 30
- **North star:** Files cleaned per user per week

---

## 07 · Channels

- **SEO:** "How to clean data without coding," "fix messy CSV online" — high-intent, low-competition keywords.
- **Communities:** Reddit r/analytics, LinkedIn data ops groups, Product Hunt launch.
- **Content:** YouTube before/after demos showing 4-hour manual job done in 30 seconds.
- **Integrations:** Zapier, Airtable, Google Sheets — show up where the data already lives.

---

## 08 · Cost Structure

- **Compute:** Cloud processing for file scanning & AI pattern detection (serverless, scales with usage).
- **Team:** Small engineering team (2–3 devs + 1 designer) in early stage.
- **Acquisition:** Content marketing & community (low CAC channel focus).

*Infrastructure: S3 storage + serverless functions. Scales linearly with file volume.*

---

## 09 · Revenue Streams

- **Free tier:** Up to 5 files/month, 10K rows max. Enough to prove value and build habit.
- **Pro — $19/mo:** Unlimited files, advanced cleaning rules, saved templates, priority processing.
- **Team — $49/mo:** Shared cleaning templates, audit logs, team collaboration, priority support.

*Enterprise (future): Custom pricing — SSO, API access, SLAs, on-prem option.*

---

*Lean Canvas — Ash Maurya framework*

**Pain Score: 9/10 — OpenRefine exists but the UX gap is massive**

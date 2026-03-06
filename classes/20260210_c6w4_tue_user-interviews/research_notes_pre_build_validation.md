# Research Notes: Pre-Build Startup Validation Techniques

**Date:** 2026-02-09
**Researcher:** Claude (Opus 4.6)
**Purpose:** Raw research notes to inform the full report on pre-build validation techniques

---

## TABLE OF CONTENTS

1. [Validation Stages Framework](#1-validation-stages-framework)
2. [Evidence Hierarchy: Say vs Do vs Pay](#2-evidence-hierarchy-say-vs-do-vs-pay)
3. [Technique Taxonomy (18 Techniques)](#3-technique-taxonomy)
   - 3.1 Problem Interviews / Customer Discovery
   - 3.2 Solution Interviews / Concept Testing
   - 3.3 Surveys
   - 3.4 Competitive Analysis
   - 3.5 Landing Page / Smoke Tests
   - 3.6 Fake Door Tests
   - 3.7 Waitlist Signups
   - 3.8 Pre-Orders / Letters of Intent
   - 3.9 Concierge MVP
   - 3.10 Wizard of Oz MVP
   - 3.11 Paper Prototyping
   - 3.12 Clickable Mockups / Figma Prototypes
   - 3.13 Ad Campaign Validation
   - 3.14 Crowdfunding as Validation
   - 3.15 Explainer Video Tests
   - 3.16 Social Media Validation / Audience Building
   - 3.17 Email Campaign Validation
   - 3.18 Pocket Test / Pub Test
4. [Key Practitioners & Frameworks](#4-key-practitioners--frameworks)
5. [Common Mistakes & Anti-Patterns](#5-common-mistakes--anti-patterns)
6. [Case Studies](#6-case-studies)

---

## 1. Validation Stages Framework

### David Rogers' Four Stages of Validation

Source: [David Rogers, "The Four Stages of Validation"](https://davidrogersdigital.substack.com/p/the-four-stages-of-validation)

The four stages, in required sequential order:

| Stage | Question | What You're Testing |
|-------|----------|-------------------|
| **1. Problem Validation** | Are we focused on a genuine problem for an actual customer? | Does this problem exist? Is it painful enough to motivate action? |
| **2. Solution Validation** | Does the customer see value in our proposed solution? | Does our approach resonate? Will they engage with it? |
| **3. Product Validation** | Can we deliver a solution that customers use? | Does the MVP work? Do people actually use it? |
| **4. Business Validation** | Can we capture sufficient value from this innovation? | Will the economics work? Is this a viable business? |

**Critical insight:** Organizations consistently get the sequence wrong.
- Finance-driven firms rush to Stage 4 ("Show me the business case first") -- resulting in "spreadsheets filled with fictional numbers"
- Engineering-driven firms start at Stage 3 (building before validating the problem)
- Marketing-driven firms start at Stage 2 (wireframes before confirming the problem exists)

Source: [FasterCapital, "Stages of startup idea validation"](https://fastercapital.com/content/Stages-of-startup-idea-validation.html)

### Mapping Techniques to Stages

| Stage | Appropriate Techniques |
|-------|----------------------|
| Problem Validation | Problem interviews, surveys, competitive analysis, social listening, contextual inquiry |
| Solution Validation | Solution interviews, paper prototypes, Figma mockups, pocket test, explainer videos |
| Demand Validation | Landing pages, fake door tests, waitlists, ad campaigns, social media validation |
| Commitment Validation | Pre-orders, LOIs, crowdfunding, concierge MVP, Wizard of Oz |

---

## 2. Evidence Hierarchy: Say vs Do vs Pay

Source: [Learning Loop, "Validating Willingness to Pay"](https://learningloop.io/playbooks/validating-willingness-to-pay)

**Core principle:** "Do not trust people's words; we want to get people to put money behind their words."

People consistently overstate their willingness to pay and understate their resistance to change. When someone says "I would definitely pay for this," they often mean "This sounds useful in theory."

Source: [Medium / Review Raccoon, "7 Steps to Really Validate Any Startup Idea"](https://medium.com/@reviewraccoon/7-steps-to-really-validate-any-startup-idea-will-anyone-pay-for-it-7dad06c69a97)

### Ranked Evidence Strength (Strongest to Weakest)

| Rank | Evidence Type | Examples | Reliability |
|------|-------------|----------|-------------|
| 1 | **Actual financial commitment** | Pre-orders, deposits, purchases | Strongest |
| 2 | **Market experiments** | A/B tested price points with real transactions | Very strong |
| 3 | **Auction mechanisms** | Bidding behavior reflecting actual WTP | Strong |
| 4 | **Behavioral analytics** | Purchase history, discount response patterns | Moderate |
| 5 | **Conjoint analysis** | Feature valuation trade-off studies | Moderate |
| 6 | **Direct surveys** | "Would you pay $X?" / Van Westendorp | Weakest |

Source: [Product Talk / Teresa Torres, "How Can You Test a Customer's Willingness to Pay?"](https://www.producttalk.org/2023/05/willingness-to-pay/)

**Key quote from Rob Fitzpatrick's The Mom Test:** Real validation comes from commitments and advancements -- Time (agreeing to a follow-up meeting), Reputation (making an introduction), Money (pre-orders, budget allocation).

Source: [Rick Lindquist, "Notes from The Mom Test"](https://www.ricklindquist.com/notes/the-mom-test-by-rob-fitzpatrick)

---

## 3. Technique Taxonomy

---

### 3.1 Problem Interviews / Customer Discovery Interviews

**What it is:** One-on-one conversations with potential customers focused exclusively on understanding their problems, pain points, and current behaviors -- NOT pitching your solution. The goal is to validate that a real problem exists and is painful enough to motivate action.

**When to use:** Stage 1 (Problem Validation). This should be the FIRST thing you do. Before any prototyping, landing pages, or solution design.

**What evidence it produces:**
- Confirmation (or invalidation) that the problem exists
- Understanding of severity/frequency of the problem
- How customers currently solve the problem (or cope with it)
- Language customers use to describe the problem (critical for marketing later)
- Who the decision-makers and budget-holders are
- Willingness to invest time/money in solving it

**Time and cost:**
- Time: 2-4 weeks to complete 15-30 interviews
- Cost: $0-500 (coffee, thank-you gifts)
- Each interview: 30-45 minutes recommended
- Source: [Naviu, "25 Proven Ways to Validate"](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**How many interviews:**
- Minimum 10 to start understanding patterns ([HBS Rock Center](https://startupguide.hbs.edu/product/customer-problem-fit/customer-interviewing-techniques-that-uncover-your-users-unmet-needs/))
- 20-30 for stronger signal ([Growth Ramp](https://www.growthramp.io/articles/customer-discovery-interviews))
- Stop when you can predict what the next person will say before they say it

**Strengths:**
- Most reliable early-stage insights
- Reveals unexpected needs and problems you didn't anticipate
- Builds relationships with potential early adopters
- Cheap and requires no technology
- Produces rich qualitative data

**Weaknesses:**
- Time-intensive -- each interview takes 30-45 min plus scheduling
- Requires interviewing skill (most founders are bad at this initially)
- People lie to be polite -- politeness bias is the #1 threat
- Limited sample size (can't interview thousands)
- Confirmation bias -- founders hear what they want to hear
- Source: [ProductPlan, "9 Tips for Better Customer Validation Interviews"](https://www.productplan.com/learn/customer-validation-interviews/)

**Key methodological rules (from The Mom Test):**
1. Talk about THEIR life, not your idea
2. Ask about past behavior, not hypothetical futures ("Tell me about the last time..." not "Would you ever...")
3. Never pitch your solution during a problem interview
4. Listen more than you talk
5. Beware 3 types of bad data: compliments, hypothetical fluff, and wishlists
6. End every conversation with a commitment ask (time, reputation, or money)
- Source: [Rob Fitzpatrick / The Mom Test](https://www.ricklindquist.com/notes/the-mom-test-by-rob-fitzpatrick), [Dualoop summary](https://dualoop.com/en-be/blog/the-mom-test-explained-by-rob-fitzpatrick)

**Critical distinction -- Problem Interview vs Solution Interview:**

| Aspect | Problem Interview | Solution Interview |
|--------|------------------|-------------------|
| **Goal** | Discover and validate problems | Test whether your solution addresses those problems |
| **When** | First -- before any solution design | After problem validation |
| **What you show** | Nothing -- just listen | Mockup, prototype, wireframe, or concept |
| **Key question** | "Tell me about the last time you dealt with [problem]..." | "Here's what we're thinking -- rank these features..." |
| **Volume** | 10-15 minimum | 20+ recommended |
| **Risk** | Leading questions, hearing what you want | Confirmation bias from demo effect |

Source: [LEANFoundry / Ash Maurya](https://blog.leanstack.com/the-updated-problem-interview-script-and-a-new-canvas/), [Angel Star Digital](https://www.angelstardigital.com/lean-startup-solution-interview/)

---

### 3.2 Solution Interviews / Concept Testing

**What it is:** Structured conversations where you present a proposed solution (mockup, wireframe, concept description) to people who have the validated problem, and gauge their reaction. Unlike problem interviews, you ARE showing something -- but the goal is still learning, not selling.

**When to use:** Stage 2 (Solution Validation). After you've confirmed the problem exists through problem interviews.

**What evidence it produces:**
- Whether the proposed solution addresses the validated problem
- Feature prioritization (must-have vs nice-to-have vs don't-need)
- Willingness to pay signals (though stated, not behavioral)
- UX expectations and mental models
- Competitive alternatives they'd compare you to

**Time and cost:**
- Time: 1-3 weeks for 15-25 interviews
- Cost: $0-500 (similar to problem interviews, plus prototype creation time)
- Requires a simple prototype/mockup to show (paper, Figma, or even a verbal description)

**Strengths:**
- Tests solution fit before building anything
- Feature prioritization prevents building the wrong thing
- Direct feedback on value proposition
- Can test pricing sensitivity in conversation
- Reveals deal-breakers early

**Weaknesses:**
- Demo effect: showing something creates artificial enthusiasm
- "Cool idea!" does NOT mean "I will pay for this"
- Stated feature preferences often differ from actual usage
- Requires having a clear enough concept to present
- Source: [DevSquad, "The 7-Step Process to Startup Validation"](https://devsquad.com/blog/startup-validation)

**Format (from Lean Startup methodology):**
1. Open with problem confirmation (1-2 min)
2. Present the solution concept (keep it minimal -- 2-3 min)
3. Let them explore/react (5-10 min)
4. Ask them to rank features: "must-have", "nice-to-have", or "don't need"
5. Ask about willingness to pay (but don't trust the answer at face value)
6. End with a commitment ask: "Can I follow up with you when we have a beta?" / "Would you introduce me to someone else who has this problem?"

Source: [AngelStar Digital, "Lean Startup Solution Interview"](https://www.angelstardigital.com/lean-startup-solution-interview/)

---

### 3.3 Survey Validation

**What it is:** Structured questionnaires distributed to a larger sample of potential customers to quantify patterns discovered in interviews. Surveys validate at scale what interviews reveal in depth.

**When to use:** Stage 1-2 (Problem and Solution Validation). Best used AFTER interviews, to quantify qualitative findings. Never use surveys as your FIRST validation method.

**What evidence it produces:**
- Quantified frequency/severity of the problem across a larger sample
- Market segmentation data
- Feature preference rankings
- Price sensitivity data (Van Westendorp method)
- Demographic and behavioral patterns

**Time and cost:**
- Time: 1-2 weeks to design, distribute, and analyze
- Cost: $0-200 (free tools like Google Forms, Typeform; or paid panels)
- Recommended sample: 100+ responses; ideal is 1,000 for statistical significance
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea), [LinkedIn Advice](https://www.linkedin.com/advice/1/what-best-ways-validate-business-idea-using-surveys)

**Strengths:**
- Quantifiable data at scale
- Validates interview insights with larger sample
- Can reach geographically diverse respondents
- Relatively cheap and fast
- Produces data that investors find compelling

**Weaknesses:**
- **Presumes you know the right questions to ask** -- you could be completely missing the mark
- Even if respondents all say yes, it does NOT mean they'd actually use/pay for a solution
- Response bias: people answer how they think they should, not how they actually behave
- Self-selection bias: only certain types of people complete surveys
- Survivorship bias: you only hear from people who are still engaged
- Survey bias can "systematically skew findings in particular directions" and "a survey can produce highly consistent results (good reliability) that are consistently wrong (poor validity)"
- Source: [Medium / Masatoshi Nishimura](https://medium.com/kaffae/how-i-used-survey-to-validate-idea-dos-and-don-t-startup-week-17-a2aa60624789), [Lensym, "Survey Bias Guide"](https://lensym.com/blog/survey-bias-guide)

**Critical design rules:**
1. Do NOT tell respondents about your idea until the end of the survey
2. First 2-3 questions should be screening/qualifying questions
3. Avoid jargon; use language your customers use
4. Be neutral -- don't ask leading questions
5. Keep it short (5-7 minutes max)
6. Use a mix of closed-ended (quantitative) and open-ended (qualitative) questions
- Source: [SurveyMonkey](https://www.surveymonkey.com/curiosity/validate-startup-idea-consumer-behavior-bridgecare-finance/), [ForEntrepreneurs](https://www.forentrepreneurs.com/surveys/)

---

### 3.4 Competitive Analysis as Validation Input

**What it is:** Systematic study of existing competitors, alternatives, and substitutes in your problem space. Not a standalone validation technique -- it's a supporting input that informs other validation methods.

**When to use:** Stage 1 (Problem Validation) and ongoing. Should happen early and continuously. Particularly valuable before interviews (helps you ask better questions) and before landing page tests (helps you position effectively).

**What evidence it produces:**
- Confirmation that the problem is real (others are solving it)
- Gaps in existing solutions (opportunity signals)
- Pricing expectations and models
- Customer complaints and unmet needs (from reviews)
- Feature expectations and table stakes
- Market size indicators

**Time and cost:**
- Time: 1 week for initial analysis
- Cost: $50-200 (tools like SEMrush, Ahrefs, or free alternatives)
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Strengths:**
- Quick identification of gaps and underserved segments
- Reveals customer frustrations through review mining
- Cost-effective early validation input
- Helps refine value proposition before customer conversations
- Available data -- competitors have already done some market validation for you
- Source: [Antler Academy](https://www.antler.co/academy/startup-competitor-analysis)

**Weaknesses:**
- Does NOT validate YOUR specific solution
- Past competitor behavior doesn't predict future market needs
- Can create "false crowding" -- just because competitors exist doesn't mean the market is served well
- May lead to me-too thinking rather than innovation
- Source: [Pragmatic Coders](https://www.pragmaticcoders.com/blog/how-to-conduct-a-competitive-analysis)

**Frameworks:**
- **Feature matrix:** Compare 10-15 competitors across key features, pricing, target segment
- **Review mining:** Read 1-star and 5-star reviews of competitors on G2, Capterra, App Store, Reddit
- **SWOT analysis** for each major competitor
- **Porter's Five Forces** for overall market dynamics (though "may not be as effective in niche markets and emerging industries")
- Source: [Qubit Capital](https://qubit.capital/blog/competitive-analysis-strategies-for-startups), [Harvard Business School](https://www.isc.hbs.edu/strategy/business-strategy/Pages/the-five-forces.aspx)

**Practical approach:**
Talk to potential customers and note what names keep coming up when discussing the problem space. Those are your real competitors -- not what a Google search returns.
- Source: [Female Switch](https://www.femaleswitch.com/playbook/tpost/1kn43hli61-5-simple-steps-to-a-useful-startup-compe)

---

### 3.5 Landing Page / Smoke Tests

**What it is:** Creating a simple web page that presents your product's core value proposition with a clear call-to-action (email signup, "Get Started", pricing page), then driving traffic to it and measuring conversion. The product doesn't exist yet -- you're testing whether the *description* of the product generates interest.

**When to use:** Stage 3 (Demand Validation). After you've validated the problem and solution concept through interviews. You need a clear enough value proposition to articulate on a page.

**What evidence it produces:**
- Conversion rate (visitors to signups/clicks)
- Which value proposition messaging resonates (if A/B testing)
- Email list of interested potential customers
- Traffic source quality data
- Bounce rate and engagement metrics

**Time and cost:**
- Time: 3-7 days to build and launch
- Cost: $100-500 (page builder + initial traffic)
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Conversion rate benchmarks:**
- There is NO universal threshold that validates an idea -- context matters
- A 20% conversion rate (visitor to email signup) was cited as a strong result for a budgeting app
- Industry average conversion rates for landing pages: ~2-5%
- "If your product is high-ticket or niche B2B, even a 2% conversion could be significant if the leads are high quality"
- The key: set your own success threshold BEFORE running the test
- Source: [GLIDR Help Center](https://help.glidr.io/en/articles/1648431-landing-page-smoke-test), [Founder FAQs](https://founderfaqs.com/blogs/how-to-run-a-smoke-test-landing-page-to-prove-demand)

**Strengths:**
- Quick results -- days not months
- Measures actual behavior (clicking, signing up) vs stated intent
- Creates an email list for future outreach
- Low cost relative to building a product
- Can A/B test messaging, pricing, and positioning
- Source: [Eximius VC](https://eximiusvc.com/blogs/guide-to-smoke-testing-for-product-ideas/)

**Weaknesses:**
- Normal conversion rates are only 1-2%, so you need significant traffic for meaningful data
- Email signups do NOT equal willingness to pay
- Poor page design/copy creates false negatives (killing good ideas)
- Requires traffic generation skill (SEO, ads, community posting)
- Doesn't tell you WHY people signed up or didn't
- Source: [CXL, "Guide to Smoke Testing"](https://cxl.com/blog/smoke-test/)

**Famous example -- Buffer:**
Joel Gascoigne built a 2-page landing page: Page 1 described the concept with a "Plans & Pricing" button. Page 2 showed pricing tiers. Page 3 collected email. The pricing page was the key innovation -- it tested willingness to pay, not just interest. Result: 100 signups and 3 paying customers in the first month. He then built the product.
- Source: [Buffer blog, "Idea to Paying Customers in 7 Weeks"](https://buffer.com/resources/idea-to-paying-customers-in-7-weeks-how-we-did-it/), [Joel Gascoigne on Medium](https://medium.com/@joelgascoigne/how-to-successfully-validate-your-idea-with-a-landing-page-mvp-ef3c2d02dc51)

---

### 3.6 Fake Door Tests

**What it is:** Presenting users with what appears to be a real feature or product option (a button, link, menu item), but nothing actually exists behind it. When someone clicks, they encounter a "coming soon" message, often with an option to sign up for updates. Measures genuine interest through behavior.

Also called: painted door test, 404 test.

**When to use:** Stage 3 (Demand Validation). Especially useful for testing new features within existing products, or testing product concepts where you already have an audience.

**What evidence it produces:**
- Click-through rate (CTR) -- what percentage of people who see the option click on it
- Post-click conversion (email signups on the "coming soon" page)
- Comparison data if testing multiple concepts simultaneously
- Source: [Learning Loop, "Fake Door Testing"](https://learningloop.io/plays/fake-door-testing)

**Time and cost:**
- Time: 3-5 days (extremely fast)
- Cost: $0-100 (minimal engineering/design effort)
- Aim for 1,000+ views or 100+ clicks before analyzing
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Strengths:**
- Rapid validation in days, not months
- Very low cost
- Behavioral data (real actions, not opinions)
- Repeatable and scalable for testing multiple ideas
- No product impact -- nothing actually deployed
- Source: [Learning Loop](https://learningloop.io/plays/fake-door-testing)

**Weaknesses:**
- User frustration/trust risk -- the "gotcha" can alienate users
- Measures desirability ONLY -- not feasibility, usability, or satisfaction
- Execution bias -- poor wording/placement creates false negatives
- Ethical concerns about deception
- High clicks might indicate curiosity, not purchase intent
- Source: [Learning Loop](https://learningloop.io/plays/fake-door-testing), [Evelance](https://evelance.io/blog/fake-door-testing-the-complete-guide/)

**Real-world examples:**
- **Zynga:** Tests new game concepts by inserting five-word pitch promotions into existing games; CTR determines which ideas get development budgets
- **Buffer:** Landing page with "Plans & Pricing" button before the product existed
- **Tesla:** $5,000 deposit to secure a Roadster build date before production
- Source: [Learning Loop](https://learningloop.io/plays/fake-door-testing)

---

### 3.7 Waitlist Signups

**What it is:** Collecting email addresses from people who want to be notified when your product launches, typically through a "coming soon" or pre-launch landing page. Often combined with referral mechanics to create viral growth.

**When to use:** Stage 3 (Demand Validation). After you have a clear value proposition. Especially effective for consumer products and SaaS.

**What evidence it produces:**
- Total signup volume (raw demand signal)
- Signup velocity (growth rate -- is interest accelerating or plateauing?)
- Referral rate (organic word-of-mouth signal)
- Email engagement metrics (open rates, click rates on updates)
- Qualitative data if you add survey questions to signup
- Source: [Prefinery, "Building a Waitlist"](https://www.prefinery.com/blog/building-a-waitlist-for-your-startup-the-complete-step-by-step-guide/)

**Time and cost:**
- Time: 1-2 weeks to set up; 2-8 weeks to accumulate meaningful data
- Cost: $0-500 (landing page + email tool + optional ads)
- Tools: Prefinery, LaunchList, KickoffLabs, Viral Loops

**Strengths:**
- Validates demand before building
- Creates a launch audience (warm leads for Day 1)
- Referral mechanics can create viral growth
- Provides segmentation data if you ask questions at signup
- Source: [Aleph One, "The Power of Waitlists"](https://aleph1.io/blog/startup-waitlist-success-guide/)

**Weaknesses:**
- **A long waitlist alone does NOT guarantee a viable product** -- some startups have had massive waitlists but ultimately failed
- Email signup is a very low-commitment action
- Many signups will never convert to active users or paying customers
- Doesn't test willingness to pay
- Can create false confidence
- Source: [Aleph One](https://aleph1.io/blog/startup-waitlist-success-guide/)

**Famous examples:**
- **Robinhood:** Built a waitlist of over 1 million users with a referral program. Each user brought an average of 3 additional signups. Helped secure $13 million in funding.
- **Harry's Razors:** Tiered referral system (5 friends = free shaving cream, 10 = razor). Led to 100,000 signups in one week.
- Source: [Prefinery, "How to Turn Your Waitlist Into a Growth Engine"](https://www.prefinery.com/blog/how-to-turn-your-product-waitlist-into-a-growth-engine-lessons-from-successful-startups/), [Viral Loops](https://viral-loops.com/blog/robinhood-referral-got-1-million-users/)

**Key metrics:**
- In SaaS, 30-60% of those who make a pre-signup typically buy the product for at least one month
- Source: [Prefinery, "Pre-Launch Email Campaign"](https://www.prefinery.com/blog/referral-programs/prelaunch-campaign/email-2/)

---

### 3.8 Pre-Orders / Letters of Intent (LOIs)

**What it is:** Asking potential customers to commit financially BEFORE the product exists. Pre-orders involve actual payment (or deposits). Letters of intent are written commitments (typically non-binding) to purchase when available. Both test the strongest signal: willingness to part with money.

**When to use:** Stage 4 (Commitment/Business Validation). After problem, solution, and demand have been validated through other means. This is the final test before committing to build.

**What evidence it produces:**
- **Pre-orders:** Actual revenue and proof of willingness to pay at a specific price point
- **LOIs:** Written commitment from potential customers (especially B2B); useful as fundraising evidence
- Customer identity data (who is your actual buyer?)
- Price validation (what price point generates orders?)
- Source: [FasterCapital, "Pre-orders for Startups"](https://fastercapital.com/content/Pre-orders--How-to-Use-Pre-orders-to-Validate-Your-Ecommerce-Startup-Idea-and-Raise-Capital.html)

**Time and cost:**
- Time: 4-8 weeks for a campaign
- Cost: $500-2000 (landing page, mockups, marketing materials)
- For LOIs specifically: requires personal outreach, often founder-led sales
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Strengths:**
- **Strongest proof of willingness to pay** -- the gold standard of pre-build validation
- Funds development (pre-orders generate actual revenue)
- Creates accountability and urgency to deliver
- LOIs provide strong evidence for investor pitches
- Sets expectations with early customers
- Source: [Learning Loop, "Validating Willingness to Pay"](https://learningloop.io/playbooks/validating-willingness-to-pay)

**Weaknesses:**
- Requires a complete pitch and compelling mockups/visuals
- Sets delivery expectations -- failure to deliver damages reputation
- LOIs are non-binding: "The prospect has no legal obligation to move forward"
- Pre-orders from early adopters may not represent mainstream demand
- Requires confidence in ability to eventually deliver
- Source: [Common Paper, "What is an LOI?"](https://commonpaper.com/blog/what-is-an-loi/), [Medium / Entrepreneurs First, "The Letter of Intent Fallacy"](https://medium.com/entrepreneurs-first/the-letter-of-intent-fallacy-9929c5fc3e2a)

**LOI caveat from Entrepreneurs First:**
"In the same way that with an app it's not sign ups that matter, but level of user engagement, for a deep tech company, it's not LOIs that matter but the level of customer understanding."

**Famous examples:**
- **Tesla Model 3:** 325,000+ reservations ($1,000 deposit each) in the first week -- strongest pre-order validation in history
- **Pebble:** Over $10 million on Kickstarter from 68,000+ backers (initial goal: $100,000)
- Source: [FasterCapital](https://fastercapital.com/content/Pre-orders--How-to-Use-Pre-orders-to-Validate-Your-Ecommerce-Startup-Idea-and-Raise-Capital.html)

---

### 3.9 Concierge MVP

**What it is:** Founders personally deliver the service/solution to a small number of customers, doing everything manually. The customer knows it's human-delivered. There's no technology -- you ARE the product. The goal is to learn what customers actually need while validating demand.

**When to use:** Stage 2-3 (Solution + Demand Validation). When you need deep customer understanding and are unsure which solution component matters most. Especially useful for service businesses and B2B.

**What evidence it produces:**
- Whether customers will actually use and pay for the solution
- What the core value proposition really is (often surprises founders)
- Exactly what needs to be automated later
- Customer acquisition process insights
- Pricing sensitivity (what will they actually pay?)
- Source: [Learning Loop, "Concierge MVP"](https://learningloop.io/plays/concierge)

**Time and cost:**
- Time: 4-8 weeks with 5-10 customers
- Cost: $2,000-5,000 (primarily labor)
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Key metrics (from Learning Loop):**

| Metric | Threshold for Success |
|--------|----------------------|
| Conversion rate | 20%+ sign-up to activation |
| Repeat usage | 40%+ repeat within 30 days |
| Time per activation | >30 min = needs streamlining |
| Net Promoter Score | >30 justifies automation |
| Revenue per user | Must meet target ARPU |
| CAC | Must be <35% of projected LTV |

**Strengths:**
- Direct contact reveals pain points, language, and decision triggers
- Firsthand knowledge of effort needed for final product
- Immediate feedback without coding delays
- Transforms early users into advocates
- Low risk -- no engineering investment
- Source: [Learning Loop](https://learningloop.io/plays/concierge), [N-iX](https://www.n-ix.com/concierge-mvp/)

**Weaknesses:**
- **Does NOT scale** -- effort grows linearly with users; this is BY DESIGN
- Time-intensive: "you literally become your MVP concierge"
- Early users may not represent the broader market
- Cannot test UI/UX or automated interaction patterns
- Automation transition will require additional investment
- Feedback may be biased: "Early users are often more patient or motivated than typical customers"
- Source: [Upsilon IT](https://www.upsilonit.com/blog/what-is-a-concierge-mvp-and-when-to-use-it), [Empat Tech](https://www.empat.tech/blog/concierge-mvp)

**Famous example -- Food on the Table:**
Founder Manuel Rosso personally visited each customer, gathered food preferences, created shopping lists, selected recipes based on what was on sale at local grocery stores, and delivered products to the user's home. He solicited feedback weekly and made changes. Eventually demand was strong enough to automate. Key lesson: "Don't try to learn it all at once -- break it into small steps and move on when you can anticipate what customers will say before they say it."
- Source: [iBuild MVPs](https://ibuildmvps.com/blog/the-concierge-minimum-viable-product-maximizes-customer-learning/), [Shortform](https://www.shortform.com/blog/concierge-mvp/)

---

### 3.10 Wizard of Oz MVP

**What it is:** Users interact with what appears to be a fully functional automated product, but behind the scenes, a human is manually performing the work. Unlike a concierge MVP, users do NOT know it's human-powered. The interface looks real; the backend is a person.

**When to use:** Stage 3 (Product Validation). When you want to test the user experience and interface expectations of an automated product, but building the automation is expensive/risky. Better for consumer products where interface behavior is the unknown.

**What evidence it produces:**
- Whether users can navigate the interface successfully
- What the user experience "should" feel like
- Feature usage patterns and preferences
- Whether the product delivers value (from the user's perspective)
- Customer satisfaction without actual technology
- Evidence strength rated 90/100 by Learning Loop
- Source: [Learning Loop, "Wizard of Oz Experiment"](https://learningloop.io/plays/wizard-of-oz)

**Time and cost:**
- Time: 2-4 weeks
- Cost: $500-2000 (labor-intensive, but no engineering)
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Concierge vs Wizard of Oz comparison:**

| Aspect | Concierge | Wizard of Oz |
|--------|-----------|-------------|
| User awareness | Users know it's manual | Users think it's automated |
| Transparency | Open about manual process | Hidden human operation |
| Primary goal | Validate demand through direct contact | Test interface/workflow expectations |
| Best for | Early discovery, B2B services | UI/UX validation, consumer apps |
| Ethical risk | Low (transparent) | Higher (deception involved) |
| Source: [Learning Loop](https://learningloop.io/plays/concierge), [LogRocket](https://blog.logrocket.com/product-management/concierge-wizard-of-oz-mvp/) |

**Strengths:**
- Reveals authentic user behavior before product exists
- Detects design flaws and UX issues early
- Supports innovation testing with unproven concepts
- No engineering investment needed
- Users experience the "real" product feel
- Source: [Learning Loop](https://learningloop.io/plays/wizard-of-oz)

**Weaknesses:**
- **Ethical concerns:** Core deception is embedded in the approach
- If customers discover the illusion, trust and credibility suffer
- Scalability: manual operation cannot handle large user volumes
- Operator variability: inconsistent responses affect data quality
- Only simple workflows can be effectively simulated
- Deception-based testing may require ethics board approval
- Source: [Medium / Asaf Atzmon, "Eric Ries and the Wizard of Oz"](https://medium.com/swlh/eric-ries-and-the-wizard-of-oz-3de11e800784), [Learning Loop](https://learningloop.io/plays/wizard-of-oz)

**Famous examples:**
- **Zappos:** Nick Swinmurn photographed shoes at local malls, posted them on a website. When a customer ordered, he went to the mall, bought the shoes, and shipped them. Customers had no idea. Validated that people would buy shoes online. Zappos was acquired by Amazon for $1.2 billion.
  - Source: [Verticode](https://www.verticode.co.uk/blog/zappos-mvp-example)
- **Aardvark:** Social search engine where staff manually routed questions to experts, posing as an automated system. Acquired by Google in 2010.
  - Source: [RabitSolutions](https://www.rabitsolutions.com/blog/examples-of-mvp/)

---

### 3.11 Paper Prototyping

**What it is:** Creating rough, hand-drawn sketches of user interfaces on paper to test user flows, layout, and interaction patterns. One person plays the user, another simulates the system's responses by swapping paper "screens" in response to user actions.

**When to use:** Stage 2 (Solution Validation). Very early in the design process. Before spending ANY time on digital tools. Best for testing navigation, layout, and core user flows.

**What evidence it produces:**
- Whether users understand the interface and navigation
- Usability issues with flow and layout
- Which features/screens users gravitate toward
- Mental model alignment (do users expect the product to work this way?)
- Source: [NN/g, "Paper Prototyping"](https://www.nngroup.com/articles/paper-prototyping/)

**Time and cost:**
- Time: Hours to 1-3 days
- Cost: $0-50 (paper, pens, sticky notes, scissors)
- A team "sketched different navigation layouts, tested them with users, gathered feedback, and refined -- all within a day"
- Source: [FasterCapital, "Paper Prototyping: Low Cost and High Impact"](https://fastercapital.com/content/Paper-prototyping--A-Low-Cost-and-High-Impact-Method-for-Testing-Your-Prototype.html), [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Strengths:**
- Extremely fast and cheap
- Can be modified on the spot during testing
- Forces focus on essential flows vs visual polish
- "It can be up to 100 times more expensive to change a coded feature than a prototype"
- No software skills needed -- anyone can draw boxes
- "The biggest improvements in user experience come from gathering usability data as early as possible"
- Source: [NN/g](https://www.nngroup.com/articles/paper-prototyping/), [IxDF](https://www.interaction-design.org/literature/topics/paper-prototyping)

**Weaknesses:**
- Limited interactivity -- can't simulate complex interactions
- Requires facilitator to be present (can't send paper to remote testers)
- Users may not take it seriously or may be confused by fidelity level
- Not suitable for testing detailed visual design or micro-interactions
- At advanced stages, users expect more realistic interactions
- Source: [Medium / Shen Gao](https://medium.com/@sheneral/paper-prototyping-how-to-pros-cons-and-the-struggles-of-guerrilla-usability-testing-5546dd446d5e), [Dovetail](https://dovetail.com/ux/prototype-usability-testing-guide/)

---

### 3.12 Clickable Mockups / Figma Prototypes

**What it is:** Interactive digital mockups built in tools like Figma, InVision, or Adobe XD that simulate the user experience of a real application. Users can click through screens, navigate flows, and interact with the interface -- but there's no real backend functionality.

**When to use:** Stage 2-3 (Solution + Demand Validation). After paper prototyping validates basic flows. When you need to test more realistic interactions, share remotely, or present to stakeholders/investors.

**What evidence it produces:**
- Usability data (task completion rates, time-on-task, error rates)
- User feedback on visual design and interaction patterns
- Feature comprehension and navigation clarity
- Stakeholder/investor confidence in the concept
- Source: [Figma](https://www.figma.com/resource-library/high-fidelity-prototyping/), [UXtweak](https://blog.uxtweak.com/how-to-test-figma-prototypes/)

**Time and cost:**
- Time: 3-7 days for a clickable prototype
- Cost: $0-200 (Figma has a free tier; premium testing tools cost extra)
- Testing tools: Maze, UserTesting, Lyssna, UXtweak
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Strengths:**
- Realistic user experience testing without code
- Can be shared remotely (link sharing)
- Collaborative -- teams can work simultaneously in Figma
- Catches usability issues before expensive development
- More convincing for investor demos than paper prototypes
- "Spending time upfront can save significant time (and money) in the larger stages of development"
- Source: [Redblink](https://redblink.com/figma-clickable-prototype/), [DevTeam.Space](https://www.devteam.space/blog/how-much-does-it-cost-to-build-a-figma-prototype/)

**Weaknesses:**
- Uses fake data -- users may not react the same way with real data
- No real functionality -- can't test actual value delivery
- More time-consuming than paper prototyping
- Interaction design limitations in Figma (complex animations, conditional logic)
- Can create false confidence -- a beautiful prototype is not a validated business
- Source: [Redblink](https://redblink.com/figma-clickable-prototype/)

---

### 3.13 Ad Campaign Validation (Paid Ads to Landing Pages)

**What it is:** Running targeted paid advertising (Google Ads, Facebook/Meta Ads, LinkedIn Ads) that drives traffic to a landing page testing your value proposition. Measures click-through rates on ads and conversion rates on the landing page.

**When to use:** Stage 3 (Demand Validation). When you need to validate interest from strangers (not your network) at scale. Requires a clear value proposition and landing page.

**What evidence it produces:**
- Click-through rate (CTR) on ads -- does the value proposition attract attention?
- Cost per click (CPC) -- how expensive is it to reach your audience?
- Landing page conversion rate -- do they sign up/click CTA?
- Which audience segments respond best
- Which messaging/positioning resonates (through A/B testing)
- Source: [KickoffLabs, "Using Google Ads to Validate"](https://kickofflabs.com/blog/startup-validation-google-ads/)

**Time and cost:**
- Time: 1-2 weeks minimum (need enough data)
- Cost: $100-500 for initial test
  - Average Facebook CPC: $0.50 (so $100 = ~200 clicks)
  - Average Google Ads CPC: varies widely by industry ($1-5 typical)
- Source: [Data-Mania](https://www.data-mania.com/blog/how-to-test-a-new-product-idea-by-use-landing-pages-and-100-in-ads/), [GrowthMentor](https://www.growthmentor.com/blog/startup-idea-validation/)

**Conversion rate benchmarks:**
- Average Facebook ad conversion rate: ~8.95%
- Average Google Ads conversion rate: ~7.52%
- These vary massively by industry: Fitness 14.29%, Technology 2.31%
- For landing page email signups: 4.6% industry average is a reasonable baseline
- GrowthMentor case study: 16.89% conversion rate on $418 spend (75 signups) -- considered "very good"
- Source: [WordStream](https://www.wordstream.com/blog/conversion-rate-benchmarks), [GrowthMentor](https://www.growthmentor.com/blog/startup-idea-validation/)

**Platform selection:**
- **Google Ads:** Best for products where people are actively searching for solutions (intent-based)
- **Facebook/Meta Ads:** Best for products with broad appeal; good for testing messaging; often cheaper CPC
- **LinkedIn Ads:** Best for B2B with precise targeting by job title/industry; more expensive
- "Start with Facebook, test messaging, then transition to Google as you have something to sell"
- Source: [KickoffLabs, Facebook](https://kickofflabs.com/blog/startup-validation-facebook-ads/), [KickoffLabs, Google](https://kickofflabs.com/blog/startup-validation-google-ads/)

**Strengths:**
- Tests interest from STRANGERS (not your biased network)
- Quantitative behavioral data at scale
- A/B test messaging and positioning
- Relatively cheap and fast
- Creates an email list for future outreach
- Source: [Foundr](https://foundr.com/articles/marketing/product-validation-google-ads)

**Weaknesses:**
- Requires ad platform knowledge and optimization skill
- Poor ad creative can kill a good idea (false negative)
- Clicking on an ad is NOT the same as paying for a product
- Need enough budget for statistical significance
- Privacy changes (iOS 14+) have reduced targeting precision
- Source: [Data-Mania](https://www.data-mania.com/blog/how-to-test-a-new-product-idea-by-use-landing-pages-and-100-in-ads/)

---

### 3.14 Crowdfunding as Validation

**What it is:** Launching a campaign on Kickstarter, Indiegogo, or similar platforms to gauge market demand by asking potential customers to pre-pay for a product that doesn't exist yet. Crowdfunding simultaneously validates demand, tests pricing, and generates development capital.

**When to use:** Stage 4 (Commitment/Business Validation). When you have a compelling concept, strong visuals/video, and want to test if strangers will put money down. Best suited for consumer hardware, creative projects, and physical products.

**What evidence it produces:**
- Dollar amount raised (proof of willingness to pay)
- Number of backers (size of early adopter market)
- Velocity of funding (how quickly you hit your goal)
- Backer demographics and comments
- Media attention and organic sharing
- Source: [Startup Grind](https://www.startupgrind.com/blog/do-successful-crowdfunding-campaigns-pick-kickstarter-or-indiegogo/)

**Time and cost:**
- Preparation time: 6-8 weeks minimum (campaign creation, video production, outreach)
- Video production: $0-$15,000+ (successful $25k campaigns typically spend $2k-6k on video)
- Marketing: $5,000-$10,000+ (ads, PR, social media)
- Platform fees: 5% + 3-5% payment processing
- Campaign runs typically 30-60 days
- Source: [LaunchBoom, "How Much Does a Kickstarter Campaign Cost in 2026"](https://www.launchboom.com/crowdfunding-guides/how-much-does-a-kickstarter-campaign-cost-updated), [VideoPrixie](https://www.videopixie.com/blog/crowdfunding-video-cost-benchmark-what-works-how-much-to-spend)

**Platform differences:**
- **Kickstarter:** All-or-nothing funding; focused on creative projects, tech; higher average pledges
- **Indiegogo:** Flexible funding option; better for tech, fitness, home improvement
- Campaigns with videos are much more successful (50% vs 30% without)
- Source: [LaunchBoom](https://www.launchboom.com/crowdfunding-guides/indiegogo-vs-kickstarter-whats-the-difference)

**Strengths:**
- **Actual money** -- the strongest validation signal
- Simultaneously validates demand AND funds development
- Direct access to early adopters for feedback
- Creates community and social proof
- Media coverage potential
- Source: [Crush Crowdfunding](https://crushcrowdfunding.com/crowdfunding-for-startups-using-kickstarter-and-indiegogo-to-grow/)

**Weaknesses:**
- **"Crowdfunding gets at how many and much people will pay you to solve the problem -- not whether you've actually solved it"**
- Expensive and time-consuming to prepare properly
- Success may be driven by marketing skill, not product quality (a poorly marketed great product can fail)
- Early adopters who back campaigns are NOT representative of mainstream market
- Sets delivery expectations you must meet
- Famous failure: Coolest Cooler raised $13M but faced production and fulfillment disasters
- Source: [Medium / Vijay Sundaram, "Crowdfunding Is No Panacea"](https://medium.com/@vijaysundaram/crowdfunding-is-no-panacea-for-product-market-fit-2248438f053), [ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S0883902621000859)

**Famous success examples:**
- **Pebble:** $10M+ from 68,000 backers (goal: $100,000)
- **Oculus Rift:** $2.5M from 10,000+ backers; acquired by Facebook for ~$2 billion
- **Exploding Kittens:** $8.8M from 219,000+ backers
- Source: [Enicomp](https://enicomp.com/case-study-crowdfunded-consumer-gadgets-that-succeeded/), [Inc.](https://www.inc.com/walter-chen/how-oculus-vr-crowdfunded-their-way-to-a-2-billion-business-a-6-step-checklist.html)

---

### 3.15 Explainer Video Tests (Dropbox-Style)

**What it is:** Creating a short video (2-4 minutes) that demonstrates how your proposed product would work, explains the value proposition, and includes a clear CTA (typically a waitlist signup or email capture). Published before the product exists. Measures interest through signups and shares.

**When to use:** Stage 2-3 (Solution + Demand Validation). When the product concept is difficult to explain in text alone, or when a demonstration is more compelling than a description. Especially powerful for novel or category-creating products.

**What evidence it produces:**
- Signup/conversion rate from video viewers
- View count and engagement (watch time, completion rate)
- Sharing and virality metrics
- Comments and qualitative feedback
- Source: [Yans Media, "Dropbox's MVP Explainer Video"](https://www.yansmedia.com/blog/dropboxs-mvp-explainer-video-case-study)

**Time and cost:**
- Time: 1-4 weeks depending on production quality
- Cost: $0-5,000+ (DIY screencast to professional production)
- Simple screencasts: free with tools like Loom
- Animated explainers: $1,000-5,000
- Professional production: $5,000+
- Source: [Yans Media](https://www.yansmedia.com/blog/how-to-create-perfect-mvp-video)

**Strengths:**
- Shows how the product works without building it
- Emotionally engaging -- video creates connection text can't
- Can go viral (massive reach potential at low marginal cost)
- Tests whether people "get it" based on your explanation
- Works for category-creating products that are hard to describe in words
- Source: [Shortform](https://www.shortform.com/blog/dropbox-mvp-explainer-video/)

**Weaknesses:**
- Video production can be time-consuming and expensive if you overthink it
- Poor video quality can create false negatives
- Viewers may be excited but never actually need or pay for the product
- Harder to iterate than a landing page (can't easily A/B test)
- Virality is unpredictable and hard to replicate
- Source: [Yans Media](https://www.yansmedia.com/blog/how-to-create-perfect-mvp-video)

**The Dropbox case study (canonical example):**
- Drew Houston created a 3-minute video demoing the product concept
- Targeted at tech early adopters; posted on Hacker News ("My YC app: Dropbox -- Throw away your USB drive") and Digg
- Included inside jokes aimed at the Digg community to create engagement
- Result: Beta signup list went from 5,000 to 75,000 OVERNIGHT
- Validated the value hypothesis: "Was file synchronization a problem that most people didn't know they had?"
- Source: [Thrive and Grow](https://thriveandgrow.com/2025/05/17/pre-launch-traction-how-dropbox-got-75000-signups/), [Founderli](https://www.founderli.com/post/how-dropbox-used-an-mvp-to-build-a-billion-dollar-business-and-how-you-can-too)

---

### 3.16 Social Media Validation / Audience Building

**What it is:** Using social media platforms to test product ideas, gauge interest, and build an audience before launching. Includes posting about the problem space, running polls, engaging in communities (Reddit, LinkedIn groups, Facebook groups), and measuring organic engagement.

**When to use:** Stage 1-3 (Problem through Demand Validation). Can start very early as a discovery tool and continue through launch. Different platforms serve different purposes.

**What evidence it produces:**
- Engagement metrics (likes, comments, shares, saves)
- Community responses to problem descriptions
- Direct feedback on solution concepts
- Audience size and growth trajectory
- Content resonance (which topics/angles get traction)
- Source: [MeetEdgar](https://meetedgar.com/blog/how-to-use-social-media-to-validate-your-digital-product-idea), [StartupEspresso](https://startupespresso.live/validate-startup-concept-with-social-media/)

**Time and cost:**
- Time: Ongoing; minimum 2 weeks for initial signal; ideally 4-8 weeks
- Cost: $0-350/month (free organic; paid tools for scheduling/monitoring)
- Build relationships for a few weeks BEFORE seeking feedback
- Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

**Platform selection:**
- **LinkedIn:** B2B products, professional services
- **Reddit:** Honest community feedback, niche problem spaces (r/startups, r/SaaS, industry subs)
- **Twitter/X:** Tech products, thought leadership
- **Instagram:** Visual/consumer products
- **Facebook Groups:** Niche communities around specific problems
- Source: [Upskillist](https://www.upskillist.com/blog/ultimate-guide-to-social-media-idea-validation/)

**Strengths:**
- Free or very cheap
- Access to large, diverse audiences
- Real-time feedback
- Can discover problems organically by monitoring conversations
- Builds an audience for eventual launch
- Source: [FasterCapital](https://www.fastercapital.com/content/Social-Media-Engagement-as-a-Startup-Validation-Tool.html)

**Weaknesses:**
- **VANITY METRICS ARE THE PRIMARY DANGER:** "Likes don't equal loyalty and comments don't guarantee sales"
- Followers do not equal customers. Likes do not equal revenue.
- Social metrics "can be easily manipulated with money -- you can literally pay to increase their numbers"
- Time-consuming to analyze at scale
- Platform algorithm changes can reduce visibility
- 42% of startups fail due to poor validation -- social media metrics can mask this
- Source: [Brighter Messaging](https://brightermessaging.com/blog/vanity-metrics-social-media/), [Hootsuite](https://blog.hootsuite.com/vanity-metrics/)

**What to measure instead of vanity metrics:**
- Website clicks from social posts
- Email signups from social audiences
- DMs asking about the product
- Actual sales or pre-orders driven by social
- Customer lifetime value connected to social campaigns
- Source: [Soup Agency](https://soup-agency.com/blog/the-decline-of-vanity-metrics/)

---

### 3.17 Email Campaign Validation

**What it is:** Building an email list (through landing pages, content, social media, referrals) and using email sequences to test interest, nurture leads, and validate demand before launch. Includes drip campaigns, surveys to subscribers, and pre-launch engagement measurement.

**When to use:** Stage 3-4 (Demand and Commitment Validation). After you have a growing waitlist or email list. Before launch, to gauge engagement and intent to purchase.

**What evidence it produces:**
- Open rates and click rates (engagement signal)
- Reply rates (high-intent signal)
- Survey responses from subscribers (qualitative data)
- Pre-order conversion from email list
- Unsubscribe rates (negative signal)
- Referral behavior (organic sharing signal)
- Source: [Prefinery, "Pre-Launch Email Campaign"](https://www.prefinery.com/blog/referral-programs/prelaunch-campaign/email-2/)

**Time and cost:**
- Time: 4-8 weeks pre-launch; at least 1 email per week throughout
- Cost: $0-200 (free email tools like Mailchimp for small lists)
- Target: 1,000+ emails is "a large enough audience to begin validating your product"
- Source: [Demand Curve](https://www.demandcurve.com/playbooks/product-hunt-launch), [Benchmark Email](https://www.benchmarkemail.com/blog/building-and-nurturing-a-customer-email-list-prior-to-a-product-launch/)

**Key metrics:**
- In SaaS, 30-60% of pre-signups typically buy for at least one month
- Product Hunt launches with primed email lists perform significantly better
- Harry's referral email campaign: 100,000 signups in one week
- Source: [Prefinery](https://www.prefinery.com/blog/referral-programs/prelaunch-campaign/email-2/)

**Strengths:**
- Direct line to potential customers (not algorithm-dependent like social)
- Can segment and test different messages
- Builds a warm audience for launch day
- Measurable engagement signals
- Relatively cheap at scale
- Source: [Gleam](https://gleam.io/blog/launch-page/)

**Weaknesses:**
- Requires an existing email list to be useful
- Email open rates are declining industry-wide
- Subscribers are not the same as customers
- Email fatigue is real -- too many emails cause unsubscribes
- Building a meaningful list takes time
- Source: [Mirasee](https://mirasee.com/blog/build-pre-launch-email-list/)

---

### 3.18 Pocket Test / Pub Test

These are two distinct but related informal validation techniques:

#### Pocket Test (Pocket Smoke Test)

Source: [Kromatic / The Real Startup Book](https://kromatic.com/real-startup-book/4-evaluative-market-experiment/pocket-smoke-test), [GLIDR Help Center](https://help.glidr.io/en/articles/1648437-pocket-smoke-test)

**What it is:** Interviewing a prospect or customer, then physically pulling a prototype out of your pocket to drive further discussion. "Pocket" refers to the fact that you have something tangible (a phone mockup, a physical prototype, a printed wireframe) that you can whip out during a conversation to make the abstract concrete.

**When to use:** Stage 2 (Solution Validation). During or immediately after problem interviews, when you want to test whether your specific approach resonates.

**What evidence it produces:**
- Whether the solution type is appropriate for the problem
- User expectations for interaction and features
- Whether users understand the product architecture
- Depth of enthusiasm (beyond polite interest)

**Time and cost:**
- Time: Hours to days (prototype creation) + interview time
- Cost: $0-200 (phone mockups in POP or InVision; 3D printed prototypes for hardware)
- Tools: Figma, InVision, POP (Prototyping on Paper), Arduino, Raspberry Pi

**Strengths:**
- Drives deeper, more concrete conversations than abstract descriptions
- Shows natural user interactions with the concept
- Low-cost way to test solution-market fit
- Works for both digital and physical products

**Weaknesses:**
- Primary bias: founders may over-explain or nonverbally guide participants
- Prototype fidelity affects feedback quality
- In-person only (can't do this remotely without adaptation)

#### Pub Test (Pitching to Strangers)

Source: [Jeremy A Boyd, "Validating Your Ideas on Strangers"](https://jeremyaboyd.com/post/validating-your-ideas-on-strangers), [LinkedIn, "The Importance of Pitching to Strangers in Bars"](https://www.linkedin.com/pulse/importance-pitching-strangers-bars-colgan-not-just-for-presidents)

**What it is:** Going to a public place (bar, coffee shop, meetup) and pitching your startup idea to complete strangers to test whether it can be communicated simply and whether it generates genuine interest.

**When to use:** Stage 1-2 (Problem and Solution Validation). Very early, when you're still refining how to explain the concept. Tests communication clarity and basic concept appeal.

**What evidence it produces:**
- Whether you can explain your idea simply enough for a stranger to understand
- Genuine (unfiltered) reactions from people with no reason to be polite
- Pitch iteration data (try different framings across multiple conversations)
- Whether the concept is inherently interesting/compelling

**Time and cost:**
- Time: An evening
- Cost: A few drinks
- Source: [Jeremy A Boyd](https://jeremyaboyd.com/post/validating-your-ideas-on-strangers)

**Strengths:**
- "Strangers in bars are better barometers because if you cannot convey value simply, then your pitch still needs practice"
- "Strangers care less about not hurting your feelings than people staking their professional image"
- Tests communication, not just the idea
- Forces extreme simplicity
- You can pitch, then move to a different table and pitch an improved version

**Weaknesses:**
- People in bars are NOT your target market (usually)
- "Many people will go into defensive mode where they try to tell you what you want to hear to de-escalate and get you to go away"
- Lack of domain expertise from respondents
- Not statistically meaningful
- Social setting may produce artificially positive or negative reactions
- Source: [Hacker News discussion](https://news.ycombinator.com/item?id=45696438)

---

## 4. Key Practitioners & Frameworks

### Rob Fitzpatrick -- The Mom Test

**Core idea:** If you follow the right approach, even your loving mom can't lie to you about your business idea. The problem isn't people lying -- it's founders asking bad questions.

**Three rules of The Mom Test:**
1. Talk about their life instead of your idea
2. Ask about specifics in the past instead of generics or opinions about the future
3. Talk less, listen more

**Three types of bad data:** Compliments, hypothetical fluff ("I would definitely..."), and wishlists ("It would be cool if...")

**Commitment and advancement:** Real validation comes from people giving you something of value -- time (follow-up meetings), reputation (introductions), or money (pre-orders).

Source: [Rick Lindquist notes](https://www.ricklindquist.com/notes/the-mom-test-by-rob-fitzpatrick), [Looppanel](https://www.looppanel.com/blog/customer-interviews), [Dualoop](https://dualoop.com/en-be/blog/the-mom-test-explained-by-rob-fitzpatrick)

### Steve Blank -- Customer Development

**The Four Steps to the Epiphany:**
1. **Customer Discovery:** Test hypotheses about customer problems and needs
2. **Customer Validation:** Develop a repeatable, scalable sales model
3. **Customer Creation:** Drive end-user demand
4. **Company Building:** Transition from learning to execution

**Key insight:** "Customer Development starts by testing your hypotheses outside the building." If Customer Validation fails, loop back to Customer Discovery -- don't just push forward.

Source: [Steve Blank](https://steveblank.com/tag/customer-development/), [Wikipedia](https://en.wikipedia.org/wiki/Customer_development), [UCSD Innovation](https://innovation.ucsd.edu/startup/startup-toolkit/Steve-Blank-CustDev.pdf)

### Teresa Torres -- Continuous Discovery Habits

**Opportunity Solution Tree:**
- Start with a desired outcome (business metric)
- Branch into opportunities (customer needs, pain points, desires)
- Branch into solutions
- Branch into assumption tests

**Key principle:** Frame opportunities as "customer needs, pain points, or desires -- NOT solutions." Test through small, rapid experiments. Maintain weekly customer touchpoints.

Source: [Userpilot](https://userpilot.com/blog/continuous-discovery-framework-teresa-torres/), [Product School](https://productschool.com/blog/product-fundamentals/opportunity-solution-tree)

### Eric Ries -- The Lean Startup

**Build-Measure-Learn loop:** Build the smallest thing (MVP) that lets you measure customer response, learn from the data, and iterate.

**Key contributions to pre-build validation:**
- Concept of the Minimum Viable Product
- Validated learning as the unit of progress
- Pivot-or-persevere decisions based on evidence
- Both Concierge MVP and Wizard of Oz as valid validation approaches

Source: [Various Lean Startup references throughout research]

---

## 5. Common Mistakes & Anti-Patterns

### Mistake 1: Building Before Validating

**"If you build it, they will come" is the deadliest anti-pattern.** Jared Friedman's analysis of 80 million-user platforms reveals 74% of failed startups began with solution fixation rather than problem discovery. Y Combinator data shows teams using problem-first validation achieve 3.2x faster product-market fit.

Source: [Itamar Novick](https://www.itamarnovick.com/startup-anti-pattern-4-if-you-build-it-they-will-come/)

### Mistake 2: Confirmation Bias in Interviews

Confirmation bias is "the tendency to seek, interpret, and remember information that confirms our pre-existing beliefs, while ignoring or rejecting contradictory evidence." Founders hear what they want to hear.

**Fix:** Have a non-founder conduct some interviews. Write down hypotheses BEFORE interviews. Track how many interviews invalidate vs confirm assumptions. Actively seek disconfirming evidence.

Source: [LinkedIn](https://www.linkedin.com/advice/1/what-best-ways-avoid-confirmation-bias-startup)

### Mistake 3: The Friends & Family Fallacy

"89% of supportive acquaintances never convert to paying customers." 68% of failed founders "retrospectively acknowledged mistaking social validation for market validation." Your friends will tell you your idea is great because they love you, not because it's true.

Source: [Fundable Startups](https://www.fundablestartups.com/blog/validation-mistakes), [Founders Network](https://foundersnetwork.com/startup-idea-validation-mistakes/)

### Mistake 4: Treating "Cool!" as Validation

Just because people say "this is great, I could use this" doesn't mean they'd pay. Hearing "cool idea!" is the compliment trap from The Mom Test. The only reliable signal is a commitment of time, reputation, or money.

Source: [HubSpot](https://www.hubspot.com/startups/scaling-smarter/how-to-validate-startup-idea)

### Mistake 5: Surveying Before Interviewing

Surveys presume you already know the right questions. If you survey first, you'll get answers to questions that may not matter. Always interview first (discovery), then survey (quantification).

Source: [Iterative.vc](https://www.iterative.vc/post/5-validation-methods-to-validate-your-startup-idea)

### Mistake 6: Skipping the Sequence

Finance-driven teams demand ROI projections first. Engineering-driven teams build first. Marketing-driven teams wireframe first. All three skip problem validation. The correct sequence is always: Problem -> Solution -> Product -> Business.

Source: [David Rogers](https://davidrogersdigital.substack.com/p/the-four-stages-of-validation)

### Mistake 7: Waiting for 100% Certainty

"Follow the 80% rule: get just enough valid information from customer interviews and other data sources and then decide. You will never get to 100% certainty, and getting close will eat up an excessive amount of time."

Source: [ProductPlan](https://www.productplan.com/lean-market-validation-10-ways-rapidly-test-startup-idea/)

---

## 6. Case Studies

### Positive Case Studies

**Buffer -- Landing Page + Pricing Page MVP**
- Joel Gascoigne built a 2-page website: value prop page -> pricing page -> email signup
- Added pricing page specifically to test willingness to pay (not just interest)
- Result: 100 signups, 3 paying customers in month 1
- Built the real product in 7 weeks
- Source: [Buffer blog](https://buffer.com/resources/idea-to-paying-customers-in-7-weeks-how-we-did-it/)

**Dropbox -- Explainer Video MVP**
- 3-minute video demo posted on Hacker News and Digg
- Tailored with in-jokes for the Digg community
- Beta signups: 5,000 -> 75,000 overnight
- Validated the value hypothesis before building
- Source: [Thrive and Grow](https://thriveandgrow.com/2025/05/17/pre-launch-traction-how-dropbox-got-75000-signups/)

**Zappos -- Wizard of Oz MVP**
- Photographed shoes at malls, posted on website
- Manually bought and shipped shoes when orders came in
- Validated that people would buy shoes online without trying them on
- Result: Acquired by Amazon for $1.2 billion
- Source: [Verticode](https://www.verticode.co.uk/blog/zappos-mvp-example)

**Food on the Table -- Concierge MVP**
- CEO personally created meal plans and shopping lists for customers
- Went to stores with them, gathered preferences, iterated weekly
- Validated demand before building any technology
- Source: [iBuild MVPs](https://ibuildmvps.com/blog/the-concierge-minimum-viable-product-maximizes-customer-learning/)

**Robinhood -- Waitlist + Referral**
- Built a waitlist of 1 million+ users before launching
- Referral program: each user brought in an average of 3 additional signups
- Validated demand AND secured $13M in funding
- Source: [Prefinery](https://www.prefinery.com/blog/referral-programs/prelaunch-campaign/robinhood/)

### Cautionary Case Studies

**Coolest Cooler -- Crowdfunding Success, Execution Failure**
- Raised over $13 million on Kickstarter
- Faced production and fulfillment disasters
- Crowdfunding validated demand but could not validate execution ability
- Source: [Medium / Vijay Sundaram](https://medium.com/@vijaysundaram/crowdfunding-is-no-panacea-for-product-market-fit-2248438f053)

**General Statistic (from Y Combinator / Founders Network):**
- 34% of startups fail due to lack of product-market fit
- 74% of failed startups began with solution fixation rather than problem discovery
- 89% of supportive friends/family never convert to paying customers
- Source: [Founders Network](https://foundersnetwork.com/startup-idea-validation-mistakes/), [Itamar Novick](https://www.itamarnovick.com/startup-anti-pattern-4-if-you-build-it-they-will-come/)

---

## Quick-Reference: Technique Comparison Table

| Technique | Stage | Time | Cost | Evidence Strength | Signal Type |
|-----------|-------|------|------|------------------|-------------|
| Problem Interviews | 1-Problem | 2-4 wks | $0-500 | Moderate (qualitative) | Say |
| Solution Interviews | 2-Solution | 1-3 wks | $0-500 | Moderate (qualitative) | Say |
| Surveys | 1-2 | 1-2 wks | $0-200 | Weak-Moderate | Say |
| Competitive Analysis | 1 (ongoing) | 1 wk | $50-200 | Supporting input | Observe |
| Landing Page / Smoke Test | 3-Demand | 3-7 days | $100-500 | Moderate (behavioral) | Do |
| Fake Door Test | 3-Demand | 3-5 days | $0-100 | Moderate (behavioral) | Do |
| Waitlist Signups | 3-Demand | 2-8 wks | $0-500 | Moderate (behavioral) | Do |
| Pre-Orders / LOIs | 4-Commit | 4-8 wks | $500-2000 | Strong (financial) | Pay |
| Concierge MVP | 2-3 | 4-8 wks | $2K-5K | Strong (behavioral+pay) | Do + Pay |
| Wizard of Oz MVP | 3-Product | 2-4 wks | $500-2K | Strong (behavioral) | Do |
| Paper Prototyping | 2-Solution | Hours-3 days | $0-50 | Weak (usability) | Say |
| Figma Prototypes | 2-3 | 3-7 days | $0-200 | Moderate (usability) | Say + Do |
| Ad Campaign Validation | 3-Demand | 1-2 wks | $100-500 | Moderate (behavioral) | Do |
| Crowdfunding | 4-Commit | 6-8 wks prep | $5K-15K+ | Strong (financial) | Pay |
| Explainer Video Test | 2-3 | 1-4 wks | $0-5K | Moderate (behavioral) | Do |
| Social Media Validation | 1-3 | 2-8 wks | $0-350/mo | Weak (vanity risk) | Say |
| Email Campaign | 3-4 | 4-8 wks | $0-200 | Moderate (engagement) | Do |
| Pocket Test | 2-Solution | Hours-days | $0-200 | Moderate (qualitative) | Say + Do |
| Pub Test | 1-2 | An evening | A few drinks | Weak (informal) | Say |

---

## Validation Mix Recommendations by Situation

Source: [Naviu](https://www.naviu.tech/blog/how-to-validate-your-startup-idea)

| Situation | Focus | Recommended Methods | Budget | Timeline |
|-----------|-------|-------------------|--------|----------|
| Just starting out | Problem validation | Interviews, surveys, competitive research | $200-1,000 | 2-4 weeks |
| Have a concept | Product-market fit | Landing pages, prototypes, pre-sales | $1,000-5,000 | 4-8 weeks |
| Ready to scale | Growth validation | Partnerships, channel testing, unit economics | $2,000-10,000 | 6-12 weeks |
| Bootstrapped | Maximum learning per dollar | Social listening, research, surveys, landing pages | $100-500 | 1-3 weeks |
| Need fast answers | Quick insights | A/B testing, search analysis, expert interviews | $300-1,500 | 1-2 weeks |

---

---

## 7. DEEP DIVE: Sequencing Frameworks for Pre-Build Validation

This section addresses research question #2 from the brief: "How should founders sequence validation?"

### 7.1 Steve Blank's Customer Development Process (Four Steps)

Source: [Steve Blank, "Customer Development"](https://steveblank.com/tag/customer-development/), [Wikipedia](https://en.wikipedia.org/wiki/Customer_development), [Stanford PDF](https://web.stanford.edu/class/archive/engr/engr140a/engr140a/cgi-bin/MFP/wp-content/uploads/2015/03/Session-4-Customer-Development.pdf), [Scott Burleson summary](https://scottburleson.substack.com/p/book-summary-the-four-steps-to-the), [MaRS](https://learn.marsdd.com/article/the-customer-development-model-cdm-product-development-and-technology-startups/)

**The Four Steps:**

| Step | Name | Goal | Pre-Build? |
|------|------|------|-----------|
| 1 | **Customer Discovery** | Understand the customer problem and test hypotheses | YES -- core pre-build |
| 2 | **Customer Validation** | Develop a repeatable sales model | YES -- pre-scale |
| 3 | **Customer Creation** | Drive end-user demand at scale | No -- post-build |
| 4 | **Company Building** | Transition from learning to execution | No -- post-build |

**Customer Discovery has four internal phases:**

1. **State Your Hypotheses:** Write down core business assumptions -- customer problem, target audience, solution concept. Use Business Model Canvas. Be specific. Source: [MaRS Part 1](https://learn.marsdd.com/article/blanks-customer-discovery-method-part-1-the-customer-development-model-in-value-proposition/)

2. **Test the Problem (Get Out of the Building):** Develop a presentation based on hypotheses. Seek validation by speaking to people in and around target market -- potential customers, analysts, media. By end of this phase, you have an updated "problem statement." Source: [MaRS Part 2](https://learn.marsdd.com/article/blanks-customer-discovery-method-part-2-the-customer-development-model-in-value-proposition/)

3. **Test the Product Concept (Test the Solution):** Once you have deeper understanding of the customer problem, test your product idea to get a sense of relevance and attractiveness of your solution. Develop a basic version with just enough features to demonstrate value. Source: [MaRS Part 2](https://learn.marsdd.com/article/blanks-customer-discovery-method-part-2-the-customer-development-model-in-value-proposition/)

4. **Evaluate and Refine (Verify or Pivot):** Weigh information from phases 2 and 3. Consider whether to proceed with current plans or pivot. Key question: "Do people agree you're solving a high value problem, and do you understand your business model enough to start test selling?" Source: [MaRS Part 4](https://learn.marsdd.com/article/blanks-customer-discovery-method-part-4-the-customer-development-model-in-value-proposition/)

**Customer Validation (Step 2) sub-phases:**

- Build an MVP (not a full product -- just enough to test selling)
- Test sales and demand: "Release the MVP to a limited group of target users and gauge interest and willingness to pay"
- Develop a sales roadmap: duration of sales cycle, budget for purchase managers, sales scripts
- Exit criteria: "Business scale potential, a repeatable and scalable sales roadmap, and predictable sales funnel"
- Target customers at this stage: "Earlyvangelists" (Blank's term) / "Visionaries" (Geoffrey Moore's term in Crossing the Chasm)
- Source: [MaRS Customer Validation](https://learn.marsdd.com/article/develop-your-value-proposition-and-business-model-using-customer-validation/), [YourStory](https://yourstory.com/2020/10/startup-customer-entrepreneur-steve-blank)

**Critical concept -- the loop back:** If you can't find enough paying customers in Customer Validation, the model returns you to Customer Discovery to rediscover what you failed to hear or understand the first time. This is NOT failure -- it's how the process works. Source: [Steve Blank](https://steveblank.com/tag/customer-development/)

**"Get Out of the Building":** The most famous phrase from Blank's work. "There are no facts inside your building, so get outside to test them." Customer development starts with the key idea that there are no facts inside your building. Source: [Kauffman Entrepreneurs](https://www.entrepreneurship.org/learning-paths/the-lean-approach/getting-out-of-the-building-customer-development)

---

### 7.2 Eric Ries's Lean Startup -- Build-Measure-Learn & Pre-Build Validation

Source: [The Lean Startup](https://theleanstartup.com/principles), [Wikipedia](https://en.wikipedia.org/wiki/Lean_startup), [Lean Startup Co.](https://leanstartup.co/resources/articles/what-is-an-mvp/)

**The Build-Measure-Learn Loop:**

The Build-Measure-Learn feedback loop is the core engine of the Lean Startup. The team's effectiveness is determined by its ability to ideate, quickly build a minimum viable product, measure its effectiveness in the market, and learn from that experiment. Source: [Wikipedia](https://en.wikipedia.org/wiki/Lean_startup)

**But what about validation BEFORE building?**

Ries's key insight is that "Build" in Build-Measure-Learn doesn't mean "build a full product." It means build the smallest thing that generates learning. The question is NOT "Can this product be built?" but rather "Should this product be built?" and "Can we build a sustainable business around this set of products and services?" Source: [The Lean Startup Principles](https://theleanstartup.com/principles)

**Leap of Faith Assumptions:**

Every startup has "leap-of-faith assumptions" -- the riskiest elements upon which success depends. Ries identifies two critical ones:

1. **Value Hypothesis:** Does the product deliver value to customers once they use it? Test this FIRST. Source: [Blog URLaunched](https://blog.urlaunched.com/lean-startup-validation-value-growth/)

2. **Growth Hypothesis:** How will new customers discover the product? Test AFTER value is confirmed. Source: [Blog URLaunched](https://blog.urlaunched.com/lean-startup-validation-value-growth/)

Ries recommends carrying out the value hypothesis first, as "it makes sense to see if there is interest before seeing how many people are interested." Source: [Blog URLaunched](https://blog.urlaunched.com/lean-startup-validation-value-growth/)

**MVP as a Validation Tool (not a product):**

"It is not necessarily the smallest product imaginable... it is simply the fastest way to get through the Build-Measure-Learn feedback loop with the minimum amount of effort." Source: [Lean Startup Co.](https://leanstartup.co/resources/articles/what-is-an-mvp/)

Types of MVP that DON'T require building a product:

| Type | What It Is | Example |
|------|-----------|---------|
| **Landing Page MVP** | Web page describing features + CTA, before product exists | Buffer's pricing page test |
| **Concierge MVP** | Manual human delivery of the service | Food on the Table |
| **Wizard of Oz MVP** | Automated front-end, manual back-end (hidden from user) | Zappos |
| **Explainer Video MVP** | Video showing how the product would work | Dropbox's Hacker News video |
| **Piecemeal MVP** | Stitched together from existing tools (no-code) | Many early SaaS products |

Source: [Expert Program Management summary](https://expertprogrammanagement.com/2019/04/book-summary-lean-startup/), [Strategyzer](https://www.strategyzer.com/library/dont-build-when-you-build-measure-learn)

**Strategyzer's key reframe:** "Don't Build When You Build-Measure-Learn." The "Build" phase should use experiments and prototypes, not production code. Source: [Strategyzer](https://www.strategyzer.com/library/dont-build-when-you-build-measure-learn)

**Validated Learning:**

"The unit of progress for Lean Startups is validated learning -- a rigorous method for demonstrating progress when one is embedded in the soil of extreme uncertainty." The whole purpose of a startup is to obtain "validated learning" in order to "demonstrate valuable truths about a business prospect." Source: [The Lean Startup book](https://theleanstartup.com/book)

---

### 7.3 Rob Fitzpatrick's The Mom Test -- Deep Dive

Source: [The Mom Test book](https://www.momtestbook.com/), [Sachin Rekhi primer](https://www.sachinrekhi.com/the-mom-test-rob-fitzpatrick), [Michael Lynch notes](https://mtlynch.io/book-reports/the-mom-test/), [Rick Lindquist notes](https://www.ricklindquist.com/notes/the-mom-test-by-rob-fitzpatrick), [Dualoop summary](https://dualoop.com/en-be/blog/the-mom-test-explained-by-rob-fitzpatrick)

**The Three Rules:**

1. **Talk about their life instead of your idea.** "If you just pitch your idea, you lock the customer into agreeing politely instead of them telling you what the problem you can fix is." Source: [Atlanta Ventures](https://www.atlantaventures.com/blog/the-3-rules-to-customer-interviews-from-the-mom-test)

2. **Ask about specifics in the past instead of generics or opinions about the future.** "Would you buy a product which did X?" is a terrible question because people are overly optimistic about what they would do and want to make you happy. Instead: "How do you currently solve X and how much does it cost you?" Source: [Sachin Rekhi](https://www.sachinrekhi.com/the-mom-test-rob-fitzpatrick)

3. **Talk less and listen more.** "Active listening is essential as it prevents you from leading customers towards a certain answer." If you catch yourself saying "Thanks" or "I'm glad you like it" -- you're in the red zone. Source: [Atlanta Ventures](https://www.atlantaventures.com/blog/the-3-rules-to-customer-interviews-from-the-mom-test)

**Three Types of Bad Data:**

| Type | Definition | Examples | Fix |
|------|-----------|----------|-----|
| **Compliments** | "The fool's gold of customer learning: shiny, distracting, and worthless" | "That's so cool!" / "I love it!" | Deflect and return to their life |
| **Fluff** | Generic claims, future-tense promises, hypothetical maybes | "I usually..." / "I would..." / "I might..." | Ask for specifics: "When's the last time...?" |
| **Ideas/Feature Requests** | Customers misdiagnosing their own needs | "You should add X" / "It would be cool if..." | Probe motivation: "Why do you want that?" |

Source: [Michael Lynch notes](https://mtlynch.io/book-reports/the-mom-test/)

**Good Questions vs. Bad Questions:**

| BAD (Don't Ask) | WHY It's Bad | GOOD (Ask Instead) | WHY It's Good |
|-----------------|-------------|-------------------|---------------|
| "Do you think it's a good idea?" | Invites compliments, not facts | "What are your biggest goals right now?" | Focuses on their life |
| "Would you buy a product which did X?" | Hypothetical future; everyone says yes | "How do you currently solve X? What does it cost?" | Past behavior = truth |
| "How much would you pay for this?" | People overstate WTP to be polite | "What are you spending on this problem now?" | Actual spending = real data |
| "Would you use this?" | Hypothetical; no cost to say yes | "How often do you encounter this problem?" | Frequency = urgency signal |
| "What features would you want?" | Generates wishlists, not needs | "Walk me through the last time this happened" | Stories reveal real needs |

Source: [Sachin Rekhi](https://www.sachinrekhi.com/the-mom-test-rob-fitzpatrick), [TianPan.co](https://tianpan.co/blog/2025-04-29-the-mom-test)

**Currencies of Commitment (Fitzpatrick's Signal Strength Framework):**

The "currencies" of commitment, ranked from weakest to strongest:

| Currency | Examples | Signal Strength |
|----------|----------|----------------|
| **Time** | Agreeing to a follow-up meeting, trial usage, wireframe feedback session | Moderate |
| **Reputation** | Introducing you to peers/decision-makers, public testimonial, willing to be referenced | Strong |
| **Money** | Letter of intent, pre-order, deposit, actual payment | Strongest |

"The more they're giving up, the more seriously you can take what they're saying." Source: [Sachin Rekhi](https://www.sachinrekhi.com/the-mom-test-rob-fitzpatrick)

"People stop lying when you ask them for money." Source: [Dualoop](https://dualoop.com/en-be/blog/the-mom-test-explained-by-rob-fitzpatrick)

"A pipeline of concrete commitments is the only reliable signal that you're on the right track." Source: [Rick Lindquist](https://www.ricklindquist.com/notes/the-mom-test-by-rob-fitzpatrick)

**Meeting Success Criteria:**

"A meeting has succeeded when it ends with a commitment to advance to the next step." Interviews only have success and failure as outcomes -- no ambiguous "it was okay." If there's no clear next step or hard information obtained, it was a failed meeting. Source: [Dualoop](https://dualoop.com/en-be/blog/the-mom-test-explained-by-rob-fitzpatrick)

**Meeting Process (The Five Framing Components):**

1. **Vision:** You're an entrepreneur solving a problem
2. **Framing:** Here's the stage you're at
3. **Weakness:** Here's the specific question you need help with
4. **Pedestal:** Here's why THEY are uniquely qualified to help
5. **Ask:** Explicit request for help

Source: [Michael Lynch notes](https://mtlynch.io/book-reports/the-mom-test/)

**When Have You Validated Enough?**

"Keep meeting with customers until you stop learning new things." If 10 customers say different things, narrow your customer segment. Sometimes three to five meetings are enough -- if the segment is tight and patterns are clear. Source: [Michael Lynch notes](https://mtlynch.io/book-reports/the-mom-test/)

---

### 7.4 Teresa Torres -- Continuous Discovery Habits (Deep Dive)

Source: [Product Talk / Opportunity Solution Trees](https://www.producttalk.org/opportunity-solution-trees/), [Userpilot overview](https://userpilot.com/blog/continuous-discovery-framework-teresa-torres/), [Product School](https://productschool.com/blog/product-fundamentals/opportunity-solution-tree), [Chameleon](https://www.chameleon.io/blog/opportunity-solution-tree), [IxDF](https://www.interaction-design.org/literature/topics/continuous-discovery)

**Opportunity Solution Tree (OST) -- Full Structure:**

```
    [Desired Outcome]
         |
    [Opportunities]     ← customer needs, pain points, desires
    /     |     \
  [Opp A] [Opp B] [Opp C]
    |       |       |
[Solutions] [Solutions] [Solutions]   ← multiple solutions per opportunity
    |       |       |
[Assumption Tests]   ← break solutions into underlying assumptions
```

Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

**The Four Levels:**

1. **Outcome (Root):** A single, measurable business metric (e.g., increase retention by 10%). Sets scope for all discovery. Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

2. **Opportunities (Second Level):** Customer needs, pain points, and desires that, if addressed, will drive the outcome. NOT features or solutions. "Frame opportunities as customer needs, pain points, or desires -- NOT solutions." Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

3. **Solutions (Third Level):** Ideas for addressing an opportunity. Match to single opportunities. Consider multiple solutions per opportunity. Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

4. **Assumption Tests (Bottom Level):** Break each solution into underlying assumptions. Prioritize riskiest assumptions. Test 3 solutions simultaneously for compare-and-contrast. Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

**How to Build an OST:**

Step 1: Create an experience map from collected customer stories
Step 2: Map experience moments to top-level opportunities
Step 3: Group individual opportunities under relevant moments
Step 4: Structure branches with parent-child and sibling relationships

Revisit the opportunity space "every three to four customer interviews" (roughly monthly if doing weekly interviews). Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

**Compare and Contrast -- Testing 3 Solutions:**

"Compare and contrast at least 3 different solutions for your target opportunity." Decision-making research tells us when we compare and contrast our options, we make better decisions.

Rather than evaluating solutions directly, test assumptions underlying each solution. Test "the riskiest assumptions from each of your three ideas." This generates comparative data and prevents overcommitting to any one idea. Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

**How to Evaluate Assumptions:**

Categories to test: Desirability (do users want it?), Viability (can we sustain it?), Feasibility (can we build it?), Usability (can they use it?), Ethical (is there harm?). Source: [Userpilot](https://userpilot.com/blog/continuous-discovery-framework-teresa-torres/)

Set evaluation criteria BEFORE testing: e.g., "At least 3 out of 10 people will do X." Source: [Product Talk](https://www.producttalk.org/opportunity-solution-trees/)

**Weekly Cadence for Customer Interviews:**

Continuous discovery = "at a minimum, weekly touchpoints with customers by the team that's building the product where they conduct small research activities in pursuit of a desired product outcome." Source: [IxDF](https://www.interaction-design.org/literature/topics/continuous-discovery)

Torres recommends starting gradually: 1 interview/month → 1 every 3 weeks → 1 every 2 weeks → 1/week. Source: [UserInterviews blog](https://www.userinterviews.com/blog/how-to-interview-customers-continuously-with-teresa-torres-of-product-talk)

**Interviews discover opportunities; assumption testing evaluates solutions.** Different tools for different phases. Source: [Userpilot](https://userpilot.com/blog/continuous-discovery-framework-teresa-torres/)

---

### 7.5 Ash Maurya -- Running Lean (Problem/Solution Fit)

Source: [LEANFoundry](https://www.leanfoundry.com), [FourWeekMBA lecture summary](https://fourweekmba.com/running-lean-ash-maurya/), [Shortform summary](https://www.shortform.com/blog/running-lean-ash-maurya/), [LEANFoundry newsletter](https://www.leanfoundry.com/lean-1-2-3/apr-20-2024), [LEANFoundry newsletter](https://www.leanfoundry.com/lean-1-2-3/feb-24-2024)

**Three Stages of a Startup:**

| Stage | What It Means | Key Question |
|-------|-------------|-------------|
| 1. **Problem/Solution Fit** | Validate demand before building | "Have I found a problem worth solving?" |
| 2. **Product/Market Fit** | Validate the product works | "Have I built something people want?" |
| 3. **Scale** | Grow the business | "How do I accelerate growth?" |

"Problem/Solution Fit (not Product/Market Fit) is the first significant milestone of a startup." Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/apr-20-2024)

**The Demo-Sell-Build Model:**

Traditional: Build → Demo → Sell
Maurya's approach: **Demo → Sell → Build**

"Instead of build-demo-sell, it is demo-sell-build. That way we can go a lot faster as we can start with demos that not only helps us validate for market risk clearly, it also helps you to test what you're going to build." Source: [FourWeekMBA](https://fourweekmba.com/running-lean-ash-maurya/)

Instead of rushing to build out the solution, use a demo to define the solution first, then validate the solution at small scale, and finally verify the solution scales. Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/feb-24-2024)

**Running Lean Validation Sequence:**

1. **Create Your Lean Canvas:** Take your best guess at articulating a customer and problem hypothesis. Source: [Shortform](https://www.shortform.com/blog/running-lean-ash-maurya/)

2. **Problem Interviews:** Explore customer's worldview -- triggers and desired outcomes. Use "backdoor approach to problem discovery" -- don't lead with problems; extract them from customer stories. Source: [LEANFoundry / Ash Maurya](https://blog.leanstack.com/the-updated-problem-interview-script-and-a-new-canvas/)

3. **Solution Interviews / Demo:** Show the smallest demo possible to convince a customer you can solve their problem. Determine feasibility of solutions. Source: [FourWeekMBA](https://fourweekmba.com/running-lean-ash-maurya/)

4. **Sell Before You Build:** Turn the demo into a "mafia offer" and attempt to get commitments. If you can sell the demo, DON'T build the product yet -- you've validated demand. Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/feb-24-2024)

---

### 7.6 Strategyzer -- Testing Business Ideas (David Bland & Alex Osterwalder)

Source: [Strategyzer Book Summary](https://www.strategyzer.com/library/testing-business-ideas-book-summary), [Strategyzer Assumption Mapping](https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter), [Strategyzer Evidence Strength](https://www.strategyzer.com/library/how-strong-is-your-innovation-evidence), [Strategyzer Experiment Selection](https://www.strategyzer.com/library/how-to-select-the-next-best-test-from-the-experiment-library), [Strategyzer Experiment Library](https://www.strategyzer.com/library/experiment-library)

**The Assumption Mapping Framework:**

A team exercise where desirability, viability, and feasibility hypotheses are made explicit and prioritized.

**Step 1 -- Identify Assumptions:** Ask "What are all the things that need to be true for this idea to work?" Write each as "We believe that..." Use sticky notes color-coded by type.

**Step 2 -- Map on 2x2 Matrix:**
- X-axis: Evidence (have evidence ↔ no evidence)
- Y-axis: Importance (important ↔ unimportant)
- "Which hypothesis, if proven wrong, will cause our business idea to fail?"

**Step 3 -- Prioritize:** Focus on the top-right quadrant: critical beliefs with the least evidence. These are your near-term experiments.

Source: [Strategyzer Assumption Mapping](https://www.strategyzer.com/library/how-assumptions-mapping-can-focus-your-teams-on-running-experiments-that-matter), [Mural intro](https://www.mural.co/blog/intro-assumptions-mapping)

**Four Types of Hypotheses:**

| Type | Question | Risk Category |
|------|----------|--------------|
| **Desirability** | Does the market want this? | Market risk |
| **Feasibility** | Can we deliver at scale? | Tech/implementation risk |
| **Viability** | Is this profitable enough? | Financial risk |
| **Adaptability** | Can this survive changing environments? | Strategic risk |

Source: [Strategyzer](https://www.strategyzer.com/library/testing-business-ideas-book-summary)

**Evidence Strength Hierarchy:**

| Level | What It Measures | Examples | When to Use |
|-------|-----------------|----------|-------------|
| **Weak** | What people SAY (opinions) | Interviews, surveys | Early exploration |
| **Moderate** | What people INTEND to do | Stated preferences, sign-ups | After initial discovery |
| **Strong** | What people actually DO | Purchases, usage, behavior | For key go/no-go decisions |

"Interviews and surveys are fast to set up, but we all know that what (potential) customers and partners say and do are two different things." Source: [Strategyzer Evidence](https://www.strategyzer.com/library/how-strong-is-your-innovation-evidence)

"A simulated sale -- where the customer doesn't even know that she is part of an experiment -- can get you pretty close to a real world purchasing situation." Evidence strengthens "the closer you get to a real world buying example." Source: [Strategyzer Evidence](https://www.strategyzer.com/library/how-strong-is-your-innovation-evidence)

**Experiment Library (44 experiments):**

Two main categories:
- **Discovery experiments:** "Open ended and directional." Going from no evidence to light evidence. Cheaper, faster. Start here. Source: [Strategyzer Experiment Selection](https://www.strategyzer.com/library/how-to-select-the-next-best-test-from-the-experiment-library)
- **Validation experiments:** "More of a true value exchange." Going from some evidence to strong evidence. More expensive, take longer. Source: [Strategyzer Experiment Selection](https://www.strategyzer.com/library/how-to-select-the-next-best-test-from-the-experiment-library)

**Experiment selection principles:**
1. Start cheap and fast -- aim for 1 experiment per week, ~12 experiments over 12 weeks
2. Run multiple experiments per hypothesis to strengthen evidence
3. Select experiments producing strong evidence while respecting constraints
4. Defer building -- use "Wizard of Oz, Clickable Prototype and Single Feature MVP"
Source: [Strategyzer Experiment Selection](https://www.strategyzer.com/library/how-to-select-the-next-best-test-from-the-experiment-library)

---

### 7.7 Google Ventures Design Sprint (Jake Knapp)

Source: [GV Sprint](https://www.gv.com/sprint/), [The Sprint Book](https://www.thesprintbook.com/the-design-sprint), [Jake Knapp Day 5 Validate](https://library.gv.com/the-product-design-sprint-validate-day-5-761292b20d05), [Wikipedia](https://en.wikipedia.org/wiki/Design_sprint)

**The Five-Day Process:**

| Day | Activity | Goal |
|-----|----------|------|
| **Monday** | Map the problem | Agree on a long-term goal. Make a map of the challenge. Pick a target. |
| **Tuesday** | Sketch solutions | Review existing ideas. Each person sketches solutions. Four-step process emphasizing critical thinking. |
| **Wednesday** | Decide | Critique each solution. Choose winners. Weave into storyboard for prototype. |
| **Thursday** | Prototype | Build a realistic facade. "Fake it" philosophy -- customer-facing surface only. Finish in one day. |
| **Friday** | Validate | Interview 5 customers. Watch them react to prototype. Learn how far you have to go. |

Source: [The Sprint Book](https://www.thesprintbook.com/the-design-sprint)

**Day 5 -- Validation Details:**

"You'll show your prototype to five customers in five separate, 1:1 interviews." Five is the magic number -- after 5 customer interviews, big patterns emerge. Source: [Jake Knapp Day 5](https://library.gv.com/the-product-design-sprint-validate-day-5-761292b20d05)

**What makes this relevant for pre-build validation:**

The Design Sprint is a compressed validation cycle that goes from problem to tested prototype in 5 days. It's not a replacement for deeper customer discovery, but it demonstrates that you can get meaningful signal very quickly.

Over 200 sprints completed with startups including Slack and Airbnb, and companies including LEGO and Google. Thousands of teams worldwide use the format. Source: [GV Sprint](https://www.gv.com/sprint/)

---

### 7.8 IDEO's Design Thinking Process

Source: [IDEO](https://designthinking.ideo.com/), [IDEO U](https://www.ideou.com/blogs/inspiration/what-is-human-centered-design), [IxDF 5 Stages](https://www.interaction-design.org/literature/article/5-stages-in-the-design-thinking-process), [Stanford d.school](https://web.stanford.edu/~mshanks/MichaelShanks/files/509554.pdf)

**Five Stages of Design Thinking (Stanford d.school model):**

| Stage | Goal | Validation Role |
|-------|------|----------------|
| **1. Empathize** | Understand the user through observation, interaction, immersion | Problem discovery |
| **2. Define** | Synthesize insights into a clear problem statement | Problem definition |
| **3. Ideate** | Generate multiple possible solutions | Solution generation |
| **4. Prototype** | Build tangible models to test ideas | Solution materialization |
| **5. Test** | Gather feedback and refine | Solution validation |

Source: [IxDF](https://www.interaction-design.org/literature/article/5-stages-in-the-design-thinking-process)

**Critical Note on Sequence:** "These stages are not always sequential. Teams often run them in parallel, out of order, and repeat them as needed." The iterative, non-linear nature of design thinking means you can carry these stages out simultaneously, repeat them, and circle back. Source: [IxDF](https://www.interaction-design.org/literature/article/5-stages-in-the-design-thinking-process)

**IDEO's Three Lenses:** Convenience, Feasibility, and Viability. Human-centered design works at the intersection of these three. Source: [IDEO U](https://www.ideou.com/blogs/inspiration/what-is-human-centered-design)

---

## 8. DEEP DIVE: Signal Strength Framework

This section addresses research question #3: "When do you know you've validated enough?"

### 8.1 How Many Interviews Is Enough?

**Summary of recommendations from multiple sources:**

| Source | Recommendation | Context |
|--------|---------------|---------|
| Customer Dev Labs | 5 for initial patterns, 15-20 for comprehensive understanding | Problem interviews |
| Customer Dev Labs | 3 of 5 (60%) must be Early Adopters to move forward | Batch validation |
| Cindy Alvarez (Lean Customer Development) | 5 for initial patterns; stop when you stop being surprised | Problem interviews |
| LEANFoundry / Ash Maurya | 10-15 per phase (problem, solution, offer) | Running Lean 90-day process |
| Lenny Rachitsky (newsletter) | Median of 30 across successful B2B startups | Pre-build validation |
| Tyler Myracle (validation framework) | Minimum 30; no more than 5 from friends/network | Comprehensive validation |
| Qualitative research literature | 9-17 for code saturation; 16-24 for meaning saturation | Academic standard |
| NN/g (UX research) | 5 for usability testing patterns | Prototype testing |
| GV Design Sprint | 5 users on Day 5 | Sprint validation |
| Teresa Torres | 1 per week (ongoing); 3-4 before building OST | Continuous discovery |

Source: [Customer Dev Labs](https://customerdevlabs.com/2014/07/01/how-many-customer-discovery-problem-interviews-should-i-do/), [Customer Dev Labs](https://customerdevlabs.com/2017/04/10/how-many-customers-should-you-interview/), [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/jul-31-2025), [Lenny's Newsletter](https://www.lennysnewsletter.com/p/how-to-validate-your-b2b-startup), [Tyler Myracle](https://www.tylermyracle.com/articles/startup-validation-framework), [PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC9359070/), [UserInterviews](https://www.userinterviews.com/blog/how-to-interview-customers-continuously-with-teresa-torres-of-product-talk)

**The Practical Rule:**

"You're done interviewing customers when you bet $100 you know what the next one will say... and win." Source: [Customer Dev Labs](https://customerdevlabs.com/2014/07/01/how-many-customer-discovery-problem-interviews-should-i-do/)

**The 3-of-5 Rule:**

Interview in batches of 5. Once 3 out of 5 (60%) of the people you're talking to describe the same problems in the same way, you've found your Early Adopters. Move forward. Source: [Customer Dev Labs](https://customerdevlabs.com/2017/04/10/how-many-customers-should-you-interview/)

**If patterns aren't emerging by interview 5:**
Don't do more interviews -- narrow your customer segment. Vague segments (e.g., "small businesses") prevent pattern recognition. Specific niches produce consistent responses. Source: [Customer Dev Labs](https://customerdevlabs.com/2014/07/01/how-many-customer-discovery-problem-interviews-should-i-do/)

---

### 8.2 What Constitutes "Strong Signal" at Each Stage?

**Problem Validation -- Strong Signals:**
- People describe the same problem unprompted across multiple interviews
- They use emotional language ("I hate...", "It drives me crazy...", cursing)
- They've already tried to solve it (spent time/money on alternatives)
- They can tell you how much the problem costs them (time or money)
- They proactively ask for next steps or offer introductions

**Problem Validation -- Weak Signals:**
- People agree the problem exists only when you describe it
- "Yeah, that's kind of annoying" (low emotional intensity)
- They've never tried to solve it or even searched for solutions
- They can't quantify the impact

**Solution Validation -- Strong Signals:**
- "When can I get this?"
- They offer to pay before you ask
- They introduce you to others who need it
- They ask detailed "how does it work?" questions (genuine curiosity)
- They point out specific use cases you hadn't considered

**Solution Validation -- Weak Signals:**
- "That's a cool idea"
- "I could see someone using that"
- Generic enthusiasm without commitment
- No follow-up questions

**Demand Validation -- Strong Signals:**
- 5%+ conversion rate on landing page (email signup) from cold traffic
- People complete multi-step forms (high-friction = high intent)
- Pre-orders with actual payment
- LOIs from B2B customers
- Organic sharing / word of mouth
- People proactively reach out (cold inbound)

**Demand Validation -- Weak Signals:**
- Email signups under 2% from paid traffic
- High bounce rate on landing page
- Signups but no engagement with follow-up emails
- Interest only from friends/family/network

Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/jul-31-2025), [Lenny's Newsletter](https://www.lennysnewsletter.com/p/how-to-validate-your-b2b-startup), [Tyler Myracle](https://www.tylermyracle.com/articles/startup-validation-framework)

---

### 8.3 Conversion Rate Benchmarks for Landing Pages

| Benchmark | Rate | Source |
|-----------|------|--------|
| Average landing page conversion (all industries) | ~6.6% | [Unbounce Q4 2024 data](https://unbounce.com/average-conversion-rates-landing-pages/) |
| Below average (red flag) | <1% | [Unbounce](https://unbounce.com/landing-pages/whats-a-good-conversion-rate/) |
| Acceptable | 2-5% | [Unbounce](https://unbounce.com/landing-pages/whats-a-good-conversion-rate/) |
| Good | 5-10% | [Unbounce](https://unbounce.com/landing-pages/whats-a-good-conversion-rate/) |
| Very good (top 25%) | 10%+ | [Unbounce](https://unbounce.com/landing-pages/whats-a-good-conversion-rate/) |
| Excellent (top performers) | 11.4-40.8% | [Unbounce](https://unbounce.com/conversion-benchmark-report/) |
| Smoke test minimum viability | 0.5%+ | [Bundl](https://www.bundl.com/articles/techniques-validating-purchase-intention-in-4-easy-steps-the-smoke-test) |
| Smoke test minimum traffic | 1,000+ visitors | [Bundl](https://www.bundl.com/articles/techniques-validating-purchase-intention-in-4-easy-steps-the-smoke-test) |
| GrowthMentor validation case study | 16.89% on $418 spend (75 signups) | [GrowthMentor](https://www.growthmentor.com/blog/startup-idea-validation/) |

**Critical context:** Conversion rate varies enormously by industry, traffic source, and CTA type. Set YOUR threshold BEFORE running the test. Source: [Bundl](https://www.bundl.com/articles/techniques-validating-purchase-intention-in-4-easy-steps-the-smoke-test)

---

### 8.4 Lenny Rachitsky's B2B Validation Data

Source: [Lenny's Newsletter](https://www.lennysnewsletter.com/p/how-to-validate-your-b2b-startup)

**How many customer conversations before building (real data from successful B2B startups):**

| Company | # of Conversations | Approach |
|---------|-------------------|----------|
| Zip | 75 interviews over 2-3 weeks | Intensive listening |
| Stytch | ~30 over several months | Extended exploration |
| Gusto | Exactly 30 | Structured validation |
| Ramp | 100+ finance and founder teams | Broad outreach |
| Amplitude | 30 companies (wished he'd done 50) | B2B deep dives |
| Vanta | ~24 companies over 6 months | Long-cycle enterprise |

**Median: 30 potential customers.** Speak to at least 30, no more than 5 from friends/acquaintances.

**Four strong validation signals from Lenny's research:**

1. **Financial commitment:** "Several people start to (or offer to) pay for your early product, ideally people you don't have a direct connection to"
2. **Continued usage:** People keep using prototype despite poor quality
3. **Strong emotion:** Either "hatred for the incumbents (i.e. pain)" or "deep and strong emotional reaction to your idea (i.e. pull)" -- Gusto founder: "they started cursing... When you hear that strong emotion, then you know you have something"
4. **Cold inbound interest:** Unsolicited inquiries about your product

**Surprising statistic:** 40% of B2B startups pivoted at least once before finding their winning idea. Every prosumer product (Notion, Figma, Slack, etc.) took 2-4 years of wandering before they found something that worked.

---

### 8.5 The LEANFoundry 90-Day Validation Framework

Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/jul-31-2025)

**Three phases, 90 days:**

| Phase | Weeks | Activity | Success Threshold |
|-------|-------|----------|------------------|
| **Problem Discovery** | 1-4 | 10-15 behavioral interviews | At least 30% showing high problem intensity |
| **Solution Design** | 5-8 | Develop demos; test with fresh prospects | At least 30% showing strong interest |
| **Offer Delivery** | 9-12 | Design offer; request commitments | 80%+ commitment from qualified early adopters |

**The killer example:** "12 out of 15 architects committed to paying $5,000/month before he wrote a single line of code" -- an 80% conversion from qualified early adopters. Source: [LEANFoundry](https://www.leanfoundry.com/lean-1-2-3/jul-31-2025)

**Key distinction:** "There's a huge difference between 'I would buy this' and 'Take my money now.'" The framework measures actual behavior (commitments) rather than stated interest.

---

### 8.6 Tyler Myracle's Go/No-Go Checklist (15 Items)

Source: [Tyler Myracle](https://www.tylermyracle.com/articles/startup-validation-framework)

This is a practical checklist for evaluating whether you have enough signal to proceed:

1. Hair-on-fire problem severity
2. Unit economics viability
3. Existing budget or well-resourced decision-makers
4. Clear distribution wedge
5. Recurring B2B revenue model
6. Sticky/difficult-to-replace functionality
7. ACV supports 30-100 person company sales
8. Defensible competitive positioning (+4 versus incumbents)
9. Moat potential via data generation
10. Single decision-maker (no multi-function approval)
11. Crystal-clear ROI (cost savings or revenue generation)
12. Established large player precedent in space
13. Software, not services
14. Platform risk mitigation
15. 30+ customer conversations completed

**The "+4 rule":** Your solution must be at least 4 points better than incumbents on a 10-point scale. Anything less and switching costs prevent adoption. Source: [Tyler Myracle](https://www.tylermyracle.com/articles/startup-validation-framework)

**Signal strength criteria (need at least one):**
- "People we don't have a connection to have paid us money"
- Organic repeat usage without prompting
- Strong emotional response (hatred of alternatives, not polite interest)
- Non-trivial cold inbound demand

---

## 9. Case Studies (Expanded)

### 9.1 Positive Case Studies

**Dropbox -- Explainer Video MVP:**
- Drew Houston created a 3-minute demo video
- Targeted tech early adopters; posted on Hacker News ("My YC app: Dropbox -- Throw away your USB drive") and Digg
- Included inside jokes aimed at the Digg community
- Beta signups went from 5,000 to 75,000 OVERNIGHT
- Validated the value hypothesis: "Was file synchronization a problem that most people didn't know they had?"
- Source: [Thrive and Grow](https://thriveandgrow.com/2025/05/17/pre-launch-traction-how-dropbox-got-75000-signups/)

**Zappos -- Wizard of Oz MVP:**
- Nick Swinmurn photographed shoes at local malls, posted on website
- When orders came in, he bought from the store and shipped manually
- Customers had no idea it was manual
- Validated the core hypothesis: people will buy shoes online
- Result: Acquired by Amazon for $1.2 billion
- Source: [Verticode](https://www.verticode.co.uk/blog/zappos-mvp-example)

**Buffer -- Landing Page with Pricing Test:**
- 2-page website: value prop → pricing page → email signup
- Key innovation: pricing page tested willingness to pay, not just interest
- 100 signups and 3 paying customers in month 1
- Built the real product in 7 weeks
- Source: [Buffer blog](https://buffer.com/resources/idea-to-paying-customers-in-7-weeks-how-we-did-it/)

### 9.2 Cautionary Case Studies (Expanded)

**Juicero -- $120M Validation Failure:**
- Received $120 million from top VCs (Kleiner Perkins, Google Ventures)
- Built a $400 juice machine + proprietary juice packs
- A widely-shared demonstration showed people could squeeze the packs by hand -- no machine needed
- "Raised too much money too soon, encouraging them to build and launch without proper market validation"
- Collapsed within 3 years
- Source: [Medium / The Launch Path](https://medium.com/the-launch-path/the-launch-path-a-case-study-f3f72f141845)

**Google Glass -- Social Acceptance Blindspot:**
- Promised a wearable AR interface
- "Ran into trust and social acceptance barriers"
- "The prototyping process failed to validate whether users actually wanted or needed these capabilities in their daily lives"
- Failed to validate desirability in real social contexts
- Source: [Ideawake](https://ideawake.com/innovation-failures/amp/)

**Segway -- Solution Without a Problem:**
- Promised "a new mode of personal transportation"
- "What went wrong was adoption friction -- Segways were expensive, hard to store, and limited by infrastructure and regulation"
- "Solved transportation problems that weren't priorities for most consumers"
- Source: [Ideawake](https://ideawake.com/innovation-failures/amp/)

**Webvan -- Too Early, Too Big:**
- Online grocery delivery startup with ambitious logistics
- Built massive infrastructure "before the market was even used to ordering online"
- Market wasn't ready; infrastructure costs were unsustainable
- Source: [Ideawake](https://ideawake.com/innovation-failures/amp/)

**The pattern across failures:** "The more sophisticated the technical solution, the greater the risk of solving problems customers don't actually have." Source: [Scrum.org](https://www.scrum.org/resources/blog/5-examples-failed-products-lessons-product-validation)

---

## 10. Validation Anti-Patterns (Expanded)

Source: [Founders Network](https://foundersnetwork.com/startup-idea-validation-mistakes/), [Fundable Startups](https://www.fundablestartups.com/blog/validation-mistakes), [LinkedIn](https://www.linkedin.com/advice/1/what-best-ways-avoid-confirmation-bias-startup)

| Anti-Pattern | Description | The Fix |
|-------------|-------------|---------|
| **Building before validating** | 74% of failed startups began with solution fixation | Problem interviews FIRST, always |
| **Confirmation bias** | Hearing what you want to hear | Have non-founders conduct interviews; track disconfirming data |
| **Friends & family fallacy** | 89% of supportive acquaintances never convert | Max 5 of 30 interviews from your network |
| **Treating "Cool!" as validation** | Compliments ≠ commitment | Seek time, reputation, or money commitments |
| **Surveying before interviewing** | Surveys presume you know the right questions | Interview first (discovery), survey second (quantification) |
| **Skipping the sequence** | Finance teams demand ROI first; engineers build first | Always: Problem → Solution → Product → Business |
| **Waiting for 100% certainty** | Perfectionism kills momentum | 60-80% confidence is enough to move forward |
| **Leading questions** | "Wouldn't you find this feature useful?" | Use open-ended, behavior-focused questions |
| **Relying on verbal commitments** | "I would definitely buy that" ≠ actual purchase | Ask for real commitments: deposits, LOIs, pre-orders |

---

*End of research notes. These are raw research findings with citations -- not a final report.*

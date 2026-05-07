# Agent Prompt: Neko Health — JTBD-Led Competitive Landscape Analysis

## Context

Neko Health is a preventive health company that runs full-body scans using 70+ proprietary sensors (thermal cameras, 3D cameras, ECG, skin imaging, lasers, finger sensors). A Neko scan generates ~50M data points per session and covers cardiovascular health, metabolic markers, skin (including mole mapping), eye pressure, grip strength, and more. It costs £299/scan, is non-radiological (safe for annual use), and is followed by a doctor consultation. The company has a 100k+ person waitlist and 80% annual rebooking rate.

The goal of this analysis is **not** to compare Neko to other body scan companies. That's a narrow and already-documented category. Instead, the goal is to map the **jobs to be done** that Neko's product addresses — or should address — and then find what solutions exist in the market that serve those same jobs. This includes digital apps, wearables, communities, clinics, consumer biomarker tests, mental health tools, and anything else a person might reach for to get a job done that Neko is relevant to.

This analysis will be used for interview preparation for a Principal PM - AI/LLM role at Neko Health.

---

## What to research

### 1. Map the Jobs to Be Done

First, derive a clear list of the core jobs to be done (JTBDs) that Neko serves or could serve. Think about the full journey — not just what happens inside the scan, but what the person is trying to accomplish before, during, and after.

Frame each JTBD as a human outcome, not a feature. Use the format:
> *"When [situation], I want to [motivation], so I can [outcome]."*

At minimum, map JTBDs across these areas:
- **Reassurance and health confidence** — people who want to know they're okay before anything goes wrong
- **Early detection of serious conditions** — cardiovascular, cancer, metabolic, neurological
- **Skin and mole monitoring** — tracking changes over time, detecting skin cancer risk
- **Chronic condition management** — diabetes, hypertension, high cholesterol, obesity
- **Longevity and healthspan optimisation** — people optimising for a longer, healthier life
- **Health anxiety** — people who worry chronically about their health, may over-medically self-diagnose
- **GP/primary care gaps** — things that fall through the cracks of standard GP visits
- **Making sense of health data** — people who have data but don't know what to do with it
- **Accountability and behavior change** — people who need external accountability to change habits
- **Navigating the healthcare system** — finding the right specialist, understanding what tests to get

---

### 2. Competitive mapping by JTBD

For each JTBD above, identify 3–6 real competitors or alternatives that serve it today. These should be actual products, services, or approaches people use — not hypothetical.

For each competitor/alternative include:
- **Product name and category** (app, clinic, wearable, community, test kit, etc.)
- **How it addresses the JTBD** — specifically what job it does for the user
- **Key differentiator or limitation** compared to what Neko offers
- **Price point** if known
- **Who uses it** — what persona is this built for?

Do not limit yourself to direct Neko competitors (Prenuvo, Ezra, etc.). Think broadly:
- Consumer apps (Skin Vision, Miiskin, Cara Care, Levels, Zoe, etc.)
- Wearables (Oura, Whoop, Apple Watch, Ultrahuman, etc.)
- At-home test kits (Thriva, Medichecks, Everlywell, etc.)
- Telehealth/GP services (Babylon, Hims, Lemonaid, etc.)
- Longevity and functional medicine clinics (Wild Health, Parsley Health, etc.)
- Mental health and health anxiety tools (apps, CBT, therapy platforms)
- Communities and social accountability (Reddit, strava, accountability coaches)
- Corporate health programmes (Vitality, Bupa, health insurance add-ons)

---

### 3. Deep dive: Skin and mole tracking

This is an area where Neko has a specific scanner capability (mole mapping, skin cancer risk detection) but is not primarily positioned as a skin health product. Research:

- What consumer products exist specifically for skin and mole monitoring? (e.g. SkinVision, Miiskin, First Derm, DermaCompare, MoleScope, Haut.AI, etc.)
- What is the JTBD these serve — fear of melanoma? cosmetic tracking? annual dermatology gap?
- What are their limitations (e.g. no longitudinal full-body mapping, AI accuracy concerns, access to dermatologists)?
- What would Neko need to do to own this JTBD end-to-end?
- What is the size and urgency of this market?

---

### 4. Deep dive: Generalised health anxiety

Health anxiety (sometimes called hypochondria or illness anxiety disorder) affects a significant portion of people who are also Neko's most likely customers. This is an important segment to understand because:
- High health anxiety drives repeat scanning and engagement, but also creates risk of harm if the product amplifies anxiety
- The way Neko communicates results is critical for this segment
- There may be adjacent products that serve this JTBD better — or worse — than Neko

Research:
- What products or services currently serve people with health anxiety? (CBT apps, therapy, reassurance communities, GP access tools, etc.)
- How does health anxiety interact with preventive health scanning — does it help or hurt?
- What evidence exists on whether body scanning increases or reduces health anxiety over time?
- What design patterns work for communicating health risk information without amplifying anxiety?
- Who are the key players in the "health reassurance" space?

---

### 5. Gaps in the Neko product

Based on what you find, identify areas where:
- A JTBD is clearly relevant to Neko's user base but **Neko does not currently address it** (or addresses it poorly)
- Competitors are serving a job well that Neko could plausibly own
- There are emerging behaviours or products that signal unmet demand in adjacent spaces

Frame these as **product gaps and opportunity areas**, not feature requests. For each:
- Name the JTBD it connects to
- Who the primary persona is
- What the best current alternative is and why it's insufficient
- Why Neko is well or poorly positioned to own this

---

## Output format

Structure your output as follows:

### Section 1: JTBD Map
A list of 8–12 jobs to be done, each with: the JTBD statement, the emotional driver behind it, and the user segment most likely to have this job.

### Section 2: Competitive Landscape by JTBD
For each JTBD, a structured table or list of alternatives with: product name, category, what job it does, key limitation vs Neko, and price.

### Section 3: Skin and Mole Tracking — Deep Dive
Focused competitive and product analysis for this vertical.

### Section 4: Health Anxiety — Deep Dive
Analysis of the health anxiety segment: products, evidence, design implications.

### Section 5: Product Gaps and Opportunities
A prioritised list of gaps — areas where there is clear unmet demand that Neko could own.

---

## Notes

- Use real products and data wherever possible. If you reference a company, verify it exists and is active.
- Cite sources for any claims about market size, clinical evidence, or product features.
- Be opinionated where you can. The output should be useful for a PM who wants to walk into an interview and demonstrate they've thought beyond the obvious competitors.
- Do not spend time on Prenuvo, Ezra, or Human Longevity — these are already documented.

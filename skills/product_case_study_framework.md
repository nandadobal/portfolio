# Product Case Study Framework

A structured decision framework for live product case studies. Designed to move from ambiguous scenario → grounded recommendation with explicit trade-offs and measurable success criteria.

---

## Step 1 — Clarify the Situation & Understand the Goal

Before structuring anything, align on what you're actually solving for.

**Ask:**
- What is the business or product goal? (growth, retention, new market, cost reduction?)
- What does success look like from the company's perspective?
- Are there constraints I should know upfront? (timeline, resources, platform, regulation)
- Who is this decision for — and what do they need to walk away with?

**Output:** A one-sentence problem statement you can validate with the interviewer.
> *"So we're trying to [achieve X outcome] for [user/business], within [constraints], and success means [rough measure]. Is that right?"*

**Early hypothesis:** Form a rough hypothesis on what success might look like in metrics terms. You'll revisit this later — but anchoring early shows strategic instinct.
> *"My initial hypothesis is that success looks like [leading metric] improving by [rough magnitude], which would signal [lagging outcome]."*

---

## Step 2 — Identify User Personas & Jobs to Be Done

Resist jumping to solutions. Ground the problem in who you're building for and why.

**For each likely persona, define:**
- Who they are (role, context, mindset)
- Their primary **job to be done** — the functional, emotional, and social goal they're trying to achieve
- What they currently do today to get that job done (workaround, competitor, manual process)
- What's frustrating or broken about that

**Tips:**
- Name 2–3 personas maximum — don't try to serve everyone
- Identify which persona is primary (the decision-maker in prioritization)
- JTBD should be outcome-oriented, not feature-oriented: *"Help me know my body is okay before something goes wrong"*, not *"book a health scan"*

---

## Step 3 — Map the Real-World Journey

Understand how the pain point actually plays out today — before any new product exists.

**Walk through the current journey:**
1. What triggers the need? (the moment the job becomes urgent)
2. What does the user do first?
3. Where do they get stuck, confused, or drop off?
4. How do they resolve it today — and at what cost (time, money, effort, anxiety)?
5. What does "done" feel like for them?

**Look for:**
- Friction points worth eliminating
- Moments of trust or vulnerability (especially relevant in health)
- Gaps between what users think they want and what actually solves the job

---

## Step 4 — Solutions & Ideation

Generate distinct options before evaluating any of them. Breadth first.

**Aim for 3–4 meaningfully different solutions** — not variations on the same idea. Push for range:
- An incremental improvement to what exists
- A more ambitious bet
- An alternative framing of the problem entirely

**Tips:**
- Anchor each solution to the JTBD: *"This addresses [persona]'s job to be done by..."*
- Don't self-edit here — quantity matters, evaluation comes next
- Name each option clearly so you can reference it in scoring

---

## Step 5 — Evaluate Solutions: Feasibility, Desirability, Viability

This is where you turn options into a prioritized recommendation. Score each solution across three lenses, then look for the pattern.

### Feasibility — Can we build it?

| Dimension | Questions to ask |
|---|---|
| Technical complexity | How hard is this to build? Any novel engineering required? |
| Dependencies | Does this rely on third parties, APIs, data we don't own, or other teams? |
| Timeline | Can this ship in a meaningful timeframe? Is there a forcing function? |
| Team capability | Do we have the skills, or would we need to hire/partner? |
| Regulatory / compliance | Any legal, privacy, or clinical constraints? (especially in health) |

**Score: High / Medium / Low**

### Desirability — Do users actually want it?

| Dimension | Questions to ask |
|---|---|
| JTBD fit | How directly does this solve the job to be done for the primary persona? |
| Pain severity | How painful is the current alternative? Would switching feel worth it? |
| Evidence of demand | Is there qualitative signal, behavioral data, or analogues from other markets? |
| Ease of adoption | How much behavior change does this require from the user? |
| Emotional resonance | Does this feel right for the context? (trust, safety, confidence — especially in health) |

**Score: High / Medium / Low**

### Viability — Should we build it commercially?

| Dimension | Questions to ask |
|---|---|
| Revenue or growth impact | Does this drive acquisition, retention, upsell, or reduce churn? |
| Strategic alignment | Does it advance the company's positioning or long-term direction? |
| Competitive differentiation | Does this build a moat, or is it table stakes? |
| Resource cost vs. return | Is the investment proportionate to the expected return? |
| Sustainability | Is this a one-time lift or a compounding asset? |

**Score: High / Medium / Low**

---

### Reading the Scoring Pattern

| Pattern | Interpretation |
|---|---|
| High / High / High | Strong candidate — prioritize |
| High Desirability, Low Feasibility | High potential but risky — goes to assumption backlog |
| High Feasibility, Low Desirability | Easy to build, wrong to build — deprioritize |
| Medium across the board | Needs more definition — likely missing something |
| Low Viability despite strong FD | May be a feature, not a product — reconsider scope |

---

## Step 6 — Prioritize with Explicit Trade-offs

Make a call. Name your recommendation and explain the trade-offs you made to get there.

**Structure your recommendation as:**
1. **What you'd build** — one clear choice (or phased bet if genuinely warranted)
2. **Why this over the alternatives** — use the scoring to justify, not just assert
3. **What you're trading away** — explicitly name what you're deprioritizing and why
4. **Key risks** — one or two honest risks with your mitigation thinking

> *"I'd prioritize [Option B] because it scores highest on desirability and viability for our primary persona. The trade-off is [Option A]'s lower feasibility risk — but I'd rather validate demand before over-engineering the solution. The biggest risk is [X], which I'd mitigate by [Y]."*

### Assumption Backlog

Not everything you don't choose should be discarded. Solutions that scored well on 2/3 dimensions — or where a critical assumption is unvalidated — go into an assumption backlog for future discovery:

- High desirability but unproven? → Run qualitative research or a prototype test
- High feasibility / viability but uncertain demand? → Run a demand spike or concierge MVP
- High potential but regulatory unknown? → Discovery sprint with legal/compliance

This signals mature product thinking: you're making a decision *now* while being honest about what still needs to be learned.

---

## Step 7 — Define Success Metrics

Return to your early hypothesis and pressure-test it against your chosen solution.

**Define three layers:**

| Layer | What it measures | Example |
|---|---|---|
| **Leading indicator** | Early signal the solution is working | Feature adoption rate, task completion, repeat engagement |
| **Lagging indicator** | The outcome you ultimately care about | Retention, revenue, health outcome, NPS |
| **Guardrail metric** | What you must not break | Trust score, support volume, safety signals |

**Structure:**
> *"I'd measure success by [leading metric] within [timeframe], with a hypothesis that this drives [lagging outcome]. I'd watch [guardrail metric] closely to make sure we're not trading short-term engagement for long-term trust."*

---

## Quick Reference: Framework at a Glance

| Step | Purpose | Output |
|---|---|---|
| 1. Clarify & Goal | Align on the real problem | Problem statement + early metrics hypothesis |
| 2. Personas & JTBD | Ground in who and why | 2–3 personas, primary JTBD |
| 3. Real-world journey | Find actual friction | Key pain points and moments |
| 4. Ideation | Generate range | 3–4 distinct options |
| 5. FDV Scoring | Evaluate honestly | Scored options with patterns |
| 6. Prioritize | Make a call | Recommendation + trade-offs + assumption backlog |
| 7. Success metrics | Define what winning looks like | Leading, lagging, guardrail metrics |

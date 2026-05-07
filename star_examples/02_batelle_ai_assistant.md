# STAR Example 2: Batelle — Bringing the First D2C Generative AI Product to Market

**Role:** Head of Product  
**Theme:** AI/ML product, human-in-the-loop, 0→1 in Gen AI, commercial risk management

---

## Situation

Batelle was a sleep coaching company — a $1,500 premium product for parents, with a camera shipped to the home and 24/7 human sleep guides across time zones providing personalised support via chat. The model worked, but it was 100% human-powered and difficult to scale. When OpenAI released their APIs at the end of 2022, we had a narrow window to move fast and get ahead of the market.

Market size was capped. The human model had diminishing returns. We had the talent and the timing to act.

---

## Task

My task was to de-risk and execute a phased transition from a human-only model to a Gen AI-augmented product — while protecting customer trust and our refund rates. The business goal was to scale market size without breaking what made the product premium. I needed to prove feasibility, viability, and usability before committing.

---

## Action

I mapped out three categories of risk — feasibility, viability, usability — and ran them in sequence, starting with the riskiest:

**1. Feasibility (can we build something good enough?)**
I sat down with our CTO in London and gave us a 4-week time box to build *Alfred* — the internal predecessor to our public AI. Worst case, we'd have an internal tool that sped up our sleep guides. We measured *acceptance rate from sleep guides*: how often they'd send the AI suggestion as-is. We improved this iteratively through prompt engineering and a RAG knowledge base. We also ran a hidden pilot — AI-drafted messages, but a human checked before sending — to understand our baseline before any customer saw it.

**2. Viability (will it work commercially?)**
Partnered with the growth team to run a pricing analysis. I bypassed userinterviews.com and built our own no-code recruitment engine: Ads → Landing Page → Typeform → Zapier (qualify) → HubSpot → Calendly. Interviewed non-converted leads, current customers, and cold leads. Found the price point was $300–450 — enough to model margins for the scaled product and confirm the business case.

**3. Usability (will customers trust an AI?)**
This was the biggest risk. We ran a $200 pilot with 50 users — they got money back on completion. Measured NPS, programme progression, number of messages to AI vs. human, and qualitative feedback including price perception. Two key insights emerged:
- People didn't know what to ask → we added targeted suggestions
- Onboarding was critical to trust and engagement / personalization needed to feel personalized, not just be personalized. 

The human-in-the-loop wasn't just a safety net — it was a *trust architecture*. Keeping humans visible let us escalate edge cases, catch errors, and signal to customers that we hadn't abandoned them.

**4. Going to market**
In late 2022, we went live with a recommender system for sleep guides — a four-week market test. We then launched the first D2C Gen AI chatbot (Elle), measured continuously, and managed the transition carefully. Inside the org, I ran a two-pronged approach to get the team on board: education (showing sleep guides how to use AI tools, async where needed) and ground-up advocates — empowering the team to own the shift rather than fear it.

---

## Result

- **Message-to-human ratio moved from 100% → 80% → 26%** over the rollout period — a major efficiency gain
- Refund rates tracked as a continuous check on trust; we maintained our refund policy as a signal of confidence
- Measured: conversations, engagement, refund rate, message-to-human ratio
- The human-in-the-loop model was the key differentiator — it preserved trust while enabling scale
- Built a RAG knowledge base and an internal eval loop that became infrastructure for everything after
- We were among the earliest D2C Gen AI consumer products to market

---

## Key Talking Points for Interviews

- This is a genuine Gen AI 0→1 story with measurable outcomes, not just a "we experimented with AI" story
- The phased feasibility → viability → usability structure shows how to de-risk AI product launches systematically
- Human-in-the-loop wasn't a compromise — it was a product decision that built trust and enabled escalation
- The internal change management story (getting sleep guides excited about AI, not scared) is a strong stakeholder/team motivation example
- The eval loop and RAG infrastructure thinking was ahead of the curve — relevant in any conversation about AI product architecture today

---

## Metrics Summary

| Metric | Start | End |
|---|---|---|
| % messages handled by humans | 100% | 16% | (PROACTIVE ELLE)
| Pricing analysis sweet spot | — | $300–$450 |
| Pilot size (usability) | 50 users | — |
| Sleep guide acceptance rate | Baseline | Tracked iteratively |

# Neko Health — Interview Research Overview
*Compiled April 2026 | Role: Principal Product Manager — AI/LLM*

> **Name clarification:** The company is **Neko Health** (neko, not Nekko or Necco). Co-founded by Spotify's Daniel Ek and Hjalmar Nilsonne.

---

## The Actual Role (LinkedIn JD)

**Title:** Principal Product Manager — AI/LLM  
**Location:** London

**What it owns:** Defining and leading product vision for "building the world's best consumer interface for health." Specifically: LLM chat experiences, medical reasoning systems, diagnostic tools, member summaries, doctor pre-briefs, and workflow automation — across 20+ integrated product surfaces.

**Core deliverables:**
- Ship end-to-end AI/LLM products that are "simple, safe, and clinically trustworthy"
- Set quality standards and identify "10x opportunities for intelligence" across 20+ products
- Convert complex sensor and medical data into intuitive consumer experiences
- Reduce clinical workload through automation and improved data clarity
- Cross-functional leadership with engineering, design, medical, and data science

**What they require:**
- 10+ years PM experience with **deep, hands-on AI/ML/LLM product work** — not just adjacent to it
- Demonstrated track record turning complex technical systems into simple, high-taste UX
- Shipping AI/LLM at high velocity while maintaining safety, privacy, and clinical-grade trust
- Experience shaping AI strategy or quality bars across multiple product surfaces

**Preferred:**
- AI-enabled healthcare or medtech background
- Health summaries, diagnostic reasoning, or operational automation experience
- Leadership at top-tier AI, healthcare, or consumer companies

**The key phrase:** *"world's best consumer interface for health"* — this is a consumer product role with AI/LLM at its core, not a back-office clinical tools role. Think: what should the member experience look and feel like when they interact with their Neko health data via AI?

---

## 1. Company Overview

Neko Health is a Swedish preventive healthcare company that uses proprietary full-body scanning technology and AI to detect health risks before people get sick. Founded in 2018, the company's core thesis is that healthcare should be proactive — catching cardiovascular disease, metabolic conditions, skin cancer, and diabetes early — rather than reactive.

The name "neko" is Japanese for cat, referencing a cat's nine lives and the idea of longevity.

**Mission:** Shift healthcare from reactive to preventive. Give people a comprehensive picture of their health before conditions become serious.

**Customers:** General consumers, aged roughly 30–60, who are health-conscious and willing to pay out-of-pocket for preventive insight. No insurance currently accepted. Strong early-adopter, affluent demographic.

**Founding story:** Daniel Ek DM'd Hjalmar Nilsonne on Twitter in 2018 after Spotify's IPO, looking for a hard problem to solve. Neither has a clinical background (though Nilsonne comes from a family of doctors). They spent years building the hardware and software before launching.

---

## 2. Product

**Core product:** The Neko Health Check — a ~1 hour preventive health scan at a physical clinic.

**How it works:**
- Patient enters a cylindrical scanning chamber equipped with **70+ sensors** — thermal cameras, 3D/volumetric cameras, ECG, lasers, finger sensors
- Generates approximately **50 million data points** per scan
- Scans skin (mole mapping, skin cancer risk), cardiovascular system, metabolic markers (cholesterol, blood sugar, blood pressure, waist circumference), eye pressure, grip strength
- Only invasive element: a blood draw
- Followed by an **in-person doctor consultation** to review results and personalised recommendations

**The key differentiator from competitors:** Neko built its **own hardware** — proprietary scanning technology that is non-radiological (no MRI, no CT radiation). This is critical: it means annual or more frequent scanning is safe, and their data flywheel builds faster.

**Medical OS (the product role you're interviewing for):** The internal software platform that clinical staff and doctors use — workflow tools, clinical assessments, follow-up coordination, diagnostic support. This is the internal-facing product that makes the clinic operate. It is distinct from the consumer-facing health data app (which shows patients their results over time).

**Consumer app:** Patients can track their results, view their health data history, and monitor changes between annual scans.

---

## 3. Business Model

- **D2C, pay-per-scan with strong subscription dynamics**
- Price: **£299 per scan** in the UK (similar pricing in Sweden)
- Annual cadence encouraged — the model is built around people coming back every year
- **80% of customers rebook and pay in advance** for the following year — exceptional retention signal
- No paid marketing, no ads, no influencer deals — all organic demand
- 100,000+ person waitlist as of early 2025

**Unit economics signal:** High rebooking rate + growing waitlist + premium price point suggests strong margins once clinic utilisation reaches scale. Capital-intensive to open new clinics (custom hardware, space, staff) but the repeat revenue model is defensible.

---

## 4. Funding & Investors

| Round | Amount | Date | Valuation |
|---|---|---|---|
| Series A | $65M | July 2023 | — |
| Series B | $260M | January 2025 | $1.8B post-money |

**Investors:**
- **Lightspeed Venture Partners** (Series B lead — Bejul Somaia joining board)
- General Catalyst
- O.G. Venture Partners
- Rosello
- Lakestar
- Atomico
- Daniel Ek via his investment vehicle Prima Materia

**Notable:** Lightspeed's investment thesis explicitly calls out Neko's vertical integration (owning hardware + software + AI + data) as the key moat, and cites "zero paid marketing" traction as proof of genuine product-market fit.

---

## 5. Team & Leadership

| Person | Role |
|---|---|
| **Hjalmar Nilsonne** | CEO & Co-founder — engineering background (MSc Industrial Engineering, KTH Stockholm), family of doctors |
| **Daniel Ek** | Co-founder & Chairman — Spotify founder, funder via Prima Materia |
| **Bejul Somaia** | Board member (Lightspeed) |

The leadership team is deliberately lean. The company is ~6 years old, well-funded, and in a scaling phase. Product leadership is a clear gap they are hiring into — the Principal PM/Product Director roles are strategic hires, not backfills.

---

## 6. Recent News (2024–2026)

- **January 2025:** Closed $260M Series B at $1.8B valuation. US market entry named as top priority.
- **September 2024:** Opened first UK clinic in London — first expansion outside Sweden.
- **2024:** Second London clinic opened (larger, flagship).
- **2023:** $65M Series A. First clinical results published: of 2,707 people scanned in Stockholm, 14.1% required further medical treatment; 1% had severe cardiovascular, metabolic, or cancerous conditions detected.
- **Growth:** Waitlist went from 22,000 (Sept 2024) → 40,000 → 100,000+ (Jan 2025) with no paid marketing.

---

## 7. Competitive Landscape

| Company | Approach | Price | Key Difference vs Neko |
|---|---|---|---|
| **Prenuvo** | Full-body MRI | ~$2,499 | Radiation-free MRI but expensive, slower, not proprietary hardware. Reportedly the only profitable player (~$100M revenue 2024). |
| **Ezra / Function Health** | MRI + 160+ lab biomarkers | ~$1,100–$2,500 | Ezra acquired by Function Health. Lab-focused, not hardware |
| **Human Longevity (Health Nucleus)** | Premium concierge — MRI + genomics + metabolic | $25,000+ | Ultra-premium, small market |
| **Traditional private GPs/health checks** | Blood tests, GP consultation | Varies | Slow, fragmented, no hardware |

**Neko's differentiation:**
1. **Proprietary hardware** — no one else built 70-sensor non-radiological scanners
2. **Vertical integration** — own the device, the clinic, the AI, and the data
3. **Annual safety** — non-radiological means repeat scanning is safe (unlike MRI at scale, or CT)
4. **Price point** — £299 is accessible compared to Prenuvo ($2,499). Mass-market ambition.
5. **Organic demand** — 100k waitlist with zero marketing = genuine pull

**The "Apple of healthcare" framing** (referenced in press): Neko is building its own ecosystem — hardware + software + data — rather than relying on commodity diagnostic equipment. This creates a durable data moat that competitors can't easily replicate.

---

## 8. Market Context

**Market size:** The preventive health check market is nascent but large. The body scan segment alone saw significant growth in 2024. The broader preventive/longevity health market is often cited at $100B+.

**Key trends:**
- Growing consumer interest in longevity, healthspan, and early detection (driven by social media, podcasts like Huberman, Attia)
- Shift from "treat illness" to "prevent illness" — healthcare systems globally are under pressure; preventive is increasingly seen as the only scalable model
- AI-enabled diagnostics improving rapidly — detecting conditions from imaging that human clinicians would miss
- Wearables (Apple Watch, Oura) creating a habits layer that preventive clinic visits can plug into

**Regulatory context:**
- Neko operates in a complex regulatory environment: medical devices (their hardware), clinical software (Medical OS), and clinical practice are all regulated differently in UK (MHRA), EU (MDR/IVDR), and US (FDA)
- CQC registration (the one you know from Bia Care!) is exactly the kind of regulatory navigation Neko has to manage in the UK
- US expansion is the next regulatory frontier — FDA clearance will be a significant product challenge

**Insurance:** Currently entirely out-of-pocket. No reimbursement pathway yet. This is a strategic tension: it limits addressable market to affluent consumers but protects margins and avoids the complexity of claims.

---

## 9. The Principal PM AI/LLM Role — What It Actually Owns

This is **not** a back-office clinical tools role. It's a consumer-facing AI product role with clinical constraints. The framing "world's best consumer interface for health" is the north star.

**Core ownership:**
- **Member-facing AI/LLM experiences** — how members interact with their scan data via AI after they leave the clinic
- **Member summaries** — turning 50M data points into something a person can read, understand, and act on
- **Doctor pre-briefs** — AI-generated summaries that help Neko doctors prepare for consultations efficiently
- **LLM chat experiences** — conversational interface for members to explore their health data
- **Medical reasoning systems** — AI that interprets scan results in clinically appropriate ways
- **Workflow automation** — reducing administrative burden on clinical staff
- **Quality standards across 20+ surfaces** — setting the intelligence quality bar for all AI features across Neko's product portfolio

**Why this role is strategic right now:**
- Neko just raised $260M and is expanding to the US. The AI layer is what makes the product scale — you can't hire doctors fast enough to give every member a personalised experience. AI is the leverage.
- 80% of members rebook. The post-scan experience (the app, the summaries, the ongoing engagement) is what drives that loyalty. AI is central to making that experience compelling.
- 100k waitlist = massive data asset. The AI/LLM layer is how Neko monetises its longitudinal health data in a member-facing way.

**What they're looking for:**
- Hands-on LLM/AI product experience — not someone who "worked near AI" but someone who built eval loops, prompted models, shipped RAG systems
- Consumer product taste — this is a consumer experience role, not just a technical AI role
- Comfort with clinical constraints — safety, privacy, trust are non-negotiable rails
- Systems thinker who can own quality across 20 surfaces, not just one product

---

## 10. Interview Angles — Likely Themes & Hard Questions

**Theme 1: LLM product depth**
*"Walk me through an AI/LLM product you've shipped end-to-end. What was your eval framework?"*
→ Batelle is the primary answer: built Alfred (predecessor AI), RAG knowledge base, internal eval loop, acceptance rate from sleep guides as the quality gate. This is directly analogous to Neko building eval loops for clinical AI outputs.

**Theme 2: Safety + trust in AI**
*"How do you build an AI product that users trust, especially in a high-stakes context?"*
→ Batelle human-in-the-loop architecture: kept humans visible, enabled escalation, went from 100% → 16% human gradually. The trust wasn't an accident — it was designed. Neko's clinical AI needs the same architecture: "simple, safe, clinically trustworthy" is literally in their JD.

utility, comprehension, ToV, accuracy, 

**Theme 3: Quality bars across multiple surfaces**
*"The role spans 20+ products. How do you set and maintain quality standards at that scale?"*
→ Cleo re-architecture: eval quality was the #1 metric. Built the harness/platform that let quality be measured consistently across surfaces. This is exactly what Neko is asking for with "10x opportunities for intelligence across 20+ products."

**Theme 4: Consumer UX for complex data**
*"How do you turn complex, technical, or medical data into something a consumer actually understands and acts on?"*
→ Batelle: "people don't know what to ask" — added targeted suggestions. Onboarding matters. The AI was incidental; what people wanted was a trusted guide. For Neko: 50M data points per scan → what does the member actually need to see and do?

**Theme 5: 0→1 AI product with a phased risk approach**
*"How do you de-risk an AI product launch in a context where getting it wrong has real consequences?"*
→ Batelle's three-phase structure: feasibility first (internal tool, 4-week timebox), then viability (pricing/business model), then usability (50-person pilot, get money back on completion). This is a replicable framework Neko would want applied to clinical AI.

**Theme 6: Platform thinking vs features**
*"How do you decide when to build infrastructure vs ship features?"*
→ Cleo: shadow squad → POC → leadership buy-in → 2-month build → rollout. The multi-agent/tools-based architecture unlocked everything after. Neko's AI layer across 20 surfaces is exactly this kind of platform bet.

**Theme 7: Working in a regulated, high-trust environment**
*"What's different about building AI in a space where mistakes have clinical consequences?"*
→ Bia Care: CQC registration, EMR integration, clinical governance, real consequences for errors in patient records or prescriptions. You understand the difference between "acceptable error rate for a consumer app" and "acceptable error rate when a doctor is acting on your output."

**Theme 8: Live product sense exercise (very likely)**
*"Design the AI member experience for someone who just got their Neko scan results."*
→ Prep this cold. Think: what does a member feel immediately after a scan? (Anxious, curious, overwhelmed by data.) What does the AI interface need to do? (Translate, reassure, prioritise, give a clear next action.) What are the safety rails? (Never diagnose, always escalate to a doctor for anything serious.) How do you handle the 1% who got a serious finding?

---

## Key Talking Points for the Interview

1. **"I've shipped end-to-end Gen AI products — ahead of the curve"** — Batelle was among the first D2C Gen AI consumer products to market (late 2022/early 2023). RAG knowledge base, internal eval loop, phased rollout. This isn't "I've used LLMs" — it's "I built the eval infrastructure and shipped it."

2. **"I designed human-in-the-loop as a trust architecture, not a crutch"** — The Batelle story: going from 100% → 16% human wasn't just efficiency. Keeping humans visible was what made customers trust the AI. Neko needs exactly this: clinical AI that knows when to hand off to a doctor.

3. **"Eval quality is the first metric, not the last"** — Cleo re-architecture: eval quality was metric #1, before conversion, before retention. If the AI isn't good, nothing else matters. This is the right instinct for clinical AI and it's exactly what Neko's JD says.

4. **"I can set quality bars across a portfolio"** — Cleo: the tools-based/multi-agent architecture let quality be measured and improved consistently across surfaces. 20+ products at Neko need a shared intelligence quality bar, not 20 separate eval frameworks.

5. **"I understand the consumer psychology of health data"** — Bia Care: women didn't convert on the holistic programme because anxiety around health decisions is real. Batelle: the biggest risk was "will people trust an AI?" Consumer health AI has to be designed around emotional context, not just information delivery.

6. **"I de-risk AI launches with a structured feasibility → viability → usability framework"** — Batelle's three phases are directly replicable. For Neko: can the LLM summarise a scan accurately enough? (feasibility) Will members engage with it and find it valuable? (usability) Does it reduce clinical load enough to justify the build? (viability)

7. **"The world's best consumer interface for health data is the right framing"** — Show you've thought about what this means: not a chatbot bolted on, but a coherent intelligence layer that makes 50M data points feel like a conversation with a trusted doctor. Reference products that got this right (and wrong).

---

## Sources

- [TechCrunch — $260M Series B](https://techcrunch.com/2025/01/22/neko-the-body-scanning-startup-co-founded-by-spotifys-daniel-ek-snaps-up-260m-at-a-1-8b-valuation/)
- [TechCrunch — London launch](https://techcrunch.com/2024/09/03/neko-health-the-body-scanning-ai-health-startup-from-spotifys-daniel-ek-opens-in-london/)
- [Fortune — £1.4bn valuation](https://fortune.com/europe/2025/01/23/daniel-ek-body-scanning-startup-valuation-100000-people-lining-up-pay-299-for-health-check/)
- [EU Startups — Series B](https://www.eu-startups.com/2025/01/preventing-illness-not-treating-it-neko-health-raises-e250-million-to-expand-globally/)
- [Lightspeed investment thesis](https://lsvp.com/stories/why-were-investing-in-neko-health-the-future-of-healthcare-is-preventive/)
- [Welcome to the Jungle — Principal PM role](https://app.welcometothejungle.com/jobs/U9_sCKMR)
- [BeautyMatter — "Apple of Healthcare"](https://beautymatter.com/articles/is-neko-health-the-apple-of-healthcare)
- [Startup Riders — $3B preventive health race](https://www.startupriders.com/p/preventive-health-startups-function-neko-prenuvo)
- [Bloomberg — competing with Prenuvo](https://www.bloomberg.com/news/articles/2026-03-27/spotify-co-founder-is-behind-body-scan-startup-competing-with-prenuvo)

# Presentation Script

---

## Intro

I've spent just over a decade building D2C products in three domains that all ran on human trust before technology touched them: women's health, parenting, fintech. In each case the question wasn't just "can we build this?" It was: will people actually trust this to a tech product? I want to walk you through three moments where that question *was* the product. Bia Care, a health tech company I co-founded. Batelle, where I was VP Product. And Cleo, where I'm currently Product Director.

---

## 01 · Bia Care

### The Problem

In 2019, menopause care in the UK was broken in a specific way. 3 in 5 women couldn't access local NHS menopause services. The ratio of menopause experts to women aged 45–55 was 1:14,400. This wasn't a gap — it was a structural failure the market had accepted.

### The First Bet

Our first product was a 12-week lifestyle programme. The pilot worked, the waitlist looked strong, users loved it. But when it came time to pay, conversion was low. What people said they wanted and what they'd actually pay for were different things. We pivoted and refocused on the clinical core. That was a significant commercial learning for me: test willingness to pay early, follow the money signal, not the satisfaction score. Especially in the UK, where willingness to pay in healthcare is mixed.

### The Product

We moved to a clinical model focused on advice and prescription. I led the full infrastructure build: patient profiling, video consultations, EMR integration, end-to-end prescription workflows. We built regulation-grade note-taking that worked across multiple patients in the same consultation. That's how we became the first private group consultation clinic to be CQC registered. Clinical governance from day one.

The USP was group-based: women assigned to the right cohort for their profile, joining affordable shared appointments, receiving tailored plans through the web app. That's how we scaled the unit economics of telehealth while keeping care timely.

### The Impact

We became the first private company commissioned by the NHS for menopause care at primary care network level. Brought in specifically to address the shortage of menopause experts. £200k ARR across private and NHS. A patient population of 100,000 covered. We ran the ESME study with Imperial College London on 1,500 women, published the findings, and won the RCGP research award in 2021.

A footnote on the 12-week model. It wasn't a bad idea. It was too broad, and it didn't address the pain point people would pay for first: clinical care. Later in the business, we rebuilt it as a focused programme for women going through breast cancer, in partnership with GenesisCare. It worked. The lesson wasn't "don't build lifestyle programmes." It was "don't build them before you know who'll pay for them."

**Neko thread:** I've shipped consumer-facing products on top of regulated clinical infrastructure, and the NHS commissioned the result. Neko is doing the same at a different scale. The questions are the same. How do you build an ongoing relationship with a patient, not just a one-off touchpoint? How do you earn trust in a new technology? How do you innovate inside a clinical environment?

---

## 02 · Batelle

### The Problem

Batelle was a premium sleep coaching product: $1,500, hardware in the box, 24/7 access to expert sleep guides. $8M ARR. Tens of thousands of customers. NPS was high. Refund rates were at a comfortable level. The model worked.

But it wasn't scalable. Staffing for round-the-clock coverage was the ceiling. When OpenAI opened up their API in late 2022, we had a narrow window. The question wasn't whether AI could handle the volume. It was whether AI could preserve what made the product worth $1,500. I always think about new products in three lenses: commercial viability, customer desirability, technical feasibility. Our riskiest question was a desirability one. Would parents trust their child's sleep to an AI?

### The Bet

I'll never forget when I sat down with my CTO here in London at a co-working space and decided to pivot our product roadmap. Within four weeks, we built Alfred — a gen AI recommender that suggested messages to our sleep coaches in real time. The coaches would accept, reject or edit each suggestion. That gave us a built-in eval loop from day one, with 24/7 domain experts as judges.

Over the next six months, approval ratings went from 26% to over 70%. That wasn't just productivity for the guides. The real value was as a growing knowledge base we could take to market with a consumer-facing AI product.


### The Challenge

The challenge was that we went to market when people didn't know what to do with an AI. This was before ChatGPT went mainstream. Most people's experience with chatbots was asking Siri about the weather and getting their music turned on instead.

I did dozens of customer interviews myself. I used van Westendorp's price sensitivity analysis to figure out what people would pay. The conclusion: the value prop was still human expertise.

We built trust by giving parents a choice: message a human coach, or message Elle, our AI. Two behaviours emerged. Some parents tried Elle first and escalated. Others used different channels for different things. But people were choosing the AI two to one. 

The determining factor of usage: parents who had a great first experience came back. No surprises there, everyone who's ever built D2C knows onboarding matters. So we made Elle proactive — using profile data to reach out first with something tailored. The ratio shifted to 4:1 in favour of the AI. The purchasing behaviour was there. But we knew there was more we could do.

The second breakthrough: engagement still dropped off between sessions, during the day when sleep guides were available.

Parents were reading lessons in the app, but the content and the chat were disconnected. So we embedded conversation prompts directly inside each lesson. Contextual. One tap away. Not a support feature. A learning companion. Engagement doubled in some cohorts.

### The Impact

People came for the human. They stayed for the AI.

We changed how people behaved with AI. I'll never forget a mother who told me she didn't feel she was failing as a parent because of Elle. I knew it was a bot. It still made her feel better.

At launch, 80% of messages went to a human. By the end, 16%. The human-in-the-loop wasn't a compromise. It was a product decision. Keeping humans visible built trust, enabled escalation, and preserved the premium feel at a validated price point of $300 to $450.

The real asset was the feedback loop. Coaches and AI growing the knowledge base. The more data, the better it gets. The more it fits the user, the harder it is to leave.

**Neko thread:** A parent handing their child's sleep to an AI is a high-trust ask. Someone receiving a scan result that says "early signs of X" is higher stakes still. The design principles I used in 2022 — make the AI visible, keep the human accessible, build the escalation path before you need it — those apply directly to what you're building.

---

## 03 · Cleo

### The Problem

When I joined Cleo, the conversational architecture was brittle. Siloed teams, fragmented tech, a chat layer no single person fully understood. The product needed to become fundamentally different — an assistant that watches accounts, surfaces the right action at the right moment. The existing architecture made that impossible. And the window to act was closing.

### The Bet

The bet was: expose every Cleo product — savings, EWA, BNPL, credit — as a tool the AI can call when the moment is right. An orchestrator decides which agent responds. This was 2024. We were building the architecture the industry has since converged on.

The way I did it: two weeks, a working prototype. Then I took it to the CEO — not with a proposal, but with evidence. Got sign-off to run a parallel squad I was PMing while the main team continued, long enough to de-risk the bet before we committed the organisation. By the time we moved the full team of 50 across, the question wasn't whether — it was when. I did the hands-on PM work myself while setting direction for the wider org.

To do this, we tracked four metrics:
- Conversion
- Eval quality
- CS contact rate
- Retention

### What It Unlocked

This is what the architecture unlocked. Trigger, insight, action, reward. Payday hits. Cleo notices you've got £620 after bills. Proposes moving £200 to your France trip. You're now 70% there. That loop only exists because of the tools-based foundation. Every new Cleo product plugs in as a tool. No rebuild required.

### The Impact

All shipped, in full production. The Financial Assistant is now the primary surface inside a one-million-MAU app.

Week 4 retention of financial conversations is up 3x. That's the engagement loop working. CS contact rate dropped from 2.5% to 0.8% of conversations. Fewer things breaking, more trust.

On eval quality: the framework we built scores every AI response across seven dimensions — comprehension, repetitiveness, utility, accuracy, tone of voice, actions, and overall quality. It's not a single score. It's a structured quality gate. We went from 84% to 93% on it. That's what makes the number meaningful.

**Neko thread:** Money and health provoke the same anxiety. Both need an intelligence layer that earns trust not by claiming it, but by surfacing the right action at the right moment. I built that loop for financial services. The architectural pattern translates directly. The data is richer here, and the stakes are clinical. I'd like to build it for healthcare.

---

## 04 · AI in Practice — Preparing for Neko

I want to close on how I worked through this conversation, because the workflow and the thinking are the same thing. Two pieces of evidence.

### Research

The first is structured context. Before I engaged with anyone at Neko, I built out the competitive landscape, the user archetypes, the role itself. Linked in the deck. Not notes. The kind of foundation that makes every subsequent conversation higher-signal.

### Designing the Intelligence Layer

The second is a product thesis. I used the same workflow to design what I think Neko's intelligence layer should look like. The full architecture is linked, but the headline is this.

The thing I keep coming back to is: the model isn't the moat. A general-purpose AI knows medicine. Neko knows *you*. The same question — "my LDL is 112, what does that mean?" — gets two completely different answers depending on whether the AI can see your last scan, your dietary changes, your waist trend, and the ECG finding your doctor wants to discuss today.

The construct that makes that possible is what I'm calling a Health Context Object. A structured representation of what matters for each member — biomarkers, flagged findings, risk profile, trend triggers. The AI queries it through tools, grounds clinical claims through RAG, and routes serious findings to a doctor before they reach the member.

This is the same architectural move I led at Cleo: tools-based, agentic, built around the user's real state rather than a fixed conversation tree. It worked there. My sense is it's even more load-bearing here, because the data is richer and the stakes are clinical.

The full doc covers the eval framework, the member journey, the doctor pre-brief, and where it differs from a general-purpose model. Happy to go deeper on any of it.

What I want you to take from this section: I built all of it — the research, the architecture, this presentation — using the same AI workflow I run every day at Cleo. It's how I work. And it's how I'd start at Neko.

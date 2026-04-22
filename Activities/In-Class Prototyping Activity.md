# In-Class Prototyping Activity
## NBA 6045 — Session 11 (Apr 23, 2026)

**Duration:** 75 minutes
**Tool:** Lovable (lovable.dev)
**Groups:** 9 teams split into A (4–5 teams) and B (4–5 teams)

---

## Setup (Before Class)

- Assign teams to A or B.
- Post the concept cards (below) on a slide — one per group type. Students do NOT see the other group's concept until the debrief.
- Make sure every student has a Lovable account set up before class.

---

## The Hook (5 min)

Open with: "These are real pain points your classmates submitted anonymously before class today."

Read 2–3 of the raw submissions aloud (keep them anonymous). Then: "We're going to go from pain point to working prototype in 75 minutes. That's what lean product development looks like under real constraints."

---

## Concept Cards

### Group A: Campus Cafe Pre-Order

**Pain point:** "I waited a long time for my lunch. The line in Sage Atrium cafe was long and I was in a rush." *(Submitted anonymously, Apr 21, 2026)*

**Job to Be Done:** When I'm between classes and short on time, I want to get food without waiting in line, so I can eat and still make it to my next commitment.

**Product idea:** A simple mobile-first pre-order interface for a campus cafe: students browse a limited daily menu, place an order, and arrive at a specified pickup time.

---

### Group B: Rental Application Simplification

**Pain point:** "I had to fill out a background check rent application through an online portal. It asked me to upload multiple forms like my W-2, tax forms from the past two years, my license, proof of employment, and detailed bank statements. It was really inconvenient and tedious — and invasive." *(Submitted anonymously, Apr 21, 2026)*

**Job to Be Done:** When I'm applying for a new apartment, I want to verify my financial reliability quickly and securely, so I can move forward without repeatedly uploading sensitive documents to unfamiliar portals.

**Product idea:** A renter credential profile: a one-time setup where you upload and verify your documents once, then share a credentialed summary with any landlord in one click, with control over what is disclosed.

---

## Phase 1: Build Your MVP (20 min)

### Instructor framing (2 min before they start)

Say: "Your goal is not to build a complete app. Your goal is to test your riskiest assumption with the least possible work. What is the one thing you most need to learn? Build only that."

Ask them to answer — in writing, before prompting Lovable — the following three questions:

1. **What is our riskiest assumption?** (What would have to be true for this product to succeed, that we are least sure about?)
2. **What is the minimum we need to build to test that assumption?**
3. **Who is our user, and what is the one core action we want them to be able to take?**

Only after answering those three questions should they open Lovable and begin.

### Prompt structure guidance

Tell them their Lovable prompt should explicitly include:

- The user and their core pain point (one sentence)
- The single core action the MVP must support
- What to leave out (be explicit — Lovable will add features by default; fight the temptation)
- Tone and context (e.g., "simple, mobile-first, for busy college students")

**Example prompt structure (write on board):**

> "Build a simple [mobile/web] app for [user] who [pain point]. The only thing this MVP needs to do is [one core action]. Do not include [X, Y, Z — name the features you are deliberately excluding]. The design should feel [tone/style]. Keep it minimal."

**Remind them:** A smoke test landing page, a single-screen ordering flow, or a one-step form can be an MVP. More screens is not more learning.

---

## Phase 2: User Testing (15 min)

Each A team pairs with a B team. They swap: A tests B's prototype, B tests A's prototype.

### The testing protocol (post this on a slide)

**As the tester:**
- Do not explain the product before the user touches it.
- Watch silently as they try to complete the core action. Note exactly where they hesitate or get confused.
- Only after they finish (or get stuck), ask:
  - "What did you think this app was for, when you first saw it?"
  - "What would make you actually use this?"
  - "What confused you or felt missing?"

**As the builder watching your product being tested:**
- Do not coach. Do not explain. Resist the urge to say "oh, you just have to click..."
- Take notes. The confusion *is* the data.

### Teams record:
- 1 thing users understood immediately
- 1 thing users got stuck on or misunderstood
- 1 piece of feedback they did not expect

---

## Phase 3: One Iteration (10 min)

Back with your own team. Based on what you observed:

1. Name the **single most important thing** you learned.
2. Make **one change** to the prototype that directly responds to that learning.
3. Be ready to explain: "We learned X, so we changed Y."

Constraint: one change only. This forces prioritization.

---

## Debrief (20 min)

### Round 1: What did you build? (5 min)
One A team and one B team each do a 60-second demo. No slides — just show the prototype.

### Round 2: What did you learn? (8 min)
Structured rapid-fire across all teams:
- "What was your riskiest assumption going in?"
- "Did your testing validate or challenge it?"
- "What was your iteration, and why that one?"

### Round 3: Connect to the frameworks (7 min)

Instructor-led discussion:

- **On lean:** "How did the constraint of building only to test one assumption feel? What would you have built if I hadn't asked you to name the riskiest assumption first?"
- **On the Build-Measure-Learn loop:** "You just ran one cycle in 45 minutes. Startups at Rent the Runway or Dropbox ran versions of this over months. What's the tradeoff?"
- **On JTBD:** "Did the JTBD framing change what you built, versus if I'd just described the pain point? How?"
- **On user testing:** "What did you observe in Phase 2 that you would never have predicted by talking about the product in the abstract?"

---

## Instructor Notes

**Common failure modes to watch for:**
- Teams that build too much in Phase 1: intervene at the 10-minute mark if they are adding screens rather than deepening their core flow.
- Teams whose riskiest assumption is vague ("will people like it?"): push them toward something falsifiable ("will users understand what to do without being told?").
- User testing that becomes a conversation rather than observation: remind testers to watch first, ask second.

**The point of the one-iteration constraint:** Students will want to make many changes. Forcing a single change makes them argue about prioritization — which is the actual PM skill being practiced.

**Link to Sprint 3:** Remind them that their Product Requirements Document requires a vibe-coded prototype. This activity is practice for that. The discipline of writing the prompt — naming what to exclude — is what separates a useful prototype from an over-engineered one.

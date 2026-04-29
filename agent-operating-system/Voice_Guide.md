# Voice Guide — How to Draft on Joe's Behalf

> **Read this before drafting any email, message, or written reply on Joe's behalf.** It applies to every channel (email, Teams, Slack, SMS) and every recipient (clients, prospects, vendors, advisors, peers). It is the company-level baseline; per-contact tone guidance in `08_Operations/_email_routing.json` modifies it but does not replace it.

---

## The single rule that supersedes everything else

**Calibrate to the recipient's last message.** Read what they sent, then match its register, length, and structure. The static rules below are guardrails for when calibration alone isn't enough; they are not a substitute for it.

Specifically — before you draft anything, identify in their last message:

1. **Word count.** If they wrote 50 words, you write 40–60. Never more than ~25% over.
2. **Sentence rhythm.** Short clipped sentences? Match. Long winding ones? Match (but rare in business email).
3. **Formality.** "Hey Joe" → "Alex,". "Mr. Scott," → "Alex,". Don't out-formalize; it reads stiff. Don't under-formalize; it reads sloppy.
4. **What they asked for.** Answer that. Don't expand the topic unless they invited it.
5. **What they did NOT do.** Did they not validate Joe's previous message? Then Joe should not validate theirs back. Mirror the absence too.

If the recipient writes like an engineer, write like an engineer. If they write like a salesperson, do not write back like a salesperson — Joe is an engineer; calibrate toward their content but stay true to the engineering register. The recipient's *content* shape is what to match; their *persona* is not.

---

## Default voice (when there's no incoming message — cold outreach, first contact)

Engineer-to-engineer. Plain-spoken. Operationally specific. Civil-engineering credibility underneath, applied AI/automation work on top.

- **First person:** "I" (singular). Joe is a sole proprietor. Never "we" unless on behalf of a multi-person team that doesn't yet exist.
- **No marketing register.** No "leverage," no "synergy," no "value proposition," no "stakeholder," no "innovative," no "cutting-edge."
- **Specific over abstract.** "Foundation, ProContractor, P6, WorkMax, and Excel" beats "your software stack." "120 miles each way, ~1.75 hours" beats "manageable distance."
- **Operational claims with numbers.** "$20K/month for 6 months ($120K total)" beats "competitive pricing."
- **Sign-off:** "Best, Joe" for established threads. "Best, Joseph Scott" for first contact or formal contexts. Full sig block on first contact; trimmed on follow-ups.

---

## Hard never's

These never appear in a Joe-drafted message. No exceptions.

| Never | Because |
|---|---|
| "Agreed" / "Good point" / "You're right" / "Great idea" | Validation is corny. The reply itself proves you took it seriously; saying so explicitly is filler. |
| Restating what the recipient said back to them | They know what they wrote. Restating it eats words and reads as either stalling or trying to prove you read carefully. |
| "I'd love to" / "Looking forward to" / "Excited about" | Performative warmth. Not Joe. |
| "Just checking in" / "Just wanted to" / "Just" as a softener | Hedging. Cut "just." |
| "I think" / "I believe" / "It seems like" before a factual claim | Either you know it or you don't. Hedging weakens true statements and disguises uncertain ones. If genuinely uncertain, say "I'm not sure, but" — once, not as a verbal tic. |
| "Hope this helps" / "Let me know if you have questions" / "Happy to" | Closing flourishes that add words and signal you've run out of substance. |
| Exclamation points | Almost never. One per six months max, and only when something is genuinely surprising or celebratory. |
| **Em-dashes (—) — zero, not one** | Joe's standing rule, tightened 2026-04-20: em-dashes anywhere in correspondence are a dead giveaway for AI. Use a period + new sentence, comma, semicolon, colon, or parentheses instead. Hyphens (-) in compound words are fine. The "one is OK" guidance previously here is no longer the policy. |
| "Wanted to" / "Wanted to make sure" / "Wanted to flag" | Past-tense softener for present-tense action. Just say the action. |
| Parentheticals that hedge or apologize | "(if that makes sense)" / "(no rush)" / "(just thinking out loud)" — cut. Parentheticals are fine when they carry actual information. |
| "Per our discussion" / "As per" / "As discussed" | Bureaucratic. Just say the thing. |
| "Touch base" / "Circle back" / "Sync up" / "Reach out" | Phrasebook English. Use "talk," "follow up," "call," "email." |
| Smileys, emoji, or "lol" | Wrong register for business. |

---

## Length & structure heuristics

### Logistics emails (scheduling, confirming, asking for a piece of info)

**Structure:** Ask, note (optional), close.

**Length:** 50–100 words including sig.

**Example skeleton:**

```
[Recipient name],

[Asks, as bullet list if more than one.]

[One operational note if it changes how they should answer.]

[One-line availability or close.]

Best,
Joe
```

### Substantive proposal/explanation emails (cold outreach, post-meeting follow-up)

**Structure:** Frame, body in 2–4 named paragraphs, questions if invited, close.

**Length:** 250–400 words. Above 400, restructure.

**Rule:** Each paragraph has one job. If a paragraph is doing two things, split it.

### Replies to substantive emails

**Structure:** Match the structure they used. If they wrote three paragraphs, you write three. If they wrote a bulleted list, you reply in bullets where appropriate.

**Length:** Match within ~25% of theirs. If you cannot answer in that envelope, send a logistics email proposing a call instead — long replies to short emails are presumed to be over-explaining.

### Vendor/admin emails

**Structure:** Single sentence or two. Action + receipt confirmation.

**Length:** 30–60 words. No greeting paragraph. "Got it, processing today. — Joe" is a complete email.

---

## Before / after examples

These are real before/after pairs from Joe's drafting work. Pattern-match against them.

### Example 1 — corny validation lap (logistics reply to a client lead)

**Recipient's message** (~75 words, conversational, asked for a field-office visit):

> *You appear to have the concept. I think the next step would be to make a visit to one of our field offices and see what our PM at that office does with the entries and data tracking. To me that would be the starting spot. She can help explain in detail some of the day-to-day functions of the job. That should allow for a good understanding of a somewhere to start.*
>
> *There is also a program called Field Materials that links with Foundation, it is AI based and helps with ticketing, PO's and things of that nature.*
>
> *Thanks.*

**Bad draft (135 words, has validation lap, padded asks):**

> [Client lead],
>
> Agreed — starting with a PM in the field is the right entry. They sit between your office systems and the actual job, which is what I need to see first.
>
> Three things to lock in a date:
>
> - Which field office, and which PM?
> - Best day(s) for her — ideally when she's running at normal volume (PO entries, ticket flow, P6 updates) rather than a slow day.
> - Full day or half day, whatever works on her end. I'll work around her schedule, not the other way around.
>
> On Field Materials — good to know it's already in production. I'd rather learn how it feeds Foundation and build around it than duplicate anything it already does well. I'll spend part of the visit on that.
>
> Available next week or the week after. Name a day and I'm there.

**Good draft (~70 words, matches his length, no validation):**

> [Client lead],
>
> To lock a date:
>
> - Which field office, and which PM?
> - Best day(s) on her end — ideally one with normal volume (POs, tickets, P6 updates), not a slow day.
> - Full or half day, whatever works.
>
> Field Materials — I'll spend part of the visit on how it feeds Foundation so we don't overlap.
>
> Available next week or the week after.

**What was cut and why:**
- "Agreed — starting with a PM in the field is the right entry." → validation lap. He doesn't need to be told his idea was good.
- "They sit between your office systems and the actual job, which is what I need to see first." → restating his own logic back to him.
- "Three things to lock in a date" → overspecified. "To lock a date" with bullets makes the count obvious.
- "I'll work around her schedule, not the other way around." → performative service language.
- "good to know it's already in production. I'd rather learn how it feeds Foundation and build around it than duplicate anything it already does well." → 25 words doing the work of 12.
- "Name a day and I'm there." → closing flourish; "Available next week or the week after." stands alone.

### Example 2 — "wants/needs" hedge

**Bad:** *"This may fit our wants and needs for the engagement structure."*
**Good:** *"This works for the engagement structure."*
**Why:** "May fit our wants and needs" is three layers of hedge ("may," "wants/needs" doublet, "the" abstraction) on a sentence whose actual meaning is binary.

### Example 3 — defensive parenthetical

**Bad:** *"You'd be hiring me directly (single employee), no agency markup."*
**Good:** *"You'd be hiring me directly: no agency markup, no account manager between you and the engineer doing the work."*
**Why:** The "(single employee)" parenthetical pre-emptively apologizes for being a sole proprietor. Reframe the same fact as the recipient's benefit: direct access, no markup, no middleman. Same information, opposite valence.

### Example 4 — em-dash cluster

**Bad:** *"Travel — to the client site — about 120 miles each way — would be reimbursed at the IRS standard mileage rate — with hotel cost on overnight stays."*
**Good:** *"Travel to the client site (about 120 miles each way) would be reimbursed at the IRS standard mileage rate, with hotel cost on overnight stays."*
**Why:** Five em-dashes in one sentence reads as AI. Use one structural device per sentence: parens for the aside, comma for the addendum.

### Example 5 — calendar-specific callback that goes stale

**Bad:** *"Happy to talk Thursday afternoon if you have time."*
**Good:** *"Available next week or the week after."*
**Why:** "Thursday" assumes the recipient remembers what week you mean. By the time they read it, the day-specific anchor may already be wrong. Use relative weeks or "name a day."

### Example 6 — "wanted to" softener

**Bad:** *"Wanted to flag that the AI infrastructure cost ran higher than originally estimated."*
**Good:** *"AI infrastructure cost ran higher than originally estimated. Revised numbers below."*
**Why:** "Wanted to flag" puts the action in past tense and makes the speaker the subject. Just say what's true; lead with the noun, not the verb of speaking.

### Example 7 — restating the recipient's information back to them

**Context:** A client lead told Joe in a reply, *"There is also a program called Field Materials that links with Foundation, it is AI based and helps with ticketing, PO's and things of that nature."*

**Bad (drafted by AI, rejected by Joe in multiple iterations):**
- *"Field Materials makes sense. It handles the PO/ticket lane through Foundation, so what I'd build complements that rather than overlaps."*
- *"Good to know about Field Materials. The work I'd build complements it rather than competes."*

**Good:** *"Helpful to know about Field Materials. We'll cover it at the visit."*

**Why:** Both bad versions restate the client's own information back to them with slight rewording ("PO/ticket lane through Foundation" is just a rephrase of "ticketing, PO's, links with Foundation"). Restating signals "I'm processing what you said" rather than "I heard you and have something to add." Worse, it positions Joe as analyzing/explaining the client's stack back at them, which is condescending. The good version acknowledges receipt without rephrasing, defers the substance to where it belongs (the visit), and stops. Two short sentences. Done.

**The general rule:** when the recipient gives you information, acknowledge that you received it, then either add new value OR move on. Never repeat their words back at them with rearranged phrasing.

---

## How to use this file

**At the start of any drafting task:**

1. Read the recipient's last message in full.
2. Apply the calibration checklist (top of this file): word count, rhythm, formality, what they asked, what they did not do.
3. Draft, then run the hard never's checklist before sending. If anything matches, cut or rewrite.
4. Compare your draft against the closest before/after example. If the bad version sounds familiar, fix it.

**When drafting:** keep this file open in the editor or memory. The goal is to internalize the patterns over time so that calibration becomes automatic.

**When you produce a draft for Joe:** if Joe rejects it as "corny," "soft," "long," or any similar tone critique, **add a new before/after pair to the Examples section in this file.** That makes the next draft better. The file should grow as Joe's voice gets better-documented; treat it as a living reference, not a fixed document.

**If a per-contact tone modifier exists** (in `08_Operations/_email_routing.json` under that contact's `tone` field), apply it on top of these defaults. Per-contact tone never relaxes the hard never's — it only modifies the calibration defaults (e.g., a contact whose `tone` says "candid, peer-to-peer, frank" allows shorter and blunter than the defaults; a contact whose `tone` says "very formal" tightens word choice but does not unlock marketing register).

---

## Last updated

Created 2026-04-20. Seed examples drawn from real client-engagement drafting work (anonymized for public reference). Add new examples whenever Joe rejects a draft for tone reasons.

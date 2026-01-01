# The Validation: Cornell Tech, December 2024

*Second in a series about my AI lecture tour through Ivy League and international universities*

---

## Four Days

OpenAI released o1 on December 5, 2024.

My Cornell Tech lecture was December 9, 2024.

Four days.

For months I'd been doing something I couldn't fully explain to anyone - forcing AI models to reason through information before generating outputs, creating these massive primed contexts that "thought" before they "spoke."

And then OpenAI released a model that did exactly that, built into the architecture. They called it "reasoning."

I'd been calling it "my secret technique that I hope gives Andromeda a competitive advantage."

## The Moment

Standing in front of a room of Cornell Tech graduate students, I could finally point to something external and say: "This. This is what I've been doing manually. They just automated it."

o1 was four days old. Most people hadn't even tried it yet. But I understood immediately what it meant - the pattern I'd discovered through trial and error was now a product feature.

"We've been doing this manually for months," I told them. "They just baked it into the architecture."

## The Proto-RAG Technique

I explained it fully for the first time:

- Take your entire documentation, codebase, context
- Stuff it into a model with a massive context window (Gemini Pro had 2M tokens)
- Ask the model to index itself - create a table of contents of what it now knows
- Ask it key questions to establish understanding
- Feed more context, repeat the indexing
- When the conversation is "primed," fork it - use that baseline for any task

This was chain-of-thought prompting before it had a name. Force the model to organize and understand before asking it to produce anything.

The needle-in-haystack tests I ran showed it worked. The model with proper context priming was never wrong about our system. Meanwhile, everyone else was complaining about hallucinations and unreliability.

They were using the tools wrong.

## The Room

Cornell Tech's graduate CS students were sharp. They got it immediately.

When I explained that OpenAI had just validated this approach four days earlier with o1, you could see the recognition. The "oh shit, this is real" moment.

This wasn't theoretical. This wasn't futurism. This was happening right now, and I'd been ahead of the curve.

## The Split Presentation

Leif covered the Andromeda protocol specifics - ADOs, the blockchain architecture, the technical roadmap.

I was supposed to do that too. But honestly, nobody cared about blockchain.

When I pivoted into AI - the history, the tools, the techniques, what was coming - that's when the room woke up. So I leaned into it. Blockchain got the minimum viable coverage. AI got everything else.

This became the pattern for all the lectures that followed.

## What I Covered

- The reasoning revolution (o1 as validation of manual techniques)
- My proto-RAG approach to context priming
- AI engineering stack: Cursor, AI Studio, Claude, Copilot
- Open source alternatives: LM Studio, Ollama
- Androptimus (our internal fine-tuned Gemini model)
- The coming shift in how software gets built

## The Frustration

I still couldn't fully let go.

Part of me wanted to open-source the entire technique, write it up, share everything I'd learned. But I still worked for Andromeda. The technique still felt like it could be an advantage.

So I shared enough to be useful, held back enough to feel responsible to my employer.

In hindsight, it didn't matter. Andromeda wasn't going to make it. And within months, reasoning models would make my manual technique obsolete anyway.

But standing in that Cornell Tech classroom, four days after o1 launched, feeling vindicated and frustrated in equal measure - that was a moment.

## The 15 Students

After the presentation, 15 students applied for Andromeda's Winternship program.

They wanted to work in AI. They saw what was coming. Some of them probably understood it better than their professors did.

I hope they found good places to land. The company they were applying to wouldn't last.

---

*Next: Harvard 2 & MIT - back-to-back lectures in February as the AI landscape accelerates.*

---

**Photos from Cornell Tech:**
- [Add photo links/references here]

**Date:** December 9, 2024
**Venue:** Cornell Tech
**Co-presenter:** Leif (Andromeda Protocol)
**Topic:** "Andromeda AI Workshop"
**Context:** o1 released 4 days prior

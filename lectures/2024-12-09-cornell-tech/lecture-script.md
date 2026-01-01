# Cornell Tech AI Workshop - December 9, 2024
## Co-presented with Leif (Andromeda Protocol)

**Note:** This was a joint presentation. Leif covered Andromeda protocol/blockchain specifics. This script covers Myron's AI-focused portion.

---

## Opening: We Were Already Doing "Reasoning" Before They Called It That

Before RAG systems were mature, before "chain of thought" became a buzzword - before OpenAI released o1 and everyone started calling it "reasoning" - we figured something out at Andromeda.

The context windows were getting big. Really big. So I thought: what if I just... stuffed everything in there?

Here's what we did:
- Took ALL of Andromeda's documentation
- Took relevant parts of our entire codebase
- Shoved it all into Google AI Studio's context window
- Then asked the model to create a table of contents for itself - an index of everything it now "knew"
- Asked it key questions to establish the knowledge base, get it oriented
- Made it think through the structure before asking it to do anything

Once that conversation was "primed," we'd fork it. Over and over. Every new task started from that baseline - the model already understood our entire system.

We were forcing the model to reason step-by-step about our codebase before we asked it to produce anything. Organize first, then generate. That's chain-of-thought prompting.

OpenAI just released o1 four days ago - a model that thinks before it responds. They're calling it "reasoning." We've been doing this manually for months. They just baked it into the architecture.

*[2025 retrospective: This technique became the defining development in LLMs. OpenAI's o1/o3, Claude's extended thinking, DeepSeek R1 - all built on this principle. The model reasons before it generates. We were ahead of the curve.]*

The tools were janky. But you could see where this was going.

---

## My Background: Why I Saw This Coming

**Myron Koch, Head of AI and AI UX at Andromeda**

Started in entertainment in the 90s - figured out digital ticketing in my region before anyone else. That parlayed into building corporate websites, learning new languages, frameworks, operating systems.

Around 2008, became part of a red team community testing iPhone apps on the 3G. Continued through several iPhone releases.

**The Kurzweil Moment (November 2012)**

Saw Ray Kurzweil speak on his "How to Create a Mind" book tour. He discussed pattern recognition as a framework for thought - first time I heard about neural networks, AGI.

He said point blank: neural networks could and would produce an intelligence more capable than the human brain.

The Kurzweil backstory:
- President of School for the Blind asked him for help
- Invented the flatbed scanner, OCR, and the first synthesized voice
- Stevie Wonder became friends with him, bet he couldn't make it sound like a real instrument
- Kurzweil won that bet

He also talked about injectable wifi-enabled nanobots that could mimic cell types - need extra neocortex cells? The nanobots mimic neurons. Need extra muscle? They mimic actin-myosin structure.

That blasted me off. From 2012 through 2020, I tracked everything:
- Computer Vision: AlexNet, ResNet, GANs, Vision Transformers
- NLP: Word2Vec, BERT, GPT-2, GPT-3, ChatGPT
- Generative Models: GANs, DALL-E
- Reinforcement Learning: AlphaGo
- Cross-Modal AI: Vision and Language integration
- Scientific Applications: AlphaFold for protein folding

---

## The ChatGPT Moment

Got into ChatGPT's public beta on day 3. Was doing battery systems research at the time - had mountains of technical information to process.

Learned that AI could turn hours of work into minutes. From that point on, I tried to push the envelope.

**Anthropic Claude** - Amazon invested, now powers Rufus, will replace Alexa. Introduced "artifacts" - side-by-side code generation.

---

## The Current AI Engineering Stack (Late 2024)

**Closed source tools we're using at Andromeda:**
- AI Studio (Google) - our proto-RAG knowledge base approach
- Cursor - AI-native code editor
- Warp - AI-enhanced terminal
- v0 - Vercel's UI generator
- CodeRabbit - AI code review
- GitHub Copilot
- ChatGPT, Claude (the standards)

**Open source:**
- LM Studio (chat and local server)
- Ollama (local model server)

**Our internal tool: Androptimus**
- Fine-tuned Google Gemini model
- Used for internal tasks across the team
- Can generate concise documentation from a codebase dump

---

## Introducing AI Tools to an Engineering Team

The tools are janky. Let's be honest about that.

But introducing them to the Andromeda team for the first time - watching developers go from skeptical to productive - that's where you see the real potential.

The friction is real:
- Learning to prompt effectively
- Knowing when to trust the output vs. when to verify
- Integrating AI into existing workflows without disrupting everything

But once it clicks, the productivity gains are undeniable.

---

## Q&A

[Open floor for questions about AI tools, the proto-RAG approach, team adoption, practical applications]

**Resources:**
- Andromeda documentation
- Community channels (Discord, Telegram)
- Winternship program for students interested in Web3 + AI

---

*Note: Leif covered Part 2-3 of the formal curriculum (ADOs, Andromeda Protocol specifics). This script reflects Myron's AI-focused presentation.*

---
tags: [analysis, thesis, durability]
created: 2026-05-29
---

# The Scaling Debate

The durability question: as foundation models scale (longer context, better synthesis, agentic workflows, native memory), does the "decide what to build" decision/context layer become a **more valuable standalone product**, or does it get **absorbed** by the models and coding agents themselves? Builds on [[The What-to-Build Bottleneck]]; pairs with [[Market Size and Popularity]].

## Bull — the layer gets MORE valuable

`[Confirmed]` The strongest primary-sourced argument is Andrew Ng's "Product Management Bottleneck":

> "As AI agents accelerate coding… we are more constrained by deciding what to build rather than the actual building… when building becomes easier, deciding what to build becomes a bigger bottleneck." — Andrew Ng (his X account; also Stanford CS230 Autumn 2025)

`[Inference]` The logic: as agents get more autonomous, they need **structured, evidence-cited intent** to act well — a synthesized "build X, here's why, grounded in customer feedback" artifact, broken into agent-executable tasks. That is precisely [[The Full Discovery Loop]]. The [[Market Size and Popularity|adoption data]] reinforces it: AI today helps PMs *produce* (PRDs, mockups) far more than it helps them *think* (research 4.7%, ideation 1.1%) — the under-served gap this layer fills.

## Bear — native model features ABSORB the layer

`[Confirmed]` The encroachment is already shipping, with dates:
- **Claude Projects** — launched Sept 2024; context expanded 10× June 2025.
- **Claude Memory** — rolled out to all users (incl. free tier) Mar 2, 2026; carries context across sessions.
- **Anthropic Agent Skills** — announced Oct 16, 2025; published as an open standard (agentskills.io) Dec 18, 2025. Filesystem-based, on-demand "workflows, context, and **best practices**" — a native "structured context for agents" primitive.
- ChatGPT ships Memory + Projects + Canvas on the same trajectory.

`[Unverified, opinion]` The "thin wrapper" risk: *"When large platforms decide your product is a feature, not a product, your business model evaporates overnight."* Supporting evidence from the [[Market Size and Popularity|surveys]]: 57.7% of PMs default to general-purpose ChatGPT, and 88% juggle 2+ models — users reach for the raw model, not a dedicated tool. A third vector: **Granola itself is moving "up"** from notetaker into an enterprise context app.

> [!IMPORTANT]
> The piece most exposed to absorption is **persistent "context bank" / skill-and-best-practice extraction** — it maps almost 1:1 onto Claude's Memory Store + Dreams consolidation + Agent Skills. A standalone product should treat that as a *feature*, not a moat. (See the sibling `agent-memory` vault's "User-Integrated Memory Gap" note: the defensible edge there is infrastructure quality — durability, portability across providers, team ownership — not the extraction intelligence, which the model gives away.)

## Honest net

`[Inference]` The *activity* is real and growing (Ng + both surveys). The open question is **capture**: is "decide what to build" a **durable system of record** — defensible via proprietary, structured customer-evidence data, deep integrations, and write-back to coding agents — or a **transient workflow** that native Memory/Skills/Projects swallow? The bull has a credible thesis and a documented under-served gap; the bear has *shipping features with dates*. Defensibility will hinge on owning proprietary evidence data and the end-to-end discovery→spec→agent handoff, plus cross-provider portability — **not** on prompt cleverness.

## See Also

- [[The What-to-Build Bottleneck]] -- the thesis this stress-tests
- [[Market Size and Popularity]] -- the adoption/persona data behind both cases
- [[Market Map and the Open Gap]] -- where defensibility might live
- [[Critiques of the Framing]] -- "recommendations vs. executable contracts"
- [[The Judgment and Taste Critique]] -- the human limit on full automation

## Sources

- [@AndrewYNg — "Product Management Bottleneck" (primary)](https://x.com/AndrewYNg/status/2043742105852621052) `[Confirmed]`
- [Anthropic — Agent Skills announcement (Oct 16, 2025)](https://www.anthropic.com/news/skills) `[Confirmed]`
- [Anthropic — Equipping agents with Agent Skills (mechanics)](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) `[Confirmed]`
- [Lenny's Newsletter — AI productivity survey (default-to-ChatGPT, fragmentation)](https://www.lennysnewsletter.com/p/ai-tools-are-overdelivering-results) `[Confirmed]`
- [TechCrunch — Granola $125M / $1.5B (expansion into enterprise context)](https://techcrunch.com/2026/03/25/granola-raises-125m-hits-1-5b-valuation-) `[Confirmed]`
- [techbuzz.ai — thin-wrapper extinction risk](https://www.techbuzz.ai/articles/google-vp-two-ai-startup-models-face-extinction) `[Unverified, opinion]`

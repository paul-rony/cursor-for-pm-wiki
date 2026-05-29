---
tags: [analysis, market, adoption]
created: 2026-05-29
---

# Market Size and Popularity

How big and how adopted the "Cursor for PMs" category actually is — the "is this niche?" question. Pairs with [[The Scaling Debate]] (the durability question) and [[Market Map and the Open Gap]] (the competitive structure).

> [!WARNING]
> All "market size" figures below come from commercial research aggregators (Mordor, Fortune Business Insights, etc.) whose estimates for the *same* category diverge 2–3×. They are `[Unverified]` and directional. Funding, survey, and labor-statistics figures that trace to a named primary source are `[Confirmed]`.

## Persona size — niche by title, broad by activity

- **Titled PMs:** ~**700K–1M** worldwide (LinkedIn-derived; ~699K self-listed profiles, Aug 2023). `[Unverified]`
- **The US BLS has no "Product Manager" occupation code** — in 2018 the SOC panel declined to create one, noting PMs "could be classified in many existing occupations." `[Confirmed]` The closest adjacent code, Project Management Specialists, is ~1.0M jobs (May 2024) but is a different role.
- **Developers (Cursor's persona):** ~**47.2M** worldwide in 2025 (SlashData). `[Unverified, widely cited]`
- **The core seat-count risk:** "Cursor for PMs" addresses a persona ~**30–45× smaller** than "Cursor for devs." At similar ACVs, a structurally lower ceiling. `[Inference]`

**The counter-argument (broadens the TAM):** the [[YC Request for Startups|RFS]] frames the work as done "by founders, engineers, or dedicated PMs" — an *activity*, not a title. Andrew Ng predicts the historical ~6:1 engineer-to-PM ratio will *invert* as building gets cheap, implying more people doing the "decide what to build" job. So: **niche if scoped to job titles; potentially broad if scoped to the activity.** `[Inference]` See [[The What-to-Build Bottleneck]].

## Market sizing (directional)

`[Unverified]` aggregator estimates, 2025 base:

| Category | ~2025 size | CAGR | Read |
|----------|-----------|------|------|
| Product management software | ~$6–9B (one outlier $14B) | ~10–12% | Loosely defined; high variance |
| Voice-of-customer analytics | ~$3–16B (definition-dependent) | ~15–16% | Fastest-growing; widest spread |
| Product analytics | ~$11B | ~13–15% | Tightest clustering; most confidence |
| "AI for product management" | **no credible standalone TAM** | — | Greenfield *and* unproven |

## Adoption — high usage, but on *producing*, not *thinking*

`[Confirmed]` Two 2025 surveys (both with vendor/selection bias worth noting):

**Lenny Rachitsky / Noam Segal, n=1,750 tech workers (Dec 2025):**
- 83.6% named ≥1 AI tool they'd be "very disappointed" to lose.
- 63% of PMs say AI saves 4+ hrs/week; >70% report quality improvements.
- Top PM use cases: PRDs (21.5%), mockups/prototypes (19.8%), comms (18.5%).
- **Strategic work lags: user research 4.7%, roadmap ideation 1.1%.**
- **57.7% of PMs use ChatGPT as their primary AI tool.**

> "AI is helping PMs *produce*, but it lags in helping them *think*."

**Productboard / UserEvidence, n=379 (Oct 2025; vendor-biased):**
- 100% of teams use AI; 94% daily/often; ~50% call it "deeply embedded."
- Rising critical skill: synthesizing customer insights (54%).
- Fragmentation: 88% use 2+ AI models, 60% use 2+ prototyping tools — **no incumbent has won the workflow.**

`[Inference]` The strategic read: the "decide what to build" layer is simultaneously the **most under-served** (the opportunity) and the place users currently default to the raw model (the threat). See [[The Scaling Debate]].

## Granola — a relevant adjacent data point

`[Confirmed]` granola.ai (AI meeting notes): Series B $43M @ $250M (May 2025) → **Series C $125M @ $1.5B valuation (Mar 2026)**, ~$192M total raised; enterprise users incl. Vanta, Gusto, Asana, Cursor, Lovable, Mistral. No public ARR. Notably, Granola is **expanding from notetaker into an enterprise "AI context" app** — a potential platform-encroacher on the context layer. `[Confirmed]`

## See Also

- [[The Scaling Debate]] -- whether this layer survives as models scale
- [[Market Map and the Open Gap]] -- competitive structure
- [[The What-to-Build Bottleneck]] -- the "activity not title" framing
- [[Evidence and Sourcing Notes]] -- confidence conventions

## Sources

- [BLS — 2018 SOC responses (no PM occupation code)](https://www.bls.gov/soc/2018/soc_responses_July_2016.htm) `[Confirmed]`
- [BLS — Project Management Specialists (~1.0M jobs)](https://www.bls.gov/ooh/business-and-financial/project-management-specialists.htm) `[Confirmed]`
- [How many product managers in the world? (LinkedIn analysis)](https://www.linkedin.com/pulse/how-many-product-managers-world-pau-yanez) — ~1.06M; ~699K profiles `[Unverified]`
- [SlashData — global developer population 2025 (~47.2M)](https://www.slashdata.co/post/global-developer-population-trends-2025-how-many-developers-are-there) `[Unverified]`
- [Mordor — product analytics market (~$11.39B, 14.83% CAGR)](https://www.mordorintelligence.com/industry-reports/product-analytics-market) `[Unverified]`
- [Custom Market Insights — VoC platform market (~$9.5B, ~15% CAGR)](https://www.custommarketinsights.com/report/voice-of-customer-voc-platform-market/) `[Unverified]`
- [Dataintelo — product management software market](https://dataintelo.com/report/global-product-management-software-market) `[Unverified]`
- [Lenny's Newsletter — AI tools are overdelivering (Segal/Rachitsky survey, n=1,750)](https://www.lennysnewsletter.com/p/ai-tools-are-overdelivering-results) `[Confirmed]`
- [Productboard — State of AI in Product Management (n=379)](https://www.productboard.com/blog/ai-in-product-management-report/) `[Confirmed, vendor-biased]`
- [TechCrunch — Granola raises $125M at $1.5B](https://techcrunch.com/2026/03/25/granola-raises-125m-hits-1-5b-valuation-) and [Granola Series B $43M at $250M](https://techcrunch.com/2025/05/14/ai-note-taking-app-granola-raises-43m-at-250m-valuation-) `[Confirmed]`

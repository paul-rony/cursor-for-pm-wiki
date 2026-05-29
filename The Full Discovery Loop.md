---
tags: [concept, capabilities]
created: 2026-05-29
---

# The Full Discovery Loop

The capability set a winning "Cursor for PMs" product must deliver end-to-end. The [[YC Request for Startups|RFS]] names the loop; analysts (Trova, Modelence) elaborate it. No company yet covers all of it — see [[Market Map and the Open Gap]].

## What YC's text names (authoritative)

`[Confirmed]` From the RFS entry itself:

1. **Ingest** uploaded customer interviews and product usage data.
2. Answer **"what should we build next?"** with a feature outline *plus* an evidence-based explanation ("based on customer feedback as to why this is a change worth making").
3. **Propose specific changes** to the product's UI, data model, and workflows.
4. **Break down development tasks** so they can be "handled by your favorite coding agent."
5. Support **the full loop** of product discovery — not isolated steps.

## Analyst elaboration (Trova)

`[Confirmed]` as Trova's stated requirements (commentary, not YC's words):

- **Ingest from where signal already lives** — real connections to Intercom, Zendesk, Slack, GitHub, Jira, Linear, Amplitude, Mixpanel; audio interview transcription. "The PM shouldn't have to move their data."
- **Synthesize, don't just organize** — "tagging and categorizing is not the same as finding what keeps coming up."
- **Rank by evidence** — surface requests "ranked by how much evidence is behind it," preserving the chain so "the spec would cite the signal."
- **Emit agent-parseable output** — "Specs. PRDs. Linear tickets. Decision docs" in a structure coding agents can parse.
- **Live agent access via MCP** — a native MCP server giving Cursor/Claude Code live access to priorities, decisions, and signals while they build.
- **Persistent product memory** — context that "compounds over time."

## Analyst elaboration (Modelence)

`[Confirmed]` as Modelence's interpretation (its own spec, not YC's words):

- **Data ingestion:** support tickets (Intercom/Zendesk/Slack), analytics (PostHog/Amplitude/Mixpanel), interview transcripts, NPS/churn feedback, feature-request boards, session-replay metadata.
- **Synthesis:** cluster recurring pain points, detect unmet needs across segments, surface representative quotes as evidence.
- **Ranking:** score opportunities on frequency, revenue impact, retention impact, strategic alignment, effort, and confidence — with customizable weighting.
- **Spec generation:** PRD, user stories, acceptance criteria, data-model changes, API contracts, UI flows, QA checklist.
- **Post-launch tracking:** compare predicted vs. actual impact, feeding back into prioritization.
- **Governance:** roles, approvals, comment threads, audit logs.

## The decomposition that matters

`[Inference]` The loop cleaves into three sub-problems, and today's companies each own only one or two — which is why [[Market Map and the Open Gap]] argues the full product is still greenfield:

| Stage | What it does | Who owns it today |
|-------|--------------|-------------------|
| **Ingest** | gather/produce signal (incl. AI-run interviews) | [[Listen Labs]], [[Strella]] |
| **Synthesize** | cluster, rank, cite evidence | [[Enterpret]], [[BuildBetter]], [[Kraftful]], [[Dovetail]] |
| **Spec & hand off** | PRD → agent-executable tasks | [[ChatPRD]], [[GTPlanner]] |

## See Also

- [[The What-to-Build Bottleneck]] -- why this loop is the prize
- [[Market Map and the Open Gap]] -- who covers which stages
- [[Critiques of the Framing]] -- argument that the output must be *contracts*, not recommendations

## Sources

- [Wayback snapshot of ycombinator.com/rfs (2026-04-02)](https://web.archive.org/web/20260402165521/https://www.ycombinator.com/rfs) — YC's authoritative capability list.
- [Trova — Cursor for Product Managers](https://www.withtrova.com/blog/cursor-for-product-managers) — integration list, MCP, persistent memory.
- [Modelence — Cursor for Product Managers](https://modelence.com/yc-rfs-spring-2026/cursor-for-product-managers) — detailed scoring/spec interpretation.

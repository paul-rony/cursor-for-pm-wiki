---
tags: [concept, critique]
created: 2026-05-29
---

# Critiques of the Framing

Substantive pushback on *how* the [[YC Request for Startups|"Cursor for PMs" RFS]] is framed — distinct from skepticism about whether the tools work (that lives in [[Where AI PM Tools Fall Short]]).

## "The name will kill the solution" — Janne Lammi

`[Confirmed]` Janne Lammi, "YC Is Right About the Problem. The Name Will Kill the Solution." (2026-02-25). Lammi *agrees* with the diagnosis but attacks two things:

**1. Wrong persona framing.** Naming it "for Product Managers" scopes it as a role tool (a "Productboard 2.0") when the problem is systemic:

> "The gap between user friction and working software isn't owned by PMs. It's owned by everyone — or more often, by nobody."

His point: intent lives in people's heads, not in a system; pinning it to the PM persona mis-scopes the product and hurts adoption. The right analogy is Cursor as an *infrastructure layer* for everyone who decides what gets built, not a specialized instrument.

**2. Recommendations vs. contracts.** The tool must emit *executable specifications*, not suggestions:

> "Recommendations are where product decisions go to die."

Agents need "explicit objectives. Hard constraints. Edge cases. Verification criteria" — not vague guidance like "improve checkout UX." This reinforces the agent-executable-output requirement in [[The Full Discovery Loop]].

## Competing interpretation — Builder.io

`[Confirmed]` Builder.io reads "Cursor for PMs" differently: not a discovery/synthesis engine, but **PMs directly using Cursor-style agentic tools** to prototype and ship (codebase access, MCP to Jira/Notion/Linear/PostHog, no-SQL data analysis, rapid prototyping). It cites Naval Ravikant's "vibe coding is the new product management." It frames friction (MCP reliability, learning curve, tool isolation) as adoption hurdles, not conceptual flaws.

`[Inference]` This is a genuinely different product than YC's text describes — YC asks for a *decision/synthesis* layer that *feeds* coding agents; Builder.io describes PMs *becoming* the coding-agent operator. Worth holding both readings in mind.

## Most coverage is descriptive, not critical

`[Inference]` Trade coverage (Inc, Modelence, Trova, Superframeworks, StartupRadar) is largely enthusiastic/descriptive. Lammi's piece is the substantive critique of the framing itself.

## See Also

- [[The Full Discovery Loop]] -- the "contracts not recommendations" point applied
- [[Where AI PM Tools Fall Short]] -- empirical (not framing) skepticism
- [[Market Map and the Open Gap]] -- the standalone-product-vs-feature question

## Sources

- [Janne Lammi — "YC Is Right About the Problem. The Name Will Kill the Solution."](https://pathmode.io/blog/yc-got-it-wrong) — the primary framing critique (persona error; recommendations-vs-contracts).
- [Builder.io — Cursor for Product Managers](https://www.builder.io/blog/cursor-for-product-managers) — competing "PMs do agentic building" interpretation; Naval "vibe coding" reference.

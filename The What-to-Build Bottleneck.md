---
tags: [concept, thesis]
created: 2026-05-29
---

# The What-to-Build Bottleneck

The core thesis behind [[YC Request for Startups|YC's "Cursor for PMs" RFS]]: AI coding agents made *implementation* fast and cheap, so the binding constraint on shipping good software shifted upstream — to deciding **what** is worth building.

## The argument

- **Code got solved (enough).** Cursor and Claude Code make writing code fast; the RFS states "writing code is only part of building a product people want." `[Confirmed]`
- **The bottleneck moved.** The constraint is no longer how fast you can write code, but how clearly you can tell an agent *what* to build. `[Confirmed]` (RFS + Trova/Inc framing)
- **Signal is accumulating, untapped.** Companies sit on years of tickets, interviews, and analytics that AI can now synthesize at scale, "but there's no system that supports the full loop of product discovery." `[Confirmed]`
- **The output artifact must change.** Discovery historically produced "product requirements docs, Figma mocks, and Jira tickets — artifacts designed to communicate intent to human engineers." When agents take the first pass at implementation, the artifact needs to be machine-consumable. `[Confirmed]`

## The independent echo

`[Synthesis]` Practitioners and analysts independently reach the same conclusion, often citing Andrew Ng's framing that "product management is becoming the new bottleneck": AI sped up artifact production but not judgment, widening the gap between fast outputs and slow decisions. See [[The Judgment and Taste Critique]] and [[Where AI PM Tools Fall Short]].

## Why it matters for builders

If the thesis holds, the durable product is the one that owns the *decision layer* — turning raw signal into evidence-backed, agent-executable intent. That is the capability set in [[The Full Discovery Loop]]. The open question is whether that decision layer is a standalone product or a feature of existing tools — see [[Market Map and the Open Gap]].

## See Also

- [[YC Request for Startups]] -- the source of the thesis
- [[The Full Discovery Loop]] -- what the thesis implies a product must do
- [[The Judgment and Taste Critique]] -- the counter-pressure: judgment can't be automated

## Sources

- [Wayback snapshot of ycombinator.com/rfs (2026-04-02)](https://web.archive.org/web/20260402165521/https://www.ycombinator.com/rfs) — RFS thesis language.
- [Trova — Cursor for Product Managers](https://www.withtrova.com/blog/cursor-for-product-managers) — "bottleneck shifted" framing.
- [Userpilot — Is AI Product Management a Lie? (Abrar Abutouq)](https://userpilot.com/blog/what-is-product-management/) — "decision velocity is the real bottleneck" practitioner echo (vendor-published; mild conflict).

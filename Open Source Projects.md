---
tags: [index, open-source]
created: 2026-05-29
---

# Open Source Projects

Index of open-source projects in the "Cursor for PMs" space. GitHub metadata (stars/license) was read first-party via the GitHub API on 2026-05-28. `[Confirmed]` for all stars/licenses below.

> [!NOTE]
> **The OSS landscape splits, and no mature project does the full loop.** It divides into (a) feedback-*collection* tools and (b) PRD-*generation* tools/templates. The complete "ingest real feedback → synthesize → recommend → spec" pipeline appears only in tiny personal repos. See [[Market Map and the Open Gap]].

## Agent-native feedback platforms

* [[Quackback]] -- AGPL alternative to Canny/UserVoice/Productboard, **with an MCP server** so agents can triage feedback. 107★. Best OSS fit.
* **Fider** ([github.com/getfider/fider](https://github.com/getfider/fider)) -- mature feedback collection/voting, **no AI**. AGPL-3.0, Go, **4,331★** (most-starred here). Pure input layer.
* **astuto** ([github.com/astuto/astuto](https://github.com/astuto/astuto)) -- self-hosted feedback/voting, Jira/Trello/Slack integrations, **no AI synthesis**. AGPL-3.0, **2,354★**. Maintainer deliberately avoids sponsorship/funding.

## PRD-generation tools & templates

* [[GTPlanner]] -- MIT "Agent PRD" generator optimized for Claude Code/Cursor (Web UI + skill + MCP). 287★. Spec half of the loop only.
* **ai-native-pm-os** ([github.com/vishalmdi/ai-native-pm-os](https://github.com/vishalmdi/ai-native-pm-os)) -- a "PM OS" guide/framework for using Claude as a PM (11 modules). No license, **83★**. Educational, not deployable.

## Smaller / early (lower signal)

`[Confirmed]` via GitHub API; all individual/indie, mostly very early:
- **shinpr/claude-code-discover** — discovery workflows for Claude Code (hypotheses → validated PRDs). MIT, 4★.
- **varunk130/multi-ai-agent-pm-team** — 6-agent pipeline: feedback → strategy/PRDs/comms. MIT, 1★. Closest single-repo match to the *full* vision, but essentially a personal demo.
- **botingw/pm-workflow-copilot-ide** — AI PM assistant for Cline/Cursor. No license, 21★.
- **AungMyoKyaw/prd-creator** — LLM PRD generator (Gemini). No license, 21★.
- **SeeknnDestroy/agentic-prd-generation** — agentic PRD workflow. MIT, 14★.

## Honest gap

`[Inference]` No widely-starred OSS project does the full "ingest real customer feedback → synthesize → recommend what to build → spec it" loop. No LangChain/LlamaIndex voice-of-customer template with meaningful traction surfaced despite targeted searching. The OSS frontier is feedback-collection + PRD-generation, not the connective synthesis layer.

## See Also

- [[Quackback]] -- the standout
- [[GTPlanner]] -- the spec generator
- [[Market Map and the Open Gap]]
- [[Indie and Bootstrapped Tools]]

## Sources

- [Quackback](https://github.com/QuackbackIO/quackback) · [Fider](https://github.com/getfider/fider) · [astuto](https://github.com/astuto/astuto) · [GTPlanner](https://github.com/OpenSQZ/GTPlanner) · [ai-native-pm-os](https://github.com/vishalmdi/ai-native-pm-os) — first-party GitHub API reads (2026-05-28).

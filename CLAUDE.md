# Research Vault: Cursor for Product Managers

This is an Obsidian-style wiki of interlinked markdown notes on the **"Cursor for Product Managers"** space — YC's #1 Spring 2026 Request for Startups (an AI-native system for deciding *what* to build, not just *how*). It covers the YC ask itself, the company landscape (VC-backed, bootstrapped, open source), and real-world user sentiment.

## Where to Start

- **[[Cursor for Product Managers MOC]]** is the map of content. Start here for any question.
- Notes use `[[wiki-links]]` — follow them to navigate. Section links look like `[[Note Name#Heading]]`; aliased links look like `[[Note Name|display text]]`.

## Structure

- **Concept notes** (e.g., `The What-to-Build Bottleneck.md`, `The Full Discovery Loop.md`) explain one idea each.
- **Entity notes** (e.g., `Enterpret.md`, `ChatPRD.md`, `Quackback.md`) cover one company, tool, or project each.
- **Index notes** (e.g., `VC-Backed Companies.md`, `Open Source Projects.md`) are slim hubs that tier and link to atomic notes, with compact inline entries for the long tail.
- **Sentiment notes** (e.g., `User Testimonials.md`) carry attributed quotes and themes.

## Conventions (important)

Every factual claim is tagged for confidence so future readers (and agents) can trust it appropriately:

- **`[Confirmed]`** — stated in a named, datable primary or reputable secondary source (press release, Crunchbase/Tracxn/PitchBook, TechCrunch, the YC page itself, a first-party GitHub API read).
- **`[Unverified]`** — appeared in an aggregator or single source with conflicting/unclear data. Do not present as fact.
- **`[Inference]`** — the author's reasoning, not a sourced claim.

Other conventions:
- Quotes are **real and attributed**. If a sentiment is synthesis rather than a verbatim quote, it is marked `[Synthesis]`. Never convert a paraphrase into a fake quote.
- Funding figures, investors, and valuations are never invented. If unverifiable, the note says so.
- Each note ends with a **`## Sources`** section of markdown links so it is self-contained and checkable.
- Dates are absolute (e.g., `2026-05-29`), never relative.

## Adding a New Note

1. Create `Your Note Title.md` (Title Case, spaces allowed — Obsidian style).
2. Add frontmatter:
   ```
   ---
   tags: [company, vc-backed]   # or: concept, indie, open-source, sentiment, index, overview
   created: 2026-05-29
   ---
   ```
3. Open with an `# H1` title and a one-sentence definition that links out via `[[wiki-links]]`.
4. Use the `[Confirmed]` / `[Unverified]` / `[Inference]` tags on claims.
5. End with `## See Also` (wiki-links) and `## Sources` (markdown links).
6. **Register it in [[Cursor for Product Managers MOC]]** under the right section, with a `* [[Note]] -- one-line description` entry.

## If You're Looking For...

| Question | Start at |
|----------|----------|
| What exactly did YC ask for? | `YC Request for Startups.md` |
| What would a winning product need to do? | `The Full Discovery Loop.md` |
| Who is VC-funded in this space? | `VC-Backed Companies.md` |
| Who is bootstrapped / indie? | `Indie and Bootstrapped Tools.md` |
| What open-source options exist? | `Open Source Projects.md` |
| Do PMs actually find these tools useful? | `User Testimonials.md` |
| Why are PMs skeptical? | `Where AI PM Tools Fall Short.md` |
| Where is the market gap / who's closest? | `Market Map and the Open Gap.md` |
| How confident is a given claim? | `Evidence and Sourcing Notes.md` |

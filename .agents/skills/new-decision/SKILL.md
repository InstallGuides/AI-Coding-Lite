---
name: new-decision
description: Record a short decision (an ADR, architecture decision record) in 2-decisions/, numbered in sequence. Use when the user makes or asks to record a meaningful choice, such as a library, an approach or a trade-off.
---

# Record a decision

When a real choice is being made:

1. Find the highest `ADR-NNN-*.md` in `2-decisions/` and use the next number.
2. Create `2-decisions/ADR-<NNN>-<short-kebab-title>.md`. Start it with the title and a `**Status:**` line: `accepted`, or `proposed` if it isn't agreed yet. Then write the **Decision**, **Why**, **Alternatives considered**, and **Consequences**.
3. Link any research it rests on (`1-research/…`).

Keep it short: a decision record is a paragraph, not an essay. Its value is capturing *why*, so the choice isn't argued over again later.

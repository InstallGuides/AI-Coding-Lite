---
name: preserve-our-work
description: Save the session's progress so the next conversation can continue. Updates CHANGELOG.md and writes a work-ledger handoff note. Use when finishing a chunk of work, wrapping up, or when the user says "preserve our work" or "checkpoint this".
---

# Preserve our work

**Why this exists:** you don't remember past conversations, and your working memory fills up within a long one. The next conversation knows only what's written in this folder. So before you stop, save what you did and what's next. That written trail is the project's memory.

Steps:

1. **Check today's date** with `date` first. A conversation can run past midnight, so don't reuse a date from earlier in it.
2. **CHANGELOG.md:** add a dated bullet, newest first: one to three sentences on what changed and in which files, naming the spec. The reasoning goes in the handoff note, not here.
3. **Handoff note:** in `0-project-management/work-ledger/`, add `YYYY-MM-DD-<short-slug>.md`. Start it with a title and a one-sentence `**Summary:**`, then write **what** you did, **why** (decisions made and paths rejected, the reasoning that isn't obvious from the files), and **what's next**. Then add a one-line link to it at the top of `0-project-management/work-ledger/index.md`.
4. If the project uses Git, offer to commit the changes. Stage files by name (`git add <file>`), never `git add -A`. **Never commit secrets** (`.env` is git-ignored).

Write a handoff note for a *meaningful chunk* of work, not every tiny edit. Its job is handoff: a future conversation, or a different assistant, should be able to read it and continue cold.

---
name: new-spec
description: Start a new feature spec from the template, numbered in sequence, in 3-specifications/. Use when the user wants to start a new spec, plan a feature, or "spec out" an idea before coding.
---

# Start a new spec

When the user wants to plan a new feature:

1. Look in `3-specifications/` for the highest existing `SPEC-NNN-*.md` number and use the next one.
2. Copy `3-specifications/SPEC-template.md` to `3-specifications/SPEC-<NNN>-<short-kebab-title>.md`.
3. Fill in what you can from the user's request: Goal, Why, Behavior, Done when, Out of scope. Leave anything unclear as an explicit question.
4. Keep the Status line at `draft`. Under it, add a "Builds on:" line naming any decision the spec relies on.
5. Show the draft and get the user's OK **before** writing any code.

Spec first, code second.

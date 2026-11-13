# SPEC-001: Hello, world

**Status:** done

Builds on: `2-decisions/ADR-001-example-decision.md`

## Goal

A tiny program that prints a friendly greeting, so the project has one working, spec-backed feature to learn from.

## Why

To show the decide → spec → playbook → build → track loop end to end with the smallest possible feature.

## Behavior

- When run, print: `Hello from your AI-Coding-Lite!`
- Keep the greeting in a small function so it's easy to test or reuse later.

## Done when (acceptance)

- [x] Running the program prints the greeting.
- [x] `CHANGELOG.md` records the change.

## Out of scope

- Greeting the user by name. That's a good SPEC-002 to try next.
- Any input, files, or network access.

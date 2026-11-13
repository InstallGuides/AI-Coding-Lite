# PB-001: Implement SPEC-001 (hello)

**Status:** done

A playbook is step-by-step instructions your assistant follows. This one is a one-time handoff: it turns a spec into a plan and a task list, so a fresh conversation can build the feature without the one that wrote the spec. (A playbook can also be a procedure you repeat. See `PB-002`.)

## Read first

- `3-specifications/SPEC-001-hello.md`: what to build, and how you'll know it's done.
- `2-decisions/ADR-001-example-decision.md`: already decided, the example is in Python.

## Plan

One small file, `source/hello.py`. The greeting lives in its own function so it's easy to test or reuse, and a `main()` prints it when you run the file.

## Tasks

Do one task at a time, check it, and tick its box before starting the next.

- [x] 1. Create `source/hello.py` with a `greeting()` function that returns `Hello from your AI-Coding-Lite!`.
- [x] 2. Add a `main()` that prints the greeting when the file is run.
- [x] 3. Run `uv run source/hello.py` and check that the output matches the spec.
- [x] 4. Tick the spec's "Done when" boxes and set its Status to `done`.
- [x] 5. Update `CHANGELOG.md` and write a handoff note in `0-project-management/work-ledger/`.

## Done when

Every task above is ticked, and so is every box in the spec's "Done when" list.

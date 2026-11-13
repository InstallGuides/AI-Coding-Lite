# ADR-001: Use Python for the example feature

**Status:** accepted

An ADR (architecture decision record) is a short note of a choice and why, so it isn't argued over again later. Keep them short.

## Decision

Write the hello-world example (SPEC-001) in Python.

## Why

Python reads almost like plain English, which makes it a friendly first example, and uv runs a Python file with one command. (Evidence: `1-research/2026-06-20-example-note.md`.)

## Alternatives considered

- Node, Ruby, Java or Rust. The `rewrite-in-language` skill ports the example to any of them.

## Consequences

The example ships in Python. Moving to another language is a one-skill step.

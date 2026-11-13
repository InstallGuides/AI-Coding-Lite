# Start here: AI-Coding-Lite

This folder teaches a calmer, more reliable way to build software with an AI assistant: **spec-driven development**. You decide what to build and why, write it down, and then build it, so the plan outlives any one conversation.

*Step 2 of 3: plan before you build, with a small worked example. Next: [AI-Coding-Complete](https://github.com/InstallGuides/AI-Coding-Complete).*

## Open this folder with your AI assistant

- **Claude Desktop:** click **Code**, choose **Open folder…**, and pick this folder.
- **ChatGPT app (Codex):** click **Add new project**, choose this folder, and start a Codex chat.
- **Claude Code or Codex in a terminal:** open a terminal in this folder ([how](https://mac.install.guide/terminal/open)), then type `claude` or `codex`.

## Try it

1. *"Start a new spec for a program that greets me by name."* Your assistant writes `3-specifications/SPEC-002-….md`.
2. Read it, and change anything until it says what you want.
3. *"Write a playbook for SPEC-002."* You get a plan and a task list in `4-playbooks/`, with no code yet.
4. Start a fresh conversation: *"Build from PB-003, one task at a time."*
5. *"Preserve our work."* Your assistant updates the changelog and writes a handoff note.

## Why write things down

An AI assistant remembers nothing from one conversation to the next, and on a long task its working memory fills up. It knows only what it can read in this folder. A spec, a decision record and a handoff note are memory saved outside the assistant, so the next conversation, or a different assistant, can pick up where the last one stopped.

## The loop

Each habit has a skill your assistant uses when you ask:

1. **Plan** (`plan`): what you're building and why, in `0-project-management/overview.md`.
2. **Decide** (`new-decision`): a short decision record in `2-decisions/`.
3. **Write a spec** (`new-spec`): what to build and how you'll know it's done, in `3-specifications/`.
4. **Write a playbook** (`new-playbook`): a plan and task list in `4-playbooks/`, or steps you'll repeat.
5. **Build from the playbook** (`run-playbook`): one task at a time, with the code in `source/`.
6. **Preserve our work** (`preserve-our-work`): a changelog entry and a handoff note in `0-project-management/work-ledger/`.

## Follow the worked example

This folder already holds one trip around the loop. Read the files in this order: `1-research/2026-06-20-example-note.md`, `2-decisions/ADR-001-example-decision.md`, `3-specifications/SPEC-001-hello.md`, `4-playbooks/PB-001-implement-hello.md`, `source/hello.py`, `CHANGELOG.md`, and the note in `0-project-management/work-ledger/`. `PB-002` is a playbook you repeat: it runs the program.

## Run the example

In a terminal in this folder, type `uv run source/hello.py`. If the terminal says `command not found: uv`, [install uv](https://mac.install.guide/python/install-uv) first. Prefer another language? Ask *"rewrite the hello example in Rust"*. The `rewrite-in-language` skill ports it to Node, Ruby, Java or Rust.

## The instruction files

`AGENTS.md` holds the instructions your assistant reads. `CLAUDE.md` is one line that points Claude to the same file, so edit `AGENTS.md` and leave `CLAUDE.md` alone.

## Keep going

- Grow this folder into a project of your own, one spec at a time.
- Anything secret, such as an API key, goes in a file named `.env` in your home folder, never in this folder or in chat.

## Learn more

[Spec-Driven Development](https://mac.install.guide/ai/spec-driven-development/) and [Numbered Project Folders](https://mac.install.guide/project-files/numbered-folders) on Mac Install Guide.

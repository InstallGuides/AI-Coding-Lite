---
name: rewrite-in-language
description: Rewrite the hello example (source/hello.py) in another language, such as Node, Ruby, Java or Rust. Use when the user wants the example, or the project, in a different language. Works even if that language isn't installed yet.
---

# Rewrite the example in another language

The example ships in Python (`source/hello.py`). To port it to another language:

1. Ask which language: **Node**, **Ruby**, **Java**, or **Rust**.
2. Check whether it's installed by running its version command (`node --version`, `ruby --version`, `java --version`, `cargo --version`). If it isn't, say so, offer to install it, and ask before you do. Link the language's page on Mac Install Guide (`https://mac.install.guide/`) so the user can read how.
3. Write the equivalent program under `source/` (for example `source/hello.js`, `source/hello.rb`, `source/Hello.java`, or a small Cargo project), keeping the **same behavior** as `3-specifications/SPEC-001-hello.md`.
4. Note the port in SPEC-001, then preserve our work (`preserve-our-work`): a CHANGELOG entry and, if it was a real chunk of work, a handoff note. Tell the user how to run it.

This is a translation, not a redesign: keep the new version behavior-identical to the Python one.

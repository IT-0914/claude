# AGENTS.md

This file gives guidance to OpenAI Codex (and other coding agents) working in this repository.
Claude Code reads `CLAUDE.md`; keep the two files consistent when either changes.

## Current State

This repository is currently empty — it has no source code, build configuration, or documentation yet.
There are no build, lint, or test commands, and no architecture to describe.

## Working Rules

- Work on your own branch (for example `codex/<topic>`). Do not push directly to the default branch.
- Do not assume a language, framework, or toolchain until project files (a package manifest or build configuration) establish one.
- When code is added, update both `AGENTS.md` and `CLAUDE.md` with:
  - The commands to build, lint, and test (including how to run a single test).
  - A high-level description of the architecture.
- Write commit messages that state what changed and why, in one short subject line plus an optional body.
- Do not commit secrets (API keys, tokens, credentials).

## Collaboration with Claude Code

- Claude Code works on branches named `claude/<topic>`; Codex works on `codex/<topic>`.
- Do not edit or force-push another agent's branch. Hand off through pull requests.

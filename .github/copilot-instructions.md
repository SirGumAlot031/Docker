# Copilot instructions for this repository

## Repository status

This repository is currently minimal and README-driven. The root contains only:

- `README.md`
- `.gitignore`
- a `.github/` directory for project guidance

There is no application source tree, package manifest, or CI configuration yet. Treat this as an early scaffold rather than a mature project with established tooling.

## Build, test, and lint commands

There are no project-defined build, test, lint, or formatting commands configured in this repository at the moment.

The repo does not currently include common tooling files such as:

- `package.json`
- `pyproject.toml`
- `requirements.txt`
- `Makefile`
- `tox.ini`
- `pytest.ini`
- `.github/workflows/`

Because there is no active project ecosystem yet, there is no single command to run for a full suite or a single test. When the repo grows into a real app, add the appropriate commands for that ecosystem and document them here.

## High-level architecture

The current architecture is effectively a blank repository shell:

- `README.md` is the only project-facing documentation.
- `.gitignore` is a generic Python-oriented ignore file, not evidence of an active Python application.
- There is no runtime code, no library layout, and no dependency graph to reason about yet.

In practice, the architecture should be treated as "empty repo awaiting a real project structure." Do not assume Docker, Python, Node, or another stack is in use unless a new manifest or source tree is introduced.

## Key conventions

- Keep the repository root intentionally lean until a concrete project structure is added.
- Prefer project-specific conventions once a stack is chosen; do not invent frameworks or module layouts that are not supported by the repo.
- Update this file whenever the project gains real build/test tooling or a source tree so it matches the current implementation.
- Follow the README as the source of truth for repository intent, and avoid adding unrelated scaffolding or generated files.
- If future code introduces a language or framework, use the standard repository layout and command patterns for that ecosystem rather than mixing conventions.

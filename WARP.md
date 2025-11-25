# WARP.md

This file provides guidance to WARP (warp.dev) when working with code in this repository.

## Repository status

This repository currently contains only a minimal `README.md` with the title `docker-test`. There are no source files, configuration files (such as `package.json`, Dockerfiles, or test configs), or tooling definitions checked in yet.

As a result, most development, build, and test commands are not yet defined in the repo and will need to be added as the project is implemented.

## Development commands

At present, there are **no project-specific CLI commands or scripts defined in this repository** (for example, there is no `package.json`, `Makefile`, or other task runner configuration).

When such tooling is added (e.g., a frontend framework, build tool, or test runner), update this section with:

- How to install dependencies
- How to run the development server (if applicable)
- How to build for production
- How to run the full test suite
- How to run a single test (or a subset of tests), if supported by the chosen tooling

## Architecture and structure

Because the repository currently has no source code directories (such as `src/`, `app/`, or similar) or configuration beyond `README.md`, there is **no meaningful application architecture** to document yet.

Once code is added, consider documenting here:

- The main entrypoints for the application (e.g., root components, routing setup, or bootstrapping code)
- How state management is organized (if applicable)
- How API calls or data fetching are structured
- Any notable patterns or constraints that future changes should respect

## Existing documentation and rules

- `README.md` — currently only declares the project name (`docker-test`) and does not define any usage, setup, or command information.
- There are no `CLAUDE.md`, Cursor rules (`.cursor/` or `.cursorrules`), or Copilot instruction files in this repository at this time.

Future maintainers should expand both `README.md` and this `WARP.md` as the project grows, keeping the focus here on:

- Concrete development commands
- High-level architecture and cross-cutting patterns
- Any project-specific agent instructions that are not obvious from individual files.

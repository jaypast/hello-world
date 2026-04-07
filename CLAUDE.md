# CLAUDE.md

This file provides guidance for AI assistants (like Claude) working with this repository.

## Project Overview

`hello-world` is a minimal GitHub learning repository created by [@jaypast](https://github.com/jaypast). It has no source code — its purpose is to practice basic Git and GitHub workflows (branching, committing, pull requests, merging).

## Repository Structure

```
hello-world/
└── README.md   # Brief project description
```

There are no build systems, package managers, test suites, linters, or application code.

## Branches

| Branch | Purpose |
|--------|---------|
| `master` | Default/main branch |
| `claude/<description>` | AI-assisted feature/documentation branches |

## Development Workflow

1. Create a feature branch off `master` using a descriptive name.
2. Make changes and commit with a clear message.
3. Push the branch and open a pull request against `master`.
4. Merge after review.

## Commit Style

Based on existing history, commits use short, plain-English imperative messages:

```
Update README.md: brief description of change
Add CLAUDE.md with project documentation
```

## Key Conventions for AI Assistants

- **No code to build or test** — skip any steps involving compilation, test runners, or linters.
- **Keep changes minimal** — this is a learning/demo repo; avoid over-engineering.
- **Default branch is `master`** — not `main`.
- **Push AI work to `claude/<description>` branches** and open a PR rather than pushing directly to `master`.
- **Do not add unnecessary files** — only create files that are explicitly requested.

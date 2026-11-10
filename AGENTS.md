# AGENTS.md

## Current state

- Official website of Thanal MEC. The repo currently contains only `README.md` and `LICENSE` — no app code, manifest, lockfile, build/test/lint config, or CI.
- No language, framework, or package manager is established. Do not guess or run commands like `npm test`; inspect the tree first and scaffold only when the task calls for it.
- No `.gitignore` exists. Add one with any scaffolding so dependencies and build output are not committed.
- Verification is manual until tooling exists; record the real setup/dev/test/lint commands here once scaffolding lands.

## Conventions

- Default branch is `main`; remote is `github.com/thanal-mec/website`.
- Licensed under MIT (see `LICENSE`).

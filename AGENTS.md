# Meabh's page: rules for coding agents

Binding for every coding tool in this repo. `CLAUDE.md` only imports this
file. This project follows Andy's build standards, `~/.claude/BUILD-STANDARDS.md` on the Mac mini where all sessions run. This file holds the project's own rules and wins where it is more specific.
Not applicable here, by design: databases, secrets and credentials (standards
D1 to D5), tests and CI (Part B), since there is no backend and no build.

## What this is

A single hand-written HTML page (`index.html`) with inline CSS. No build, no
scripts beyond the page itself, no backend.

## Never do these

- **Never force-push, rewrite pushed history, or delete a branch (other than
  a PR branch you just merged) without Andy's go-ahead.** Otherwise the agent
  handles git: a branch per non-trivial change, one Conventional Commit per
  logical change, push, a PR via `gh`, and merging that PR once its checks
  pass.
- Keep it a single self-contained `index.html` that opens straight from disk.

## Verification

Open `index.html` in a browser.

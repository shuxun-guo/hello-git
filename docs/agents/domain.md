# Domain Docs

This repository uses a single-context layout:

- `CONTEXT.md` at the repository root: domain vocabulary and context.
- `docs/adr/`: architecture decision records.

## Before exploring

Read `CONTEXT.md` and ADRs relevant to the area being explored.

If these files do not exist, proceed silently. Do not suggest creating
them upfront. Domain-modeling work creates them lazily as terms and
decisions are resolved.

## Use the glossary's vocabulary

Use the terms defined in `CONTEXT.md` when naming domain concepts.
Avoid synonyms the glossary explicitly excludes.

If a concept is missing, reconsider the terminology or note the gap
for future domain-modeling work.

## Flag ADR conflicts

Explicitly identify any existing ADR that a proposal contradicts,
and explain why revisiting that decision may be appropriate.

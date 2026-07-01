# ADR 0001: AEOS Core Philosophy and Structure

## Status

Accepted

## Context

AEOS is meant to be an operating system for AI-assisted engineering. To avoid scatter and ambiguity, the repository needs a clear foundational philosophy, domain structure, and naming convention.

## Decision

AEOS adopts a core philosophy built on ten principles:

1. AI augments engineers.
2. Design before code.
3. Documentation is part of the product.
4. Every decision has a reason.
5. One source of truth.
6. Standards over preferences.
7. Small, reviewable changes.
8. Tests are first-class artifacts.
9. Everything should be reusable.
10. Human-first.

The repository will also use predictable naming conventions:

- `agents/*.agent.md`
- `skills/*.skill.md`
- `standards/*.standard.md`
- `workflows/*.workflow.md`

The execution model for agents is:

`README -> INDEX -> MANIFEST -> PROJECT CONTEXT -> ARCHITECTURE -> STANDARDS -> SKILLS -> WORKFLOW -> IMPLEMENT`

## Consequences

- New content will be organized by domain with a clear discovery path.
- AI agents and humans will have a shared order for context gathering.
- Future documents will be easier to maintain and reuse.

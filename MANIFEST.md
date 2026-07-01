# AEOS Manifest

AEOS is a portable engineering operating system for AI-assisted software delivery.

## Purpose

- Capture a shared operating model.
- Define reusable standards and workflows.
- Make agents and documentation discoverable.
- Enable engineering decisions to be consistent, traceable, and reusable.

## Delivery goal

The first AEOS release should provide:

- A documented core philosophy.
- A predictable repository structure.
- A naming convention for agents, skills, standards, and workflows.
- A simple AI execution model.
- A starting set of reusable artifacts.

## First release identity

- Version: `0.1.0`
- Codename: `Genesis`

## First 100 documents plan

AEOS is intentionally small at first. The immediate goal is to grow toward a curated set of 200–300 high-quality documents organized by domain, not to increase raw count.

Approximate target distribution:

- Vision: 5
- Principles: 10
- Standards: 40
- Agents: 20
- Skills: 40
- Workflows: 20
- Templates: 20
- Checklists: 20
- Architecture: 30
- Examples: 30

## Naming conventions

- `agents/*.agent.md`
- `skills/*.skill.md`
- `standards/*.standard.md`
- `workflows/*.workflow.md`

## Execution model

Agents should read project context in a fixed order before implementation:

`README -> INDEX -> MANIFEST -> PROJECT CONTEXT -> ARCHITECTURE -> STANDARDS -> SKILLS -> WORKFLOW -> IMPLEMENT`

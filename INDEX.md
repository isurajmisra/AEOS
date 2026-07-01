# AEOS Index

This index is the second place an AI agent or human should check after the root README.

## Core entry points

- `README.md`: Project vision, philosophy, and high-level orientation.
- `INDEX.md`: What the repository contains and how it is organized.
- `MANIFEST.md`: What AEOS intends to deliver.
- `VERSION`: The current release version.

## Primary domains

- `docs/vision/`: mission, vision, and operating model.
- `docs/principles/`: AEOS principles and working philosophy.
- `docs/standards/`: shared standards for code, review, documentation, and architecture.
- `docs/architecture/`: architecture guidance and system models.
- `agents/`: agent roles and operating contracts.
- `skills/`: reusable knowledge models for technologies and domains.
- `workflows/`: repeatable workflows and delivery patterns.
- `templates/`: ADR, issue, PR, and documentation templates.
- `checklists/`: review and release checklists.
- `examples/`: reference examples and usage patterns.

## First release assets

- `MANIFEST.md`
- `docs/decisions/0001-core-philosophy-structure.md`
- `docs/architecture/aeos-operating-model.architecture.md`
- `standards/Documentation.standard.md`
- `workflows/NewFeature.workflow.md`
- `skills/ESP-IDF.skill.md`
- `agents/ChiefAIEngineer.agent.md`

## AEOS loading order

An AI agent should gather context in this order:

1. `README.md`
2. `INDEX.md`
3. `MANIFEST.md`
4. Project-specific context files
5. `docs/architecture/`
6. Relevant standards
7. Relevant skills
8. Relevant workflows
9. Implementation

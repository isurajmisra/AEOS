# AEOS

AEOS (AI Engineering Operating System) is an AI-native engineering framework for building software with consistent standards, reusable knowledge, and agent-friendly workflows.

## Core philosophy

AEOS is built around ten reusable principles:

1. AI augments engineers, it does not replace them.
2. Design before code; architecture comes first.
3. Documentation is part of the product, not an afterthought.
4. Every important decision has a reason and should be captured in an ADR.
5. One source of truth prevents duplicated knowledge.
6. Standards over preferences keeps the system consistent.
7. Small, reviewable changes make collaboration easier.
8. Tests are first-class artifacts and are never optional.
9. Everything should be reusable, including agents, prompts, templates, standards, and skills.
10. Human-first workflows keep AI as a helper while humans remain the decision makers.

## Document domains

AEOS organizes knowledge by domain instead of scattering documents randomly. The initial taxonomy is:

- Vision
- Principles
- Standards
- Agents
- Skills
- Workflows
- Templates
- Checklists
- Architecture
- Examples

The goal is to grow from a small curated set into a durable library of 200-300 high-quality documents rather than a large collection of shallow ones.

## Agent hierarchy

AEOS uses a layered agent model:

- Product: Product Manager, Technical Writer
- Architecture: Solution Architect, Embedded Architect, Security Architect
- Development: Firmware Engineer, Backend Engineer, Frontend Engineer, DevOps Engineer
- Quality: QA Engineer, Reviewer, Performance Engineer

## Naming convention

AEOS favors predictable file naming:

- agents/*.agent.md
- skills/*.skill.md
- standards/*.standard.md
- workflows/*.workflow.md

## AI loading order

Before implementation, an AI agent should gather context in this order:

README -> INDEX -> MANIFEST -> PROJECT CONTEXT -> ARCHITECTURE -> RELEVANT STANDARDS -> RELEVANT SKILLS -> RELEVANT WORKFLOW -> IMPLEMENT

## Release identity

AEOS v0.1.0

Codename: Genesis

## Repository layout

- docs/: architecture, principles, standards, workflows, and decisions
- agents/: role definitions and operating contracts
- prompts/: reusable prompts and instruction packs
- skills/: domain knowledge for specific technologies
- standards/: coding, review, architecture, and documentation standards
- workflows/: repeatable engineering processes
- templates/: ADR, RFC, PR, issue, and README templates
- checklists/: review and release checklists
- examples/: reference patterns
- tools/: automation and utility scripts
- schemas/: machine-readable definitions

## First steps

1. Read the principles and standards.
2. Adapt the templates for your project.
3. Add domain-specific skills and workflows.
4. Use the agents and prompts as a base for AI-assisted delivery.

## Status

This repository is the Genesis release of AEOS and establishes the foundation for a broader ecosystem.

# Architecture Overview

AEOS is organized as a layered system:

- Foundation: mission, vision, principles
- Standards: coding, review, documentation, architecture
- Runtime: agents, workflows, prompts, skills
- Delivery: templates, checklists, examples, schemas

This structure keeps the framework stable while allowing the underlying AI tools to evolve.

## Domain-based document model

Knowledge is grouped into durable domains so that humans and AI agents can find the right asset quickly. The expected domains are Vision, Principles, Standards, Agents, Skills, Workflows, Templates, Checklists, Architecture, and Examples.

## Agent hierarchy

AEOS uses a hierarchical role model that separates product, architecture, delivery, and quality concerns. This reduces ambiguity and keeps responsibilities clear.

## AI execution model

Every task should begin with context gathering in a fixed order: README, INDEX, MANIFEST, PROJECT CONTEXT, ARCHITECTURE, relevant standards, relevant skills, relevant workflow, and only then implementation.

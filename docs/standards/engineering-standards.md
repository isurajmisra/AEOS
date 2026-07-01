# Engineering Standards

## Code

- Prefer simple, readable implementations.
- Keep functions focused and composable.
- Use descriptive names and consistent formatting.
- Make decisions that align with AEOS principles rather than local preference.

## Review

- Review for correctness, clarity, and maintainability.
- Require tests or validation evidence for meaningful changes.
- Ensure changes are small enough to be understood and reviewed quickly.

## Documentation

- Document public behavior and operational assumptions.
- Keep docs close to the relevant work.
- Treat documentation as a product asset and maintain one source of truth.
- Record significant decisions in ADRs when the impact is material.

## Architecture

- Favor clear boundaries and explicit contracts.
- Avoid introducing unnecessary dependencies.
- Define the system before implementation begins.
- Organize knowledge into documented domains so that artifacts can be found predictably.

## Execution model

When an agent performs work, it should first gather context in this order: README, INDEX, MANIFEST, PROJECT CONTEXT, ARCHITECTURE, relevant standards, relevant skills, relevant workflow, then implementation.

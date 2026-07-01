# Testing Standard

## Purpose

Testing is a first-class artifact in AEOS. This standard defines the expectations for how tests should be written, maintained, and reviewed.

## Rules

- Write tests before or alongside implementation whenever possible.
- Keep tests small, deterministic, and focused on a single behavior.
- Use descriptive names that explain the expected outcome.
- Include regression coverage for bug fixes.
- Treat test artifacts as part of the documentation for the system.

## Types of tests

- Unit tests for isolated code paths.
- Integration tests for component interactions.
- End-to-end or validation tests for cross-system behavior.

## Review

- Confirm tests cover the new or changed behavior.
- Verify tests are readable and maintainable.
- Ensure tests are run as part of the development and release workflow.

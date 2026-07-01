# Bug Fix Workflow

## Purpose

Define a repeatable workflow for fixing defects in AEOS-based projects.

## Steps

1. Confirm the bug and reproduce it.
2. Gather context: `README.md`, `INDEX.md`, `MANIFEST.md`, architecture, standards, workflows.
3. Identify the smallest safe change.
4. Implement the fix in a focused PR.
5. Add or update tests to cover the bug.
6. Update documentation if the behavior or interface changed.
7. Review the fix against AEOS standards and checklists.

## Review criteria

- The fix is minimal and easy to review.
- The bug is reproduced or the cause analyzed.
- The solution follows relevant standards.
- Tests verify the behavior.

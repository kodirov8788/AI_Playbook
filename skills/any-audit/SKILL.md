---
name: any-audit
description: Use when any or unsafe casts are hiding bugs in TS.
---

# Specialist Skill: Compile-time Type Audit

Use this skill when auditing modules to remove loose `any` declarations, unsafe assertions (`as`), or untyped library imports.

## Process
1. Inspect imports, signatures, and casting constructs.
2. Replace `any` with `unknown` + narrowing runtime guard checks, or generate concrete interfaces.
3. Validate there are no implicit or explicit compile-time typing leaks.

## Output Shape
*   **Unsafe spots:** `<paths and declarations utilizing any or unsafe casts>`
*   **Why:** `<explanation of typing defect and hidden bug risks>`
*   **Safer type:** `<proposed type structures and validation runtime guards>`

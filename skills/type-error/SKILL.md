---
name: type-error
description: Use when there is a confusing TS / build type error.
---

# Specialist Skill: TypeScript Error Diagnosis

Use this skill when facing confusing TypeScript compilation errors, type mismatches, or build breaks.

## Process
1. Inspect the exact compiler error output.
2. Locate the source line and trace recursive declarations or type evaluations.
3. Formulate a solution that addresses the strict compilation requirements.

## Output Shape
*   **Problem:** `<exact error details and failing location>`
*   **Expected:** `<type shape TS compiler expects>`
*   **Actual:** `<type shape actually resolved>`
*   **Why:** `<root cause of mismatch or structural violation>`
*   **Fix path:** `<proposed code changes to resolve the type error>`

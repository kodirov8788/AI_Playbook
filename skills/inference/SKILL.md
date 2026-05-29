---
name: inference
description: Use when types collapse to any or unknown.
---

# Specialist Skill: Inference Debugging

Use this skill when implicit types collapse unexpectedly to `any` or `unknown`, losing compile-time type safety.

## Process
1. Pinpoint the expression or variable where inference breaks.
2. Trace context-sensitive typing across parameter lists, default values, and function returns.
3. Apply assertions or explicit type annotations to restore compile-time safety.

## Output Shape
*   **Input:** `<original expression and expected implicit type>`
*   **Inferred:** `<what type TS actually inferred>`
*   **Where it breaks:** `<the precise line or declaration where inference collapsed>`
*   **Better:** `<corrected declaration with proper annotations>`

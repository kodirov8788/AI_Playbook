---
name: generics
description: Use when a generic is confusing or mis-shaped.
---

# Specialist Skill: Generics Scoping

Use this skill when designing or debugging complex generic parameter constraints, mapping structures, or recursive generic interfaces.

## Process
1. Inspect the generic parameters and constraints (`extends`).
2. Verify generic parameter defaults and inference behavior in call sites.
3. Simplify complex generic mapping to prevent recursion limit failures.

## Output Shape
*   **Goal:** `<intended generic abstraction target>`
*   **Current:** `<original generic parameter block>`
*   **Problem:** `<why generic constraints fail or collapse>`
*   **Simpler:** `<refined generic implementation>`
*   **Signature:** `<exact signature declaration example>`

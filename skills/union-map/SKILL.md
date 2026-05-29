---
name: union-map
description: Use when messy union or failed narrowing occurs.
---

# Specialist Skill: Union Discrimination

Use this skill when handling union types that cannot be narrowed cleanly, or when types lack a clear discriminator key.

## Process
1. Inspect the union states.
2. Establish a clear discriminator property (e.g. `type` or `kind`).
3. Build complete exhaustiveness checking (`never` type fallback) for switch-case logic.

## Output Shape
*   **Current:** `<original messy union declaration>`
*   **States:** `<list of union states and fields>`
*   **Missing discriminator:** `<analysis of why narrowing fails>`
*   **Model:** `<corrected discriminated union structure>`

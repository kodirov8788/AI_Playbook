---
name: library-pattern
description: Use when building a reusable abstraction or SDK package.
---

# Specialist Skill: Reusable SDK Abstraction

Use this skill when designing a modular package, shared library API, or reusable abstraction layer.

## Process
1. Inspect the implementation details, ensuring isolation from environment-specific variables.
2. Select clean, minimal public exports and hide internal configurations.
3. Design fluent interfaces, dependency injection boundaries, and comprehensive types.

## Output Shape
*   **Pattern:** `<chosen architectural pattern (e.g. wrapper, factory, strategy)>`
*   **Current:** `<original messy or tightly coupled implementation>`
*   **Better:** `<clean decoupled library signature interface>`
*   **DX impact:** `<explanation of ease-of-use upgrades>`

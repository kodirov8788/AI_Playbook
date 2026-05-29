---
name: type-transform
description: Use when deriving or transforming a type from another.
---

# Specialist Skill: Type Transformations

Use this skill when deriving new types from existing models or interfaces (e.g. mapping keys, transforming props, mapping DTOs to models).

## Process
1. Inspect the source interface or model.
2. Select appropriate TypeScript utility types (`Omit`, `Pick`, `Partial`, `Record`, etc.) or conditional types.
3. Map properties cleanly without introducing duplicate source fields.

## Output Shape
*   **Source:** `<original model/type>`
*   **Target:** `<intended transformed type shape>`
*   **Transform:** `<the transformation code syntax>`
*   **TS utility:** `<utility types or mapped keys employed>`

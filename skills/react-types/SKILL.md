---
name: react-types
description: Use for Props, hook, ref, or event typing issues in React.
---

# Specialist Skill: React Component Typing

Use this skill when encountering typing issues with React functional component props, standard hooks, ref parameters, or native DOM events.

## Process
1. Inspect the component signature or standard hooks/refs parameters.
2. Select React-specific typings (e.g. `React.ComponentProps`, `React.MouseEvent`, `React.RefObject`).
3. Clean up loose callback signatures to prevent compile errors in event propagation.

## Output Shape
*   **Component:** `<name and current signature of React component>`
*   **Props:** `<props interface definition>`
*   **Problem:** `<why React typing throws compilation warnings>`
*   **Better type:** `<corrected types for elements/callbacks/refs>`

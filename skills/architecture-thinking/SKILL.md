---
name: architecture-thinking
description: Directives for modular layout design, separation of concerns (SoC), strict compile-time typing, and dependency injection boundaries.
---

# Specialist Skill: Architectural Thinking

## Key Directives
- **Separation of Concerns (SoC):** Decouple database clients, business models, API controllers, and view layouts.
- **Dependency Injection:** Pass external utilities (loggers, db clients, fetchers) as parameters rather than hardcoding imports.
- **DRY vs. WET:** Keep logic DRY, but avoid premature abstractions that couple unrelated domain behaviors.
- **Strict Typing:** Never fallback to `any` or loose type casting. Maintain compile-time safety across all layers.

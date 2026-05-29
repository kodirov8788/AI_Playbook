---
name: improve-architecture
description: Audit and optimize codebase structures using the 'Deep Modules' philosophy (simple interfaces hiding complex implementations).
---

# Specialist Skill: Improving Codebase Architecture

## Core Philosophies (John Ousterhout)
- **Deep Modules:** Aim for modules that present a simple, clean, and minimal public interface, hiding the complex computational logic inside.
- **Shallow Modules:** Avoid modules whose interface is almost as complex as their implementation (e.g., simple pass-through helpers). These increase cognitive load.

## Auditing Workflow
1. **Friction Analysis:** Walk the codebase. Look for:
   - High coupling (changing one file forces edits in 3 other files).
   - Leaky abstractions (client must understand internal DB queries or state).
   - Shallow interfaces.
2. **Propose Refactoring Candidates:** Detail each opportunity, analyzing:
   - Test impact (how much test code must be modified).
   - Depth score (how much complexity we will hide).
3. **Interface Design Loop:** Draft 2-3 interface signatures and select the one that maximizes ease-of-use (Developer Experience) and encapsulates logic best.

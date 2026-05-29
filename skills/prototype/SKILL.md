---
name: prototype
description: Build a throwaway, lightweight prototype or MVP to test designs and validate architectures before committing to production.
---

# Specialist Skill: Prototyping & MVP Verification

## Core Directives
1. **Speed & Isolation:** Write a lightweight, self-contained mock implementation (e.g., a runnable Node/Python terminal script) inside the `.ai/scratch/` directory.
2. **No Production Pollution:** Do not edit your core production files or database schemas during the prototyping phase.
3. **Encapsulate Side-Effects:** Mock external APIs, database networks, and auth middlewares using simple local JSON mock databases or standard stub responses.
4. **Validation Loop:** Present the prototype's execution output to the user. Once the design is validated, discard the prototype and plan the stable production implementation using TDD.

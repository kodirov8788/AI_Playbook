---
name: tdd
description: Disciplined Red-Green-Refactor workflow prioritizing vertical behavioral slicing over structural slice testing.
---

# Specialist Skill: Test-Driven Development (TDD)

## Core Directives
1. **Vertical Iteration (Red-Green-Refactor):** 
   - Never write horizontal slices (writing all tests first, then all code).
   - Write **one** failing test first (Red).
   - Write the **minimum** amount of production code to pass the test (Green).
   - Refactor immediately to clean up duplication and deepen interfaces (Refactor).
2. **Test Interfaces, Not Internals:**
   - Write assertions targeting the public module boundaries.
   - Avoid mocking internal helper functions; test the final behavioral side-effects. This prevents test fragility during future structural refactoring.
3. **Refactor Phase Guard:**
   - Do not add new features during the Refactor phase.
   - Keep the test suite executing continuously.

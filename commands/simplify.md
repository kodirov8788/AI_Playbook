# Command: Simplify

Refactoring goals to execute when invoked:
1. **Flat Nesting:** Reduce nested conditional flows into early exit clauses.
2. **Atomic Functions:** Break down large multi-responsibility functions into single-purpose pure functions.
3. **State Consolidation:** Replace multiple local state hooks with cohesive unified state representations or state machines.
4. **Eliminate Abstractions:** Delete wrapper utilities that add indirection without adding security, testing, or API normalization.

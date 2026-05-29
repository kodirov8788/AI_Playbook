# Command: Grill Me

When this command is invoked, the agent must challenge the active implementation plan by raising:
1. **Weak Assumptions:** Highlight where client inputs, network states, or API responses are assumed to be perfect.
2. **Edge Cases:** Push boundaries on high loads, missing headers, extreme input lengths, and concurrent state changes.
3. **Tradeoffs:** Compare alternative architectural choices and identify what is being sacrificed (speed vs. simplicity).
4. **Fail-safes:** Demand disaster-recovery or database rollback strategies.

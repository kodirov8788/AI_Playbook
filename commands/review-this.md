# Command: Review This

When auditing a PR or a codebase block:
1. Check for hardcoded credentials, secrets, or unsecured HTTP protocols.
2. Ensure variable naming conforms to repository conventions.
3. Identify redundant variables, memory leak sources, and blockages in asynchronous loops.
4. Output a clear checklist of recommended modifications categorized by priority (Blocker, Major, Minor).

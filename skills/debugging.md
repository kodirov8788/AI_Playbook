# Specialist Skill: Root Cause Debugging

## Protocol Sequence
1. **Isolate & Reproduce:** Create a minimal reproducible example (MRE) or a scratch script in the `.ai/scratch/` directory.
2. **State Delta Analysis:** Log state variables immediately before, during, and after the failure event to map mutation paths.
3. **Binary Search Logs:** Systematically isolate boundaries by analyzing log traces from entry point to exit point.
4. **Side-Effect Audit:** Check for race conditions, unhandled promise rejections, database lock timeouts, and third-party API dependencies.

# Command: grill

## Trigger
Invoked via `/grill` or `grill`.

## Actions
1. Audit current proposed implementation plans against engineering guidelines and repo-specific standards.
2. Search for hidden edge cases, performance assumptions, or structural concerns.
3. Output details formatted exactly as:
   - Weak assumptions: `<details on what could break>`
   - Blind spots: `<omitted features or requirements>`
   - Better option: `<alternative architecture/implementation>`
   - Questions: `<clarifying queries for the team>`

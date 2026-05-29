# Command: pr-comment

## Trigger
Invoked via `/pr-comment` or `pr-comment`.

## Actions
1. Format a clean PR review comment listing all pending items as checkbox markdown.
2. Ensure format matches:
   ```markdown
   - [ ] Description of the todo goes here
   ```
3. Exclude conversational filler. Print only after `y` gate.

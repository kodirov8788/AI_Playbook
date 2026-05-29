# Command: changeset

## Trigger
Invoked via `/changeset` or `changeset`.

## Actions
1. Create a changeset file named `.changeset/0000-*.md`.
2. Format exactly as:
   ```markdown
   ---
   "<package>": patch|minor|major
   ---

   Description of the change.
   ```
3. Write to the filesystem only upon `y` approval.

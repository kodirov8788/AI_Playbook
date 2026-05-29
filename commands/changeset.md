# Command: changeset

## Trigger
Invoked via `/changeset` or `changeset`.

## Actions
1. Map out active component changes to generate release notes.
2. Structure the changeset in exact format:
   ```markdown
   ---
   "<pkg>": patch|minor|major
   ---

   One-line description of the change.
   ```
3. Halt at the standard lowercase `y/n` approval gate before saving to `.changeset/0000-*.md`.

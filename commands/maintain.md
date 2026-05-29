# Command: maintain

## Trigger
Invoked via `/maintain` or `maintain`.

## Actions
1. Audit current repository rules, memory logs, and `.agent` context mappings against active branch progress.
2. Formulate highly precise diffs for updating overview, file-map, architecture, and sessions rule configurations.
3. Show proposed rule diffs, then halt at the standard lowercase `y/n` approval gate.
4. If approved with `y`, write the updated rules directly to the `.agent/project-rules/` folder.

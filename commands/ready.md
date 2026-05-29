# Command: ready

## Trigger
Invoked via `/ready` or `ready`.

## Actions
1. Run `git status --short` to ensure working directory is clean.
2. Read the latest `.agent/project-rules` context.
3. Output exactly `Ready. Waiting command.` if clean.

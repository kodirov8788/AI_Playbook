# Command: init

## Trigger
Invoked via `/init` or `init`.

## Actions
1. Detect project name using `basename $PWD`.
2. Check for existing context folder `.agent/project-rules/<project-name>/`.
3. Check for external changes since the last saved session using:
   - `git status --short`
   - `git diff`
   - `git log --oneline -5`
4. If changes exist, execute the changes review flow immediately before initializing.

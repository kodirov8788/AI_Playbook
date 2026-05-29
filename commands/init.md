# Command: init

## Trigger
Invoked via `/init` or `init`.

## Actions
1. Load project context, repository guidelines, and `.agent` rule configurations.
2. Check `git status`, diff log, and GitHub PR/issue tracking.
3. Compare local tracking branches against remote state.
4. Output `Ready. Waiting command.` if everything is clean and idle.

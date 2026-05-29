# Command: commit

## Trigger
Invoked via `/commit` or `commit`.

## Actions
1. Review uncommitted changes and active staging buffers.
2. Formulate a highly concise commit message (e.g. `sync maintain files`, `fix auth redirect`).
3. Show changed files, diff status, and proposed message.
4. Halt at the standard lowercase `y/n` approval gate before executing the Git commit.

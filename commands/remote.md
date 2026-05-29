# Command: remote

## Trigger
Invoked via `/remote` or `remote`.

## Actions
1. Audit tracking branch commits against origin.
2. Output details formatted exactly as:
   - Branch: `<active branch>`
   - Ahead-behind: `<count of unpushed/unpulled commits>`
   - Unpushed: `<list of unpushed commits>`
   - PRs: `<list of remote pull requests>`

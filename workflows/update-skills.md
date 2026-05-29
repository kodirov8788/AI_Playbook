# Workflow: Central Skill Synchronization

## Trigger
When the user says "update skills" or asks to synchronize skills.

## Operational SOP

### Phase 1: Remote Reconnaissance
1. Run `read_url_content` on:
   - `https://github.com/mattpocock/skills` (Primary engineering reference)
2. Scan the remote files, commit history, and README to identify if:
   - A skill file has been modified or improved.
   - A new skill directory has been added.

### Phase 2: Audit & Comparison
1. Compare the retrieved remote skills with the local files inside `~/AI_Playbook/skills/`.
2. Map out any differences:
   - Identical skills with updated logic.
   - Completely new skill blocks.

### Phase 3: Proposal & Approval
1. Present the diffs in a structured format (showing BEFORE/AFTER or NEW files).
2. Detail the exact actions to take (Step-by-Step).
3. Halt at the standard lowercase `y/n` approval gate.

### Phase 4: Safe Execution
1. Once approved with `y`, write the updated/new skills in the compliant folder-based `SKILL.md` format.
2. Update the `index.md` routing table and `changes.md` log files.
3. Commit and push the updates to GitHub.

# AI Loading Order Protocol

When an AI agent boots up in a client workspace:

1. **Verify Bootloader Connection:** Check if local `CLAUDE.md` points to `~/AI_Playbook/index.md`.
2. **Read Playbook Index:** Read `~/AI_Playbook/index.md` first to fetch the routing registry.
3. **Resolve Task Type:** Inspect the current user request and resolve which playbook modules (skills, workflows, principles) match the task.
4. **Load Rules into Context:** Dynamically read the required markdown files from the playbook directory.
5. **Begin Session:** Process user goals using the retrieved cognitive templates.

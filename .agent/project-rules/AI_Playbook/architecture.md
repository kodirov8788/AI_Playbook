# Playbook Architecture & Dynamic Loading

## Bootstrap Sequence
1. Project agent boots and reads local `CLAUDE.md` or `.ai/bootstrap.md`.
2. Bootstrap file contains an absolute path reference to `~/AI_Playbook/index.md`.
3. Agent reads `index.md` to identify files matching the active task.
4. Agent reads selected `.md` files into active memory.

## Module Categories
- **Core:** Global operational limits. Must always be loaded.
- **Skills:** Specialized analytic patterns. Loaded on demand.
- **Commands:** Interactive workflows. Executed upon explicit user slash command.
- **Workflows:** Multi-phase execution plans.

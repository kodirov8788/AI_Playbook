# Playbook Change Log

- Initialized Project Rules Memory (.agent/)
- Created directory skeleton (core, skills, commands, workflows, project-bootstrap)
- Created dynamic router (`index.md`)
- Populated `skills/` with backend-review.md, debugging.md, architecture-thinking.md, and ui-review.md.
- Populated `commands/` with grill-me.md, review-this.md, think-deeper.md, and simplify.md.
- Populated `patterns/` with nextjs-structure.md, firebase-auth.md, and api-design.md.
- Populated `workflows/` with feature-planning.md, bug-investigation.md, and release-checklist.md.
- Created human explanation master document (`README.md`).
- Refactored `skills/` directory into folder-based skill packages matching official Anthropic progressive disclosure spec:
  - backend-review/SKILL.md
  - debugging/SKILL.md
  - architecture-thinking/SKILL.md
  - ui-review/SKILL.md
- Created and registered new advanced agentic skills from mattpocock/skills:
  - tdd/SKILL.md (vertical test-driven loops)
  - improve-architecture/SKILL.md (John Ousterhout Deep Modules refactoring)
  - handoff/SKILL.md (agent state handoff markdown format)
- Created skill synchronization workflow (`workflows/update-skills.md`) and added automated "update skills" trigger in `core/guidance.md`.
- Created and registered new advanced engineering skills:
  - to-prd/SKILL.md (distill session to PRDs)
  - to-issues/SKILL.md (vertical task decomposition)
  - prototype/SKILL.md (throwaway MVP verification loops)
- Created and registered all 14 repository operations command guides under `commands/` and registered them inside the dynamic loading router:
  - init.md, status.md, review.md, diagnose.md, issues.md, pr-comment.md, maintain.md, changeset.md, commit.md, zoom.md, step.md, plan.md, remote.md, ready.md





# Playbook System Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Context Clutter | High | Never copy playbook files into projects. Dynamically load on-demand. |
| Version Drift | Med | All updates happen inside `AI_Playbook`. Projects only reference, never duplicate. |
| Over-Coupling | Med | Do not put project-specific business logic or sprint notes in this repository. |

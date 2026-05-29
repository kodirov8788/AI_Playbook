---
name: handoff
description: Formats active session state, design decisions, and unresolved tasks into a structured markdown block for handoff.
---

# Specialist Skill: Agent Handoff

## Core Directives
When ending a session, transferring work, or handing off to another agent, generate a structured Handoff context block:

```markdown
# Session Handoff

## 🎯 Active Goal
[Describe the exact feature/bug being worked on]

## 🛠️ Completed Changes
[List files edited and what was accomplished]

## 📌 Active State & Context
[Describe current state, server outputs, or build flags]

## 📝 Next Actions
- [ ] Task 1
- [ ] Task 2

## ⚠️ Unresolved Risks / Blockers
[Uncaught exceptions, missing environment vars, or pending design choices]
```

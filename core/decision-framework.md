# Decision Framework

## The Execution Cycle
```
  ┌────────────────────────────┐
  │  Research & Audit Context  │
  └─────────────┬──────────────┘
                │
                ▼
  ┌────────────────────────────┐
  │   Build Structured Plan    │
  └─────────────┬──────────────┘
                │
                ▼
  ┌────────────────────────────┐
  │ Ask Clarifying Questions   │
  └─────────────┬──────────────┘
                │
                ▼
  ┌────────────────────────────┐
  │ Present Steps & Gate       │
  └─────────────┬──────────────┘
                │
        ┌───────┴───────┐
    [y] │           [n] │
        ▼               ▼
┌──────────────┐┌──────────────┐
│ Deterministic││  Halt / Plan │
│  Execution   ││   Revision   │
└──────────────┘└──────────────┘
```
- Always inspect dependencies and config schemas before executing a change.
- Challenge assumptions before choosing an implementation route.

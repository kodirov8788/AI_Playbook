---
name: to-issues
description: Decomposes a plan, spec, or PRD into independently actionable developer issues using vertical slicing.
---

# Specialist Skill: Decomposing Plans into Developer Issues

## Core Directives
1. **Vertical Slicing:** Avoid horizontal slices (e.g., "build all DB tables" or "design all UI buttons"). Create vertical slices that represent complete, end-to-end user stories (e.g., "implement login form and DB auth check").
2. **Issue Format:** Every decomposed issue must be outputted in structured checkbox markdown:

```markdown
### 🎫 Issue: [Descriptive Title]

#### 🎯 Goal
[What this issue accomplishes]

#### 🛠️ Tasks
- [ ] Task 1 (Database schema changes)
- [ ] Task 2 (API route controller)
- [ ] Task 3 (Frontend UI page/component)

#### 🧪 Verification Plan
- [ ] Run test suite command `...`
- [ ] Verify visually via `...`
```

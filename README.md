# 🚀 Centralized AI Operating Layer (Playbook)

Welcome! This repository is **not** just a collection of static prompts—it is a **centralized intelligence layer and cognitive operating system** for AI-assisted software engineering.

By separating **How an AI thinks** (operational principles, debugging methods, quality standards) from **What you are building** (project-specific requirements and business logic), this playbook ensures zero version drift, optimized context windows, and unified engineering standards across all your codebases.

---

## 🏗️ Architectural Anatomy

```
     [ Local Project Codebase ]
                 │
                 ▼ (Reads bootloader instruction)
       [ AI Agent Context ] ◄─── (Dynamic on-demand load) ───┐
                                                            │
                                                   [ ~/AI_Playbook/ ]
                                                            ├── core/ (Global laws & communication)
                                                            ├── skills/ (Specialized diagnostics)
                                                            ├── commands/ (Interactive operations)
                                                            └── workflows/ (Step-by-step recipes)
```

- 📂 **`core/` (The Constitution):** Base parameters that control agent personality, communication styles, decision matrices, and absolute default safety boundaries.
- 📂 **`skills/` (Analytical Tools):** Heavyweight cognitive procedures (e.g., deep type audits, system debugging sequences, aesthetic UI reviews).
- 📂 **`commands/` (Directives):** High-level interactive instructions (e.g., `/grill-me` to challenge code paths, `/simplify` to refactor).
- 📂 **`patterns/` (Reference Designs):** Best-practice layout and integration blueprints (e.g., modern Next.js directory hierarchy, secure authentication templates).
- 📂 **`workflows/` (Standard Operating Procedures):** Actionable recipes showing exactly how to execute a sequence of events (e.g., pre-release checks or bug investigations).
- 📂 **`project-bootstrap/` (The Bootloader):** The blueprint on how any repository hooks itself up to this central intelligence layer.

---

## 🔌 How to Connect Your Projects (For Humans)

Connecting a new codebase to your playbook takes less than a minute.

### Step 1: Create a Bootloader File
In the root directory of your project, create or open a `CLAUDE.md`, `.cursorrules`, or `AGENTS.md` file.

### Step 2: Add the Bootloader Block
Insert this block at the absolute top of the file:

```markdown
## 🧠 AI Playbook Bootloader
Always begin your session by reading the dynamic routing table:
- Map directory: `~/AI_Playbook/index.md`

Based on my current goals, dynamically load the matching core guidance and task-specific modules before planning or changing any code.
```

### Step 3: Tell Your AI Agent to Boot
When starting a session inside your project, simply instruct the AI:
> *"Read CLAUDE.md and load the appropriate skills/workflows from my central Playbook to help me plan [Feature/Bug]."*

---

## 📈 How to Evolve Your Playbook
As you build more apps, you will discover better prompts, tighter guidelines, and new technology stacks. 
1. **To update engineering rules globally:** Simply edit files in `~/AI_Playbook/core/` or `~/AI_Playbook/skills/`. All connected projects will immediately inherit the upgrades.
2. **To keep context clean:** Always place project-specific sprint details or API tokens inside the local project files—never in this global playbook!

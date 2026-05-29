---
name: to-prd
description: Packages conversational request context into a structured Product Requirements Document (PRD).
---

# Specialist Skill: Product Requirements Document (PRD) Generation

## Core Directives
When generating a PRD, compile the current conversation context, goals, and architectural rules into a structured markdown block:

```markdown
# Product Requirements Document (PRD)

## 📌 Executive Summary
[High-level description of what we are building and why]

## 🎯 Target Audience & Core Goals
[Who is the user, and what key problems are we solving?]

## 🛠️ Functional Specifications
- **Req 1:** [Core functionality]
- **Req 2:** [Security/Auth validation]

## 🏗️ Technical Constraints & Stack
- **Languages/Frameworks:** [Next.js App Router, TypeScript, Go, etc.]
- **Database/Storage:** [ACID compliance requirements, migrations]

## 📈 Visual Layout & UX Flow
- [Describe page layout or CLI interfaces in clean ASCII art]

## 📝 Success Criteria & Out-of-Scope
- **In-Scope:** [What must work]
- **Out-of-Scope:** [What we are explicitly NOT building in this MVP]
```

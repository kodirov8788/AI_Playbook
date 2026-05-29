---
name: api-shape
description: Use when frontend/backend models or DTO schema mismatch occurs.
---

# Specialist Skill: API Boundary Synchronization

Use this skill when auditing or debugging differences between backend schemas (DB models / controllers) and frontend API client data objects (DTOs).

## Process
1. Inspect backend endpoints and payload models.
2. Compare to frontend HTTP clients, parsing utilities, or state stores.
3. Align types, adding validation runtime checks if fields are optional.

## Output Shape
*   **Request:** `<payload request schema>`
*   **Response:** `<payload response schema>`
*   **Schema:** `<mismatch analysis between backend payload and frontend parse>`
*   **Mismatch / Owner:** `<which component has structural drift, and recommended owner fix>`

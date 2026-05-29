---
name: backend-review
description: Vetted checkpoints for auditing backend schemas, transaction safety, validation rules, caching, and serialization pipelines.
---

# Specialist Skill: Backend Architecture Review

## Core Auditing Checkpoints
1. **Input Validation:** Enforce strict validation rules (Zod, Joi, or language-native) on all API endpoints. Reject unknown properties.
2. **Database Queries:** Identify N+1 query patterns. Ensure indexes exist on all queried foreign keys and compound query fields.
3. **Transaction Safety:** Wrap mutating operations affecting multiple tables/collections in explicit transactional blocks (ACID compliance).
4. **Authentication & Authorization:** Verify token validation occurs at the middleware layer. Never trust client-side user IDs for resource access.
5. **Caching & Serialization:** Audit payload sizes. Ensure fields are strictly typed and exclude unnecessary relational joins.

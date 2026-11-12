---
name: backend-supabase
description: Design secure backend services and Supabase databases, authentication, storage, policies, and server-side integrations.
---

# Backend and Supabase

## Workflow
1. Identify entities, relationships, ownership, roles, and data lifecycle.
2. Design schema with constraints, indexes, timestamps, and migration strategy.
3. Enable Row Level Security for user-facing tables and write least-privilege policies.
4. Keep privileged service-role keys on trusted server environments only.
5. Validate all input on the server; do not trust client-side role checks.
6. Configure storage buckets and object policies deliberately.
7. Use server/edge functions for secrets and privileged external API calls.
8. Test access as anonymous, user A, user B, and admin; verify users cannot access each other's records.
9. Back up before destructive migrations and document rollback steps.

## Security rules
Never expose keys in frontend bundles, logs, screenshots, or Git history. Do not disable RLS as a shortcut. Do not store passwords in plaintext. Collect only necessary personal data.

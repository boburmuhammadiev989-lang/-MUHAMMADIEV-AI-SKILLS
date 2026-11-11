---
name: ai-web-development
description: Build and improve real apps, websites, and bots with AI coding tools such as Base44, Lovable, Replit, Bolt, and similar platforms.
---

# AI web development

## Before building
- Clarify user problem, target users, core flows, platform, languages, data, roles, integrations, and launch constraints.
- Inspect the existing app and current implementation before prompting an AI builder.
- Write acceptance criteria and a phased plan; separate MVP from future features.
- Prefer a working vertical slice over a large mockup.

## Build workflow
1. Map pages, navigation, states, roles, and data entities.
2. Define auth, permissions, storage, database, notifications, and integrations explicitly.
3. Prompt the builder with scope, constraints, expected behavior, edge cases, and tests.
4. Build in small phases; inspect generated code and app behavior after each phase.
5. Verify every button, form, upload, filter, navigation action, and error state.
6. Test logged-out, new-user, returning-user, empty, loading, success, and failure states.
7. Test responsive layouts and localization, including RTL if supported.
8. Document environment variables and deployment steps without exposing secrets.

## Prompt structure
Context → goal → existing behavior to preserve → exact changes → data/security rules → UI behavior → acceptance tests → out-of-scope items.

## Rules
Do not call a prototype production-ready. Do not remove working features without approval. Confirm pricing, platform limits, and integrations from current official sources. Avoid hard-coded secrets and fake API responses.

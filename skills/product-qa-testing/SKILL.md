---
name: product-qa-testing
description: Turn product requirements into acceptance criteria and test real app behavior before release.
---

# Product QA and testing

## Planning
1. Convert each requirement into observable acceptance criteria.
2. Prioritize critical user journeys and high-risk integrations.
3. Build a test matrix for roles, devices, browsers, languages, and data states.
4. Include positive, negative, boundary, and regression cases.

## Execution
- Test the actual running product, not just source code or screenshots.
- Verify links, buttons, forms, validation, uploads, permissions, emails, payments, and persistence.
- Test mobile viewport, slow network, empty data, expired sessions, and server errors.
- Record reproducible steps, expected result, actual result, and evidence.
- Re-test fixes and adjacent flows.

## Release gate
No critical security/data-loss bugs; core journeys work; no broken navigation; accessibility basics checked; backup/rollback plan exists. Clearly separate tested, untested, and blocked items.

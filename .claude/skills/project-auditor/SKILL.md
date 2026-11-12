---
name: project-auditor
description: Audit an existing app, website, bot, or AI project for broken flows, UX problems, security risks, performance issues, and release readiness before making changes.
---

# Project auditor

## Audit-first rule
Do not change code during the initial audit unless explicitly asked. Inspect the repository and running product, then establish scope.

## Review areas
- Product flows: onboarding, auth, navigation, forms, uploads, payments, notifications, admin.
- UI/UX: responsive layouts, accessibility, localization, loading/empty/error states.
- Engineering: architecture, duplicated logic, dependencies, errors, performance, maintainability.
- Security: secrets, authorization, data isolation, input validation, rate limits, privacy.
- Operations: logs, backups, deployment config, environment variables, monitoring.

## Evidence format
For each finding provide severity, affected location/flow, reproduction steps, expected behavior, actual behavior, evidence, and recommended fix. Separate confirmed defects from suspected risks.

## Completion
Produce a prioritized plan: critical blockers, high-priority fixes, improvements, and optional polish. Do not claim a feature works unless tested. After authorized fixes, rerun regression tests and report remaining limitations.

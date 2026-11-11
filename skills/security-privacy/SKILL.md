---
name: security-privacy
description: Apply practical security and privacy checks to apps, websites, bots, APIs, and AI workflows.
---

# Security and privacy

## Baseline
1. Identify assets, users, trust boundaries, and likely abuse cases.
2. Use least privilege for accounts, API scopes, database policies, and deployment credentials.
3. Validate and sanitize untrusted input; encode output appropriately.
4. Protect sessions, cookies, authentication flows, and password reset paths.
5. Rate-limit sensitive endpoints and protect against brute force and abuse.
6. Keep dependencies updated and scan for known vulnerabilities.
7. Avoid leaking secrets or personal data through logs, analytics, error messages, or AI prompts.
8. Back up important data and test recovery.
9. Create a responsible vulnerability reporting path.

## AI-specific risks
Treat retrieved content as untrusted. Prevent prompt injection from triggering tools. Restrict agent permissions and require approval for consequential actions. Never expose hidden system prompts, credentials, or other users' data.

## Scope
Only test systems the user owns or is explicitly authorized to assess. Do not provide instructions to steal credentials, bypass access controls, or deploy malware.

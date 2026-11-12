# MUHAMMADIEV AI SKILLS

A practical, growing skill library for building AI-powered apps, websites, Telegram bots, agents, and video/content workflows.

**Owner:** MUHAMMADIEV  
**Languages:** Uzbek (default), English, Turkish, Russian  
**Principles:** real working products, verify before claiming, prefer free/low-cost tools, protect credentials, preserve existing functionality.

## How to use
Each folder contains a `SKILL.md` with triggers, workflow, quality checks, and safety rules. Read the relevant skill before starting a task. These are reusable instructions; they do not automatically install themselves into ChatGPT or any other model.

## Skill index
- [AI video production](skills/ai-video-production/SKILL.md)
- [Video editing and post-production](skills/video-editing/SKILL.md)
- [AI web development](skills/ai-web-development/SKILL.md)
- [Frontend engineering](skills/frontend-engineering/SKILL.md)
- [Backend and Supabase](skills/backend-supabase/SKILL.md)
- [AI agents and MCP](skills/ai-agents-mcp/SKILL.md)
- [Instagram and content growth](skills/instagram-growth/SKILL.md)
- [Social automation](skills/social-automation/SKILL.md)
- [UI/UX and design systems](skills/ui-ux-design/SKILL.md)
- [SEO and analytics](skills/seo-analytics/SKILL.md)
- [Security and privacy](skills/security-privacy/SKILL.md)
- [Product QA and testing](skills/product-qa-testing/SKILL.md)

## Working rules
1. Inspect the existing project before changing it.
2. Never invent integrations, features, metrics, prices, or successful test results.
3. Preserve working functionality; make focused, reversible changes.
4. Test on mobile and desktop where relevant.
5. Use official documentation for changing APIs and platform policies.
6. Never commit API keys, passwords, tokens, personal data, or private customer information.
7. Ask before destructive actions, paid services, public publishing, or production deployment.

## Upstream inspiration
This library is independently written and links to upstream projects for further study:
- https://github.com/affaan-m/ECC
- https://github.com/obra/superpowers
- https://github.com/anthropics/skills
- https://github.com/vercel-labs/agent-skills
- https://github.com/coreyhaines31/marketingskills
- https://github.com/mattpocock/skills

Check each upstream repository's license before copying or redistributing its files.

## Claude support

Claude Code project skills are included under `.claude/skills/<skill-name>/SKILL.md`. Open this repository as a project in Claude Code and the skills are discoverable as slash commands / contextual skills. Review the skill files before trusting them, especially in repositories that accept outside contributions.

For Claude.ai (web app), custom skills are uploaded separately: package the contents of one skill folder as a ZIP (the ZIP should contain the skill folder with its `SKILL.md`), then open **Customize → Skills → + Create skill → Upload a skill**. Enable Code execution and file creation in Settings → Capabilities if required by your account. The GitHub repository itself does not automatically upload skills into a Claude.ai account.

### Claude Code skills
- [Full-stack app builder](.claude/skills/full-stack-app-builder/SKILL.md)
- [Cinematic video director](.claude/skills/cinematic-video-director/SKILL.md)
- [Instagram growth manager](.claude/skills/instagram-growth-manager/SKILL.md)
- [Telegram bot builder](.claude/skills/telegram-bot-builder/SKILL.md)
- [AI agent and MCP engineer](.claude/skills/ai-agent-mcp-engineer/SKILL.md)
- [Project auditor](.claude/skills/project-auditor/SKILL.md)

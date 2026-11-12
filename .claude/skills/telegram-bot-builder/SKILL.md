---
name: telegram-bot-builder
description: Design, implement, test, and maintain Telegram bots with reliable commands, state, storage, admin tools, and multilingual user experiences.
---

# Telegram bot builder

## Plan
Clarify the bot's purpose, users, commands, languages, admin roles, data, integrations, hosting, and expected load. Draw the conversation states and fallback paths before implementation.

## Build
1. Use the official Telegram Bot API and a maintained framework appropriate to the existing stack.
2. Keep the bot token in environment variables or a secrets manager.
3. Validate all callback data and user input; never trust client-provided user IDs or admin flags.
4. Design persistent state for workflows that must survive restarts.
5. Add duplicate-update/idempotency handling, rate limits, retry strategy, and graceful API failure handling.
6. Provide clear /start, /help, cancel/back, and human-support paths.
7. Separate user and admin permissions; log moderation and admin actions without leaking private data.
8. Support localization consistently, including language selection and fallback text.

## Test
Test new and returning users, invalid commands, repeated callbacks, blocked users, network failures, restart recovery, admin access, and data isolation. Never expose the bot token in source, logs, or screenshots.

# Fewdo releases & skills

[Download Fewdo](https://github.com/caijinyc/fewdo-release/releases)

## Fewdo CLI Skill

[View the Fewdo analysis skill](skills/fewdo-analysis/SKILL.md) to let your AI agent query tasks, goals, schedules, focus records and task images through the CLI bundled with Fewdo for macOS.

Copy this instruction to your agent:

```text
Install the Fewdo skill from https://github.com/caijinyc/fewdo-release/tree/main/skills/fewdo-analysis for this agent, then use the CLI bundled in Fewdo.app to read my tasks.
```

CLI support requires a compatible Fewdo build. If the app has no `Contents/Resources/fewdo-cli/fewdo` entry, use a build that includes the CLI; the skill alone does not add it. AI settings are available in builds that include Settings → AI. Queries are read-only and can work while the app is closed. Keep Fewdo running during use so synced data stays up to date. This repository contains public skill instructions, not user data.

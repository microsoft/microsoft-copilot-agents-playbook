# M365 Declarative Agent Project

This is an M365 Copilot declarative agent project managed by the ATK CLI.

## Available Skills

When working on this project, you MUST use the appropriate skill for the task. **Do NOT work directly on files without invoking a skill first.**

| Skill | When to Use |
|-------|-------------|
| **declarative-agent-developer** | Any task involving this agent (see scenarios below). **This is the primary skill for this project.** |
| **ui-widget-developer** | Only when adding an MCP server that renders rich interactive widgets (HTML) in Copilot Chat using the OpenAI Apps SDK. |
| **install-atk** | Only when the ATK CLI is not installed or needs updating. |

## ⛔ MANDATORY: Invoke `declarative-agent-developer` Skill First

**This is a declarative agent project. For ANY task in this workspace — regardless of what it is — you MUST invoke the `declarative-agent-developer` skill BEFORE doing any work.** This is not optional. Do not attempt to handle any task yourself. Always delegate to the skill.

### Scenarios handled by this skill

- Creating a new agent project from scratch
- Editing manifests (declarativeAgent.json, manifest.json, m365agents.yml)
- Adding or removing capabilities (web search, Graph connectors, etc.)
- Adding API plugins from OpenAPI specs
- Adding MCP server plugins
- Adding OAuth authentication to plugins
- Localizing an agent into multiple languages
- Adding a new language to an already-localized agent
- Writing or updating agent instructions
- Deploying and provisioning with `atk provision`
- Validating the project with `atk validate`
- Fixing manifest errors or validation failures

**Do NOT:**
- Edit `declarativeAgent.json` or other manifest files directly without the skill
- Run `npx -y --package @microsoft/m365agentstoolkit-cli atk` commands without the skill
- "Help" by manually making changes — always delegate to the skill

# Add Skills to Declarative Agents

## Skills structure

Every skill is a folder with exactly one SKILL.md at its root.

```bash
repair-lookup/
   SKILL.md
   reference/
      error-codes.json
   scripts/
      lookup.py
```
**Rules:**
- Exactly one `SKILL.md` — skill.md and SKILL.md both work
- It must sit at the root of the skill directory
- The folder named in the manifest must exist and match the name in `SKILL.md`
- Scripts allowed: Python, JavaScript/Node.js and Bash

## In Declarative Agent

Skills ship inside the agent package, declared in the **manifest**.

```json
{
  "name": "Repairs GPT",
  "agent_skills": [
    {
      "folder": "./skills/repair-lookup",
      "expose_skill_to_copilot": true
    }
  ]
}
```

What the manifest controls:
- Every skill has to be declared here
- folder points at the skill directory
- expose_skill_to_copilot decides whether Copilot Chat sees it

## Tools
- **Agent Builder**: No-code solution. Create within the Copilot chat UI.
- **Microsoft 365 Agents Toolkit**: VS Code extension.
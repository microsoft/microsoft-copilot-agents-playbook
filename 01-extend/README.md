# Skill Up: Adding Skills to Your Agent in Microsoft 365 Copilot

Discover how Skills can extend Declarative Agents with new capabilities, actions, and knowledge tailored to your business scenarios. 

[![Episode 1 video](images/yt-thumb-01.png)](https://...)

📅 Video will be available after **August 18, 2026** 

## 👁️ Overview - What are Skills?

Skills are modular, reusable packages of instructions and resources that give agents specialized domain expertise and repeatable workflows. Agents dynamically load Skills only when needed so you can save some tokens!
A Skill is just a folder containing a SKILL.md file (instructions in plain markdown, with YAML metadata up top) plus optional scripts, templates, or reference files.

### Skills in Microsoft 365

In the world of M365, Skills as one of the capabilities of Declarative Agents.
A Declarative Agent can have one or more Skills, and each Skill can contain instructions, scripts, references, and assets. 
Skills are:

- Progressive Disclosure - Only minimal metadata (YAML) is loaded initially. Full instructions (in skill.md) load later. If the instructions reference other files (a script, a template, a reference doc), those get pulled in only when actually needed, not preloaded.
- Reusable workflow packaging - Skills become reusable building blocks. 
- Executable code - Skills can contain scripts and automation


### What are Declarative Agents? - Quick summary

- Declarative Agent is essentially a specialized version of Microsoft 365 Copilot that uses M365 Copilot as its brain (model) and orchestrator. It inherits Microsoft 365 compliance, RAI, and security standards.
- Great when you don't need complex multi-agent workflows, or autonomous behavior, and want to ship fast.
- Agent components are:
  - Instructions - Agent personality and behavior
  - Knowledge - What agent knows
  - Actions/MCP - What agent can call
  - Skills - How agent performs specialized workflows

### What can you do with Skills? - Use-cases

- Convert docs to markdown
- Format content nicely
- Create branded deck or letterhead

## 🤿 Deep Dive

- [More with Skills in Declarative Agents]()

### Demos & Code samples

- Fun demo: [Kitty-Explain Skill](kitty-explain-demo/README.md)
- Practical demo: [TBD]()

## 🔗 Learn More

- 📖 [Declarative Agents Overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/overview-declarative-agent)
- 📖 [Create Skills for Declarative Agents](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/...) - TBD
- 🧪 [Copilot Developer Camp - Build Declarative Agent](https://microsoft.github.io/copilot-camp/pages/extend-m365-copilot/)
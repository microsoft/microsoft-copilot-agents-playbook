# 🐱 Skill example: Kitty Explain

**Kitty Explain** is a skill that generates a "Kitty Explain" meme-style cat visual explainer for summarized content. 

![Kitty explain](../images/screenshot-skill.png)

## 💎 Demo:
[📺 Watch the demo on YouTube](https://youtu.be/173fx_0X7gg)

Skills are reusable packages of instructions and resources. So, **Kitty Explain** skill can be used with any agents too, especially it works well with agents that summarize some content from uploaded documents, URLs of articles, or concepts. 

In this demo, the skill is used in two different agents, SimpleLearn agent, which knows everything from Microsoft Learn docs (built using **M365 Agents Toolkit**), and Explain-me agent, which can summerize and explain a given content (built using **Agent Builder**).

![skill](../images/skill.png)

**kitty-explain** skill contains a `SKILL.md` file (instructions in plain markdown, with YAML metadata up top) plus reference folder with cat meme images to be references.

```bash
📂 kitty-explain
    ├── 📄 SKILL.md
    └── 📂 references
      ├── 📄 kitty01.png
      ├── 📄 kitty02.png
      └── 📄 ...
```


## 💪 How to use the skill in an agent

Basically, you can just dump this folder into your agent!

- 📂 [kitty-explain](kitty-explain/)

### 🎨 Add Skill to an agent built with Agent Builder (No-Code)

Fisrt, compress the entire `kitty-explain` folder that include SKILL.md and references to create `kitty-explain.zip`.

1. Go to https://m365.cloud.microsoft/ and from the left menu, click **Agents** and create a new agent.
1. Create a simple agent that summarizes a given content. Or start with a template. Choose **Document Summary** or **Expert Answers**.
1. Add (or modify) an instruction. Then, include a "Use skill" instruction. (See below)
1. Add a sample prompt under **Suggested prompts**: Title: "Kitty Explain visual" and Message should be something similar to "Explain [concept] by cats.". Make this fit to what the agent does.
1. Under **Skills**, upload a zipped **kitty-explain** skill.
1. Voilà!

![Add skill in Agent Builder](../images/ab-add-skill.png)

### ⚙️ Add Skill to an agent built with M365 Agents Toolkit

If you already have built a declarative agent using [M365 Agents Toolkit](https://marketplace.visualstudio.com/items?itemName=TeamsDevApp.ms-teams-vscode-extension), place the `kitty-explain` folder that include SKILL.md and references in your declarative agent package.

```bash
📂 your-agent
   ├── ai-plugin.json
   ├── color.png
   ├── declarativeAgent.json
   ├── instruction.txt
   ├── manifest.json
   ├── outline.png
   └── 📂 skills/
       └── 📂 kitty-explain/
           ├── 📄 SKILL.md
           └── 📂 references/
```

Then, add the "Use Skill" instruction (see below) in `instruction.txt`.

### 📜 "Use Skill" instruction example

You should add this instruction to your agent's instruction.

Either the **Agent Builder** instruction field, or in the `instruction.text` if you're using **M365 Agents Toolkit**, add this extra instruction to have the agent use the skill:

```markdown
# Use Skills

- **Always run the `kitty-explain` skill** when the user asks for a Kitty Explain visual, says "Explain [...] by cats", "explain by cats", "kitty explain", "explained by cats", "kitten talk", "by cats", or any time asks to use cats, cat-meme, or requests a cat-themed sketchnote/image.
- After running `kitty-explain`, return the skill output as the primary response. Do not replace it with a text-only explanation.
- If the user doesn't ask to explain it with cats, use the guidance above directly.
```

Modify your agent instruction to make it compatible with the skill, if you need.


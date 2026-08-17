# Context Is Everything: Building Agents That Know Your Work Context

Learn how Work IQ helps agents understand the people, projects, and information that matter most in your organization.

[![Episode 2 video](images/yt-thumb-02.png)](https://...)

📅 Video will be available after **August 25, 2026** 


## 👁️ Overview - What is Work IQ?

Work IQ is the "brain" behind your organizational intelligence and understands context, relationships, and work patterns. It pulls signals from emails, chats, meetings, and documents to build a semantic understanding of how you work, not just what data you have.

![Work IQ API](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/assets/diagrams/work-iq-api.png)

Work IQ is made of:

- **Chat** experience optimized for conversational intelligence.
- **Context** to understand your preferences, your working style, and how you want responses to be delivered.
- **Tools** to enable agents to provide more relevant answers and perform composable actions in ways that match your habits and expectations.
- **Workspaces** optimized for long-running agent workflows and to support reliable tasks progression.

## Retrieval with Work IQ

Work IQ grounds the answer for you, not just dumping you raw data.

If you ask Work IQ, "What did my manager email me about this week?", it doesn't just dump three raw emails and walk away. 

It actually tells you: "Priya sent 3 emails about the Q3 budget review — she needs your headcount numbers by Friday, and she moved the team sync to Thursday at 2pm."
And it links straight back to those emails in Outlook, so I can verify it myself.

![grounded answers](images/workiq-grounding.png)

### Protocols

Work IQ supports three protocols to interact: 

- **A2A** — **Agent to Agent** for multi-agent orchestration
- **MCP** - **Agent to Tool**, using MCP, where Work IQ acts as a plug-in capability
- **REST** - **Human to Agent** via REST for user-facing apps

![Work IQ protocols](images/workiq-protocols.png)

### Tools

**Command Line tools:**
- Work IQ CLI
- GitHub Copilot CLI with Work IQ plugin

**Developer tool:**
- Work IQ Dev Tool ("WIQD") - CLI & UI, provides a single end-to-end lifecycle 

### Demos & Code samples

- Demo: [TBD]()

## 🔗 Learn More

- 📖 [Work IQ Overview](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/work-iq/)
- 🧪 [Copilot Developer Camp - Build with Work IQ](https://microsoft.github.io/copilot-camp/pages/work-iq/)
- 💻 [Work IQ samples](https://github.com/microsoft/work-iq-samples)
- ⚙️ [Work IQ Dev Tool Docs](https://microsoft.github.io/wiqd/)
- 🍳 [Work IQ Cookbook](https://aka.ms/wiqd/cookbooks)


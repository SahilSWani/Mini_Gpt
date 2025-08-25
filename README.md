# 🚀 Mini-GPT Agent

An intelligent conversational agent built using **LangChain**, **OpenAI**, and **Anthropic** models.  
It can handle structured prompts, execute tools, and automate workflows for intelligent task assistance.  

---

## ✨ Features
- 🔹 **Multi-Model Integration** – Combines OpenAI & Anthropic LLMs for enhanced reasoning.  
- 🔹 **Structured Output Handling** – Uses `ChatPromptTemplate` + `PydanticOutputParser` for reliable responses.  
- 🔹 **Tool Calling Agent** – Integrated tools (Search, Wiki, Save) with `AgentExecutor` for task automation.  
- 🔹 **Extensible Design** – Easy to plug in new APIs/tools for domain-specific tasks.  

---

## 🛠️ Tech Stack
- 🐍 Python  
- 🔗 LangChain  
- 🤖 OpenAI API  
- 🧠 Anthropic API  
- 📝 Pydantic  

---

## 📂 Project Breakdown
- ⚙️ **Core Agent** – Built using `create_tool_calling_agent`.  
- 🧩 **Prompt Engineering** – Designed structured prompts for predictable outputs.  
- 🗂️ **Tools Integration** – Added search, wiki, and storage tools.  
- 🤖 **Agent Execution** – Automated workflow using `AgentExecutor`.  

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/minigpt-agent.git
cd minigpt-agent

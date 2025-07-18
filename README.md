# AI-Agent-For-Research

This project is an intelligent research assistant built using LangChain, OpenAI's GPT-4o, and Wikipedia search tools. It takes a user's query and returns a structured research summary with key points, sources, and the tools used.

---

## 📦 Features

- Uses **OpenAI's GPT-4o** to generate structured research responses
- Integrates with tools like **Wikipedia Search** for up-to-date information
- Outputs a Pydantic-validated structured summary including:
  - Topic
  - Summary
  - Sources
  - Tools used
- Modular architecture for adding more tools easily (e.g., Google Search)
- Saves research to disk (if configured with save tool)

---

## 🛠️ Tech Stack

- [LangChain](https://www.langchain.com/)
- [OpenAI GPT-4o](https://platform.openai.com/)
- [Wikipedia Tool](https://python.langchain.com/docs/integrations/tools/wikipedia)
- `pydantic`, `dotenv`, `langchain_openai`, `langchain_community`, `langchain_core`, etc.

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/AI-Agent-For-Research.git
cd AI-Agent-For-Research

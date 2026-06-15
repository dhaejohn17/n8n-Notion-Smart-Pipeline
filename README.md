# n8n-Notion-Smart-Pipeline  
**Give a reminder without typing**  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

---

### 📝 Description  
An AI-powered automation workflow that parses natural language transcripts into structured tasks and dynamically schedules them into Notion using **n8n**, **Ollama**, and **Telegram bot** integration.  

---

### 🚀 Key Features  
- **Voice audio to Notion tracker**: Convert voice notes into actionable tasks automatically.  
- **AI-Powered Parsing**: Leverage LLMs via **Ollama** to extract intents and deadlines from natural language.  
- **Dynamic Scheduling**: Automatically create and update Notion databases with task timelines.  
- **Telegram Bot Integration**: Trigger workflows via voice or text commands in Telegram.  

---

### 🛠️ Tech Stack  
- **n8n** – Workflow automation engine  
- **Notion** – Task and project tracking  
- **Ollama** – Local LLM inference (e.g., Llama, Mistral)  
- **Telegram Bot** – Voice/text command interface  
- **NLP/LLM** – Natural language understanding and task extraction  

---

### 🛠️ Getting Started  

#### 1. **Clone the Repository**  
```bash  
git clone https://github.com/dhaejohn17/n8n-notion-smart-pipeline.git  
```  

#### 2. **Set Up Environment**  
- Install [n8n](https://n8n.io/) and configure the workflow using `workflow.json`.  
- Set up [Ollama](https://ollama.ai/) for local LLM inference.  
- Configure Notion API credentials and Telegram bot tokens in environment variables.  

#### 3. **Run the Workflow**  
Start n8n and trigger the workflow via Telegram voice/text commands or direct API calls.  

---

### 📄 License  
This project is licensed under the **MIT License** – see [LICENSE](LICENSE) for details.
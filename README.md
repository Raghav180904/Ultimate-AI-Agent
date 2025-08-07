# 🧠 AI-Powered Personal Assistant using n8n + GPT-4o

This project is a modular personal assistant built using [n8n](https://n8n.io), OpenAI GPT-4o, and other automation tools. It uses a team of AI agents to handle tasks like sending emails, retrieving contacts, and performing web searches — all triggered from a Telegram message.

---

## 🔧 Tech Stack

- **n8n** – Automation workflows
- **OpenAI GPT-4o** – Language understanding
- **Telegram** – Chat interface
- **Airtable** – Contact database
- **Gmail API** – Email automation
- **Tavily API** – Web search
- **OBS Studio** – Screen recording
- **Premiere Pro** – Video editing

---

## 📦 Workflow Architecture
User (Telegram)
↓
Switch Node (Text / Voice)
↓
Ultimate Assistant (Main AI Agent)
↓
┌────────────┬────────────┬────────────┐
↓ ↓ ↓ ↓
Email Agent Contact Agent Calendar Agent Web Search (Tavily)
↓
Response → Telegram

---

## 🚀 How It Works

1. Telegram message triggers the workflow.
2. Voice inputs are transcribed.
3. Message is processed by the "Ultimate Assistant" node.
4. Based on the task, it routes to the correct agent:
   - Contact lookup
   - Email generation
   - Calendar access
   - Web search
5. Response is generated and sent back to the user.

---

## 📁 Workflows Included

- `Ai Assistant.json`
- `Contact Agent.json`
- `Email Agent.json`

Import these into n8n to get started.

---

## 🧩 Challenges Faced

- Agent loops in n8n (solved with Switch + max iteration)
- Audio issues while recording
- OBS display fix (black screen)
- Video compression + scaling for LinkedIn

---

## 🙏 Credits

Mentor: [Paramveer Nandal](#)  
Summer School: **IIT Jammu – July 2025**

---

## 📝 License

MIT License



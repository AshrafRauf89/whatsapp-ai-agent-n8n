# 🤖 WhatsApp AI Automation Agent (n8n)

**Enterprise-grade AI agent for WhatsApp** built with **n8n**, **OpenAI GPT**, and **RAG (Retrieval-Augmented Generation)**.  
This project automates business conversations, customer support, lead generation, and scheduling workflows — all inside WhatsApp.

---

## 🧠 Core Features

### 🤖 AI Conversational Engine
- Natural language understanding (text, voice-to-text)
- Context-aware responses
- Support for images and links

### 🔄 Workflow Automation
- Built using **n8n visual workflow builder**
- Connects to APIs and webhooks
- Integrates with multiple services

### 📚 RAG Knowledge System
- Stores documents in a vector database
- Retrieves answers based on real data (PDFs, docs)
- Smart context answering with embeddings

### 📅 Business Integrations
- Google Calendar scheduling
- Email notifications
- CRM and lead automation

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| Orchestration | n8n |
| AI | OpenAI GPT (API) |
| RAG | Pinecone or FAISS |
| Messaging | WhatsApp API / Evolution API |
| Backend | Python (if needed) |
| Deployment | Docker / Cloud |

---

## 🏗 Architecture Overview
WhatsApp User
│
▼
WhatsApp Cloud API
│
▼
n8n Orchestrator
│
├── AI Agent (OpenAI)
├── RAG Pipeline
├── Scheduler & Calendar Agent
├── CRM & Lead Capture
└── Alerts & Notifications


---

## 🚀 Use Cases

✔️ Customer support bot  
✔️ Lead qualification & capture  
✔️ Appointment scheduling  
✔️ Knowledge-base response system  
✔️ Multilingual support

---

## 📦 Getting Started

### Prerequisites
1. Node.js & Docker  
2. n8n (self-hosted or cloud)  
3. WhatsApp API credentials  
4. OpenAI API key  
5. Vector Database (Pinecone/FAISS)

### Install & Run
```bash
git clone https://github.com/AshrafRauf89/whatsapp-ai-agent-n8n.git
cd whatsapp-ai-agent-n8n
Import Workflows

Open n8n

Go to Workflows → Import

Select JSON files

🧠 How It Works

User sends message on WhatsApp

n8n webhook receives it

Message is passed to AI agent

RAG system fetches relevant context

Response sent back to user

📫 Contact & Connect

👤 Ashraf Rauf
📧 Email: ashrafrauf.icdl@yahoo.com

🔗 GitHub: https://github.com/AshrafRauf89

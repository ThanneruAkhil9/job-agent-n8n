# 🤖 AI Job Agent

An automated AI agent that reads job emails daily 
and extracts company information.

## 🚀 What it does
- 📧 Reads job emails from Gmail automatically
- 🤖 Extracts company name, job title, location & salary using AI
- 📊 Saves results to Google Sheets
- 📱 Sends Telegram notifications daily

## 🛠️ Tools Used
- **n8n** - Workflow automation
- **Groq AI** - Free LLM (llama-3.3-70b)
- **Gmail API** - Read emails
- **Google Sheets** - Store results
- **Telegram Bot** - Notifications
- **Railway** - Cloud hosting 24/7

## ⚙️ How it works
1. Schedule Trigger runs every day
2. Gmail node fetches latest job emails
3. Wait node handles rate limiting
4. AI Agent extracts job information
5. Results saved to Google Sheets
6. Telegram notification sent

## 🆓 Cost
Everything is completely FREE!

## 👤 Author
Akhil - Built with n8n and Groq AI# job-agent-n8n
AI Job Agent that reads emails and sends Telegram notifications

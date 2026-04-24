# 🤖 AI Job Search Automation System

Two AI agents that automatically find and filter 
AI/ML jobs and send notifications daily!

## 🚀 Agent 1 — Email Job Reader
- 📧 Reads LinkedIn/Naukri job alert emails
- 🤖 Extracts company info using AI
- 📊 Saves to Google Sheets
- 📱 Sends Telegram notifications daily

## 🚀 Agent 2 — AI Job Finder
- 🔍 Searches Google for AI/ML jobs using SerpAPI
- 🤖 Scores each job out of 100 using Groq AI
- ✅ Filters only 80+ match score jobs
- 📊 Saves to Google Sheets
- 📱 Sends Telegram notifications

## 🛠️ Tools Used
- **n8n** - Workflow automation
- **Groq AI** - Free LLM (llama-3.3-70b)
- **SerpAPI** - Google Jobs search
- **Gmail API** - Read emails
- **Google Sheets** - Store results
- **Telegram Bot** - Notifications
- **Railway** - Cloud hosting 24/7

## ⚙️ How Agent 2 Works
1. Schedule Trigger runs every 3 days
2. SerpAPI fetches real AI/ML jobs from Google
3. Code node extracts job details
4. AI Agent scores each job out of 100
5. IF node filters only 80+ score jobs
6. Results saved to Google Sheets
7. Telegram notification sent

## 🆓 Cost
Everything is completely FREE!

## 👤 Author
Akhil - Built with n8n, Groq AI and SerpAPIeads emails and sends Telegram notifications

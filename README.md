# ainewsdigest 
AI-driven news assistant that delivers personalized, clutter-free news summaries straight to your inbox.

URL to test the feature: https://github.com/iamtusharchopra/ainewsdigest

Overview

This project transforms how you consume news.

Instead of scrolling through multiple sources, simply provide:

📝 A topic of interest 📧 Your email ID

…and receive a curated news digest within seconds.

✨ Features 🔍 Topic-Based News Retrieval Fetches the most relevant and recent articles based on your query.

🧠 AI-Powered Summarization Each article is condensed into a 5-point crisp summary for quick consumption.

📰 Clean & Structured Output Clear headlines Direct source links

⚡ Fast & Efficient Designed for near real-time delivery.

📬 Email Delivery Automatically sends a well-formatted digest to your inbox.

🏗️ Tech Stack Workflow Automation: n8n (Self-hosted)

Containerization: Docker
AI Model: Gemini 2.5 Flash (for fast summarization)
News Source API: NewsData.io (strong coverage, especially for Indian news)
Cloudfare Tunnel: Cloudflare Tunnel is used to securely expose my self-hosted n8n webhooks to the internet.

🔧 How It Works:
1. User inputs a news topic + email ID
2. n8n workflow triggers: Fetches articles via NewsData.io API and Processes content using Gemini AI
3. AI generates: Concise summaries and Structured output
4. Final digest is sent via email

💡 Use Cases:
📊 Busy professionals who want quick news insights 
📈 Traders & investors tracking specific sectors/themes 
🧠 Anyone seeking distraction-free news consumption

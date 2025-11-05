# RSS to Gmail Automation — n8n Workflow

This workflow automates reading RSS feed articles, summarizing them using Google Gemini (LLM), and sending the summarized content via Gmail.

## 🧩 Workflow Overview
1. *Trigger* — Starts when “Execute Workflow” is clicked.  
2. *RSS Read* — Fetches the latest articles from an RSS feed.  
3. *Limit* — Restricts the number of items to process.  
4. *Basic LLM Chain (Google Gemini)* — Uses Google’s Gemini model to analyze and summarize the article content.  
5. *Edit Fields* — Adjusts or formats the data before sending.  
6. *If Node* — Filters results based on defined conditions (e.g., relevance or topic).  
7. *Gmail (Send Message)* — Sends the final summarized message via email.

## 💡 Use Case
Perfect for automating daily content summaries, news monitoring, or sending curated insights directly to your inbox.

## ⚙ Tools & Integrations
- *n8n Cloud*
- *Google Gemini API*
- *Gmail API*
- *RSS Feeds*

## 📂 Files
- My workflow.json — Exported n8n workflow file  
- README.md — Documentation for the workflow

---

✨ Created with n8n and AI-powered automation.
add readme file

# 📰 AI-Powered News Summarizer & Telegram Automation

An AI-powered news summarization workflow built using **n8n**, **Google Gemini**, and **Telegram**.

The workflow automatically reads news articles from a Daily Thanthi RSS feed, uses Google Gemini to generate a short and clear summary, and sends the summarized news directly to Telegram.

---

## 🚀 Project Overview

Reading multiple news articles every day can take a lot of time.

This project automates the process by:

1. Monitoring a news RSS feed.
2. Receiving new news articles.
3. Sending the article content to an AI Agent.
4. Using Google Gemini to summarize the article.
5. Formatting the result.
6. Sending the final summary to Telegram.

### Workflow

```text
Daily Thanthi RSS Feed
        ↓
   RSS Feed Trigger
        ↓
      AI Agent
        ↓
 Google Gemini Model
        ↓
    Edit Fields
        ↓
 Send Telegram Message

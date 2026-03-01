# 📧 Email-Summarizer AI Agent

An intelligent automation agent that monitors your inbox and transforms cluttered email threads into concise, actionable summaries using Large Language Models (LLMs).

## 🚀 The Problem
Modern professionals receive dozens of emails daily, leading to "inbox fatigue." Most of these messages contain "fluff" like signatures, legal disclaimers, and thread history that make it difficult to find the core message.

## ✨ Key Features
* **Automated Triage:** Connects to any IMAP-enabled provider to pull unread messages automatically.
* **Smart Parsing:** Strips HTML, CSS, and email signatures to feed only relevant text to the AI.
* **Abstractive Summarization:** Uses Gemini/GPT to generate a 3-bullet-point summary of the message.
* **Task Identification:** Automatically identifies "Action Items" (e.g., deadlines, meeting requests).
* **Low-Code Logic:** Built with a modular `.json` workflow architecture for easy deployment.

## 🛠️ Tech Stack
* **Core:** Python, JSON
* **AI Engine:** Google Gemini 1.5 Flash / OpenAI GPT-4
* **Automation:** Integration-ready workflow (Merge/n8n)
* **Protocols:** IMAP / SMTP for secure mailbox access

## 📂 Project Structure
* `Email Summarizer Using Merge.json`: The core logic and API integration mapping.
* `README.md`: Project documentation and setup guide.
* `Preview.png`: Visual demonstration of the summary output.

## ⚙️ Setup Instructions
1. **Clone:** `git clone https://github.com/swathi-0611/Email-Summarizer1`
2. **Configure:** Add your AI API Key to the environment variables.
3. **Connect:** Use an "App Password" (for Gmail) to authenticate the IMAP node.
4. **Run:** Import the JSON workflow into your automation tool or run the Python wrapper.

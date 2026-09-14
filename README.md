# HIRElink AI - Automated Recruitment & Applicant Screening System

An end-to-end automated HR and recruitment pipeline built with **n8n**, **Google Gemini AI**, **Telegram Bot API**, and **Google Sheets**. The system streamlines applicant processing, resume analysis, and dynamic candidate notification.

## 🚀 Key Features

- **Automated Telegram Bot Interaction:** Receives candidate data and triggers the screening pipeline via Telegram interface.
- **AI-Powered Candidate Analysis:** Utilizes Google Gemini LLM via AI Agent nodes to evaluate CVs, match job descriptions, and extract candidate info.
- **Google Sheets Integration:** Automatically fetches, records, and updates applicant statuses in real-time.
- **Interactive HR Notifications:** Sends direct automated reports and recommendations to HR managers.

## 🛠️ Tech Stack & Tools

- **Workflow Automation:** n8n
- **AI/LLM Engine:** Google Gemini (via LangChain / AI Agent Nodes)
- **Integrations:** Telegram Bot API, Google Sheets API
- **Data Handling:** JSON, JavaScript Data Transformation

## 📋 How to Import & Setup

1. **Download Workflow:** Clone this repository or download the JSON workflow file from this repository.
2. **Import to n8n:** Open your n8n instance -> **Workflows** -> **Import from File**.
3. **Configure Credentials:**
   - Add your **Telegram Bot Token**.
   - Add your **Google Gemini API Key**.
   - Connect your **Google Sheets Account**.
4. **Activate:** Set the workflow to `Active` and test via your Telegram Bot.

# 🧾 Expentra

**Effortless expense tracking from receipt to spreadsheet.**  
Automate your expense logging by sending receipt images via Telegram — powered by n8n, DeepSeek AI, and Google Sheets.

---

## 🚀 Overview

Expentra is a lightweight automation flow that lets users track their expenses by simply uploading receipt photos to a Telegram bot. The system uses OCR and AI (via DeepSeek on Hugging Face) to extract relevant data and log it automatically into a connected Google Spreadsheet.

### ✨ Features

- Upload receipt images via Telegram
- AI-powered data extraction (DeepSeek AI)
- Google Sheets integration for structured expense tracking
- Seamless automation using n8n
- No manual data entry required

---

## 🛠️ Tech Stack

- **Telegram Bot** – User-friendly interface for uploading receipt images
- **n8n** – Workflow automation engine connecting all components
- **DeepSeek AI** – Receipt OCR and data understanding (via Hugging Face)
- **Google Spreadsheet** – Destination for structured expense logging

---

## 🔧 How It Works

1. **User sends a receipt image** via a Telegram bot.
2. **n8n receives the image** and passes it to DeepSeek AI for processing.
3. **DeepSeek AI extracts** key data (e.g., date, total, merchant, items).
4. **n8n formats and logs** the data into a specified Google Spreadsheet.

---

## 📦 Prerequisites

To run your own version, you’ll need:

- A Telegram bot token (via [BotFather](https://t.me/BotFather))
- A running instance of [n8n](https://n8n.io/)
- A Hugging Face account & API token (for DeepSeek AI)
- Access to Google Sheets API (with credentials)

---

## 📂 Project Structure

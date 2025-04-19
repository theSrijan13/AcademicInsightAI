# 📄 TranscriptIQ

**TranscriptIQ** is an AI-powered web app that extracts and analyzes academic transcript data from PDF files using [Claude (Anthropic)](https://www.anthropic.com/index/claude) and displays the information in a structured format via Streamlit. It also stores the parsed results and user feedback in **Google Drive** and **Google Sheets** for easy access and review.

---

## 🚀 Features

- 🔐 **Password-protected access**
- 📤 **PDF upload and parsing**
- 🧠 **Claude 3 Sonnet integration for data extraction**
- 🧾 **Extracts term-wise course info (credits, grades, GPA points, etc.)**
- 📊 **Displays extracted data in interactive tables**
- 💬 **User feedback form after transcript analysis**
- ☁️ **Uploads PDF to Google Drive**
- 📋 **Logs feedback and results in Google Sheets**
- 🧮 **Calculates missing credits based on GPA points and grades**

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/)
- [Anthropic Claude 3 API](https://docs.anthropic.com/)
- [Google Drive API](https://developers.google.com/drive)
- [Google Sheets API via GSpread](https://gspread.readthedocs.io/)
- [Python](https://www.python.org/)

---

## 📦 Installation

```bash
git clone https://github.com/your-username/TranscriptIQ.git
cd TranscriptIQ
pip install -r requirements.txt

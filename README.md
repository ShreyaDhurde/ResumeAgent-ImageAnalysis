# ResumeAgent + Image analysis agent 💼🤖

ResumeAgent-GIGA is an AI-powered resume analyzer built using **Python**, **Streamlit**, and **Google Gemini API**. This intelligent assistant helps you align your resume with a given job description by highlighting skill gaps, suggesting improvements, and enabling Q&A-style feedback.

---

## ✨ Features

- 📄 Upload your **resume** (PDF/DOCX) and **job description**.
- 💡 Get **skill gap analysis** and suggestions based on AI insights.
- 💬 Chat-based Q&A to ask personalized resume improvement questions.
- 🔎 Supports multi-turn conversations and feedback refinement.
- 🧠 Powered by **Google Gemini** for natural language understanding.

---

## 📦 Tech Stack

- Python 3.10+
- Streamlit
- Google Gemini API (via `google.generativeai`)
- `python-docx`, `PyMuPDF` for parsing documents

---

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/ShreyaDhurde/ResumeAgent-ImageAnalysis.git
cd ResumeAgent-GIGA


## 2. Set Up the Environment

**Install the required Python packages:**

```bash
pip install -r requirements.txt
```

If `requirements.txt` is missing, install the following manually:

```bash
pip install streamlit python-docx PyMuPDF google-generativeai python-dotenv
```

## 3. Add Google API Key

Create a `.env` file in the root directory of the project and paste your Gemini API key like this:

```env
GOOGLE_API_KEY="YOUR_API_KEY_HERE"
```

🔑 You can generate your API key at [Google AI Studio](https://aistudio.google.com/app/apikey).

⚠️ **Make sure not to commit your `.env` file to version control.**

## 4. Run the Streamlit App

Start the app by running:

```bash
streamlit run imgamz.py
```

A browser window will open with the ResumeAgent-GIGA interface.

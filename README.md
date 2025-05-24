# 🧠 AI-Powered Job Recommender

This is an interactive Streamlit application that uses **Google Gemini (Generative AI)** to analyze a user's resume and selected skills, and then suggests **3 personalized job titles** along with relevant upskilling recommendations.

---

## 🚀 Features

- Upload your **resume (PDF or DOCX)**
- Select your **skills** from categorized lists (e.g., Programming, Data Science, Cloud, etc.)
- Securely input your **Gemini API key** (from Google AI Studio)
- Get **3 AI-recommended job titles**, each with:
  - A markdown-formatted job block
  - Bullet points for skills/tools to learn
- Powered by **Gemini 1.5 Pro** from Google

---

## 🧰 Tech Stack

- [Streamlit](https://streamlit.io/)
- [Google Gemini API](https://makersuite.google.com/app/apikey)
- [PyMuPDF](https://pymupdf.readthedocs.io/en/latest/) for PDF parsing
- [python-docx](https://python-docx.readthedocs.io/en/latest/) for DOCX parsing
- Python standard libraries

---

## 📄 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-job-recommender.git
cd ai-job-recommender
```
### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Run the Streamlit app

```bash
streamlit run app.py
```

## 🔐 Gemini API KEY

To use the app, you need a Gemini API key from Google.
Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
Sign in and create an API key
Paste the key in the sidebar of the app




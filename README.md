
# ⚡️ Universal Code Translator & Enhancer

Convert code between programming languages or improve its readability — instantly, intelligently.\
Powered by Google Gemini + LangChain, wrapped in a simple Streamlit UI.

🔗 **Live Demo**: [(universal-code-translator-Link)](https://universal-code-translator.onrender.com) \
**Note**: This was deployed on Render (Free Tier). So, it takes 40 sec to load

---

## ✨ Features

- 🔄 Translate code across multiple languages  
- 🧼 Improve code readability and structure  
- 🤖 AI-powered with Gemini 2.0 Flash  
- 🧪 Supports: Python, C++, JavaScript, Go, Rust, and more

---

## 🚀 Getting Started

### 1. Clone this repo

```bash
git clone https://github.com/your-username/code-modernization.git
cd code-modernization
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Set up environment

Create a `.env` file with your [Google API Key](https://aistudio.google.com/app/apikey):

```
GOOGLE_API_KEY=your_key_here
```

### 4. Run the app

```bash
streamlit run app.py
```

---

## 🧠 How It Works

* **LLM**: Gemini 2.0 Flash (via LangChain)
* **Classification**: Determines if input is code or text
* **Conversion Mode**: Translates between selected languages
* **Enhancement Mode**: If input/output language is the same, code is enhanced for clarity

---

## 💼 Tech Stack

* [Streamlit](https://streamlit.io/) – UI Framework
* [LangChain](https://www.langchain.com/) – Prompt pipelines
* [Google Generative AI](https://ai.google.dev/) – LLM backbone
* [Render](https://render.com/) – Free-tier deployment

---

## 📄 Files

* `app.py` – Main application logic and UI
* `requirements.txt` – Python dependencies

---

## 📬 Feedback

Open an issue or submit a PR — contributions welcome!

---

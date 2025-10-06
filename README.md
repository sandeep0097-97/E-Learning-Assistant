# 🎓 E-Learning Assistant — Streamlit App

An AI-powered learning assistant that helps students:
- Upload study materials (PDF/DOCX/TXT)
- Ask questions and get personalized explanations
- Generate quizzes automatically
- Track learning progress and notes

---

## 🚀 Demo
Deployed on **Streamlit Cloud:**  
👉 [https://your-username-elearning-assistant-app.streamlit.app](https://your-username-elearning-assistant-app.streamlit.app)

---

## 🧰 Features
✅ PDF / DOCX / TXT uploads  
✅ Vector-based retrieval (OpenAI embeddings or SBERT)  
✅ Chat-based Q&A using OpenAI models  
✅ Quiz generator (MCQs with explanations)  
✅ Local progress + notes tracking  
✅ Streamlit sidebar for model & settings

---

## 🛠️ Setup

### 1️⃣ Clone this repo
```bash
git clone https://github.com/<your-username>/elearning-assistant-app.git
cd elearning-assistant-app
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ (Optional) Set your OpenAI API key
Create a file `.streamlit/secrets.toml`:
```toml
OPENAI_API_KEY = "sk-your-api-key"
```

### 4️⃣ Run locally
```bash
streamlit run streamlit_elearning_assistant.py
```

Then open your browser at `http://localhost:8501`

---

## ☁️ Deploy on Streamlit Cloud
1. Push this folder to GitHub  
2. Visit [https://share.streamlit.io](https://share.streamlit.io)  
3. Click **“New App”**, select your repo & `streamlit_elearning_assistant.py`  
4. Set secrets (`OPENAI_API_KEY`) under **Settings → Edit Secrets**  
5. Click **Deploy** 🎉

---

## ⚙️ Optional Enhancements
- Add database (SQLite/PostgreSQL) for cloud persistence  
- Add Google OAuth for student login  
- Integrate progress charts using `plotly` or `matplotlib`  
- Deploy on Hugging Face Spaces for free GPU-backed hosting

---

**Built with ❤️ by [Your Name]**

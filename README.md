# 🚀 AI_Recruitment

An AI-powered recruitment and mock interview system built using **LLM + RAG (Retrieval-Augmented Generation)**.
It generates **resume-based interview questions**, evaluates answers, and provides structured feedback to help users prepare for real-world interviews.

---

## ✨ Features

* 📄 Resume Upload (PDF/DOCX)
* 🧠 Personalized Question Generation (based on resume)
* 🔍 RAG-based Context Retrieval
* 🎯 Technical & HR Interview Modes
* 📊 AI-based Answer Evaluation
* 🔄 Dynamic Follow-up Questions
* 📈 Final Score with Feedback

---

## 🏗️ Workflow

```
Resume Upload → Text Extraction → Chunking & Embedding → Local Vector DB
→ User Input (Role, Difficulty, Type)
→ RAG + LLM → Question Generation
→ User Answer → AI Evaluation
→ Next Question / Final Report
```

---

## 🧠 How It Works

**1. Resume Processing**
Extracts and converts resume data into embeddings stored in a vector database.

**2. Question Generation**
Uses RAG + LLM to generate questions based on skills, projects, and experience.

**3. Answer Evaluation**
Analyzes responses based on correctness, clarity, and depth.

**4. Adaptive Flow**
Dynamically adjusts questions based on previous answers.

---

## ⚙️ Tech Stack

**Frontend:** HTML, CSS, JavaScript
**Backend:** FastAPI, Python
**AI / RAG:** OpenAI / Gemini, LangChain, Local Vector DB

---

## 🚀 Installation

```bash
git clone https://github.com/sagartripathi027/AI_Recruitment.git
cd AI_Recruitment

python -m venv venv
venv\Scripts\activate   # Windows

pip install -r requirements.txt
uvicorn main:app --reload
```

---

## 📂 Project Structure

```
AI_Recruitment/
│
├── backend/
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── uploads/
├── vector_db/
├── requirements.txt
└── README.md
```

---

## 📊 Sample Output

```
Score: 8/10

Strengths:
- Strong fundamentals
- Clear explanation

Weaknesses:
- Lacks real-world examples

Suggestions:
- Improve communication
- Add practical examples
```

---

## 🔮 Future Improvements

* 🎙️ Voice-based interviews
* 🤖 AI avatar interviewer
* 📈 Performance dashboard
* 🌐 Multi-language support

---

## 👨‍💻 Authors

**Sagar Tripathi**
GitHub: https://github.com/sagartripathi027

**Pragati Mishra**
GitHub: https://github.com/Pragati-cloud

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

## ⚡ Note

This project focuses on **core AI logic (RAG + evaluation system)** rather than just UI, making it practical for real-world interview preparation.

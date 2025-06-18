# 📚 StudyBuddy AI – Personalized Learning Assistant (In Progress)

StudyBuddy AI is an intelligent study assistant that helps students convert their notes, textbooks, or handwritten content into **adaptive quizzes**, **flashcards**, and a **custom study schedule** based on their strengths and weaknesses.

---

## 🎯 Features

- ✅ **Smart Content Extraction**: Upload PDFs or handwritten notes and extract text using OCR.
- 🧠 **AI-Powered Question Generation**: Automatically generate multiple choice questions, fill-in-the-blank, and flashcards using Hugging Face NLP models.
- 📈 **Adaptive Quizzing**: Focuses more on the concepts you get wrong to reinforce weak topics.
- 📊 **Progress Dashboard**: Visualize your mastery levels by topic and track your learning journey.
- ⏰ **Study Reminders**: Get spaced repetition notifications based on your performance and review needs.

---

## ⚙️ Tech Stack

| Layer        | Technology |
|--------------|------------|
| **Frontend** | React, Tailwind CSS |
| **Backend**  | FastAPI (Python), Uvicorn |
| **AI Models**| Hugging Face Transformers (T5/BART), OCR (Tesseract or Donut) |
| **Database** | SQLite (MVP), PostgreSQL (optional for scaling) |
| **Storage**  | Local or Firebase/S3 |
| **Deployment**| Docker, Render (backend), Vercel (frontend) |

---

## 🚀 Getting Started

### 📁 Clone the Repository
```bash
git clone https://github.com/ADJG6183/StudyBuddyAI.git
cd studybuddy-ai

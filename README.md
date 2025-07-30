# 🎬 AI Entertainment Hub 🎶

An AI-powered web application that recommends personalized movies and music to users based on their preferences, ratings, and mood. It integrates machine learning, collaborative filtering, and APIs like Spotify and MovieLens to deliver a seamless entertainment experience.

---

## 📌 Features

- 🔐 User Authentication (JWT-based)
- 🎥 Movie Recommendations (MovieLens Dataset)
- 🎵 Music Recommendations (Spotify API)
- ⭐ Content Rating System
- 📊 Personalized Dashboard
- 🧠 AI-powered Collaborative Filtering
- 🌍 Deployed on Render & Vercel

---

## 🏗️ Tech Stack

| Frontend      | Backend       | AI/ML              | Database       |
|---------------|----------------|---------------------|----------------|
| React (Vite)  | Flask (Python) | Surprise, scikit-learn | MongoDB Atlas  |

---

## 🗂️ Folder Structure

ai-entertainment-hub/
├── backend/
│ ├── app.py
│ ├── routes/
│ ├── recommender/
│ ├── models/
│ └── utils/
├── frontend/
│ ├── src/
│ └── public/
├── .gitignore
├── README.md
├── requirements.txt
└── package.json

---

## ⚙️ Setup Instructions

### 🔹 Backend

(```bash)

cd backend/
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python app.py


### 🔹 Frontend

cd frontend/
npm install
npm run dev

---

🚀 Deployment

Backend: Render (Flask)

Frontend: Vercel or Netlify

Database: MongoDB Atlas

---

📚 References:
 
MovieLens Dataset

Spotify Web API

Surprise Recommender Library

---

🙏 Acknowledgments

This project is part of the 3rd-year B.Tech Software Engineering coursework, under guidance of my professor.

---

📌 License
MIT License © 2025 Arunabh Kshitij

---

## ✅ `.gitignore`

(```gitignore)

# Python
__pycache__/
*.py[cod]
*.env
venv/
*.sqlite3

# Environment variables
.env

# Flask & VS Code
instance/
*.log
.vscode/

# Jupyter Notebook
.ipynb_checkpoints/

# Node/React
node_modules/
dist/
build/
.env.local
*.lock

# OS
.DS_Store
Thumbs.db

# 🎓 EduSphere AI

AI-Powered Personalized Learning & Teacher Assistant Platform for Government and Rural Schools in Gujarat.

## 📌 Overview

EduSphere AI is a web-based educational assistant built as a **single-page application** using **HTML, CSS, and JavaScript**.

The platform uses an **LLM through the Groq API** to provide personalized learning experiences for students while assisting teachers with lesson planning, assessments, classroom support, and learning analytics.

The entire application is contained in a **single `index.html` file**.

---

## ✨ Features

### 👨‍🎓 Student Mode

- Personalized learning recommendations
- Concept explanations
- Adaptive learning support
- Quiz generation
- Homework assistance

### 👨‍🏫 Teacher Mode

- AI-generated lesson plans
- Classroom activity generation
- Worksheet creation
- Progress reports
- Assessment support

### 👨‍👩‍👧 Parent Mode

- Student progress monitoring
- Learning recommendations
- Educational guidance

---

## 🤖 AI Agents

The platform combines five educational AI agents:

### 1. Personalized Learning Recommendation Agent

- Adaptive learning
- Personalized study plans
- Learning path recommendations

### 2. Lesson Plan & Content Generation Agent

- Lesson plans
- Worksheets
- Homework
- Classroom activities

### 3. Student Performance & Learning Analytics Agent

- Learning analytics
- Weakness detection
- Student progress tracking

### 4. Automated Assessment & Feedback Agent

- Quiz generation
- Answer evaluation
- Performance feedback

### 5. Teacher Assistant & Classroom Support Agent

- Teacher assistance
- Administrative support
- Report generation

---

## 🛠️ Technology Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Groq API
- IBM Granite-compatible LLM

---

## 🖥️ User Interface

The application includes:

- Student mode
- Teacher mode
- Parent mode
- Profile customization
- Chat interface
- Quick-action toolbar
- Typing indicator
- Markdown support
- Chat export
- Responsive design

---

## 📂 Project Structure

```text
EduSphere-AI/
│
├── index.html
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/EduSphere-AI.git
```

### Open the project folder

```bash
cd EduSphere-AI
```

### Add your Groq API key

Open `index.html` and update:

```javascript
const API_KEY = "YOUR_GROQ_API_KEY";
```

### Run the application

Open `index.html` in your browser.

---

## 🚀 Future Improvements

- IBM BOB integration
- IBM Granite integration
- Voice input
- Voice output
- Student dashboard
- PDF export
- Database integration
- Authentication
- RAG support
- Offline mode

---

## 🔒 Security Notice

Do not expose your API key inside the frontend code.

Store API keys in a backend service or environment variable before deploying the application.

---

## 📜 License

This project was developed for educational and hackathon purposes.
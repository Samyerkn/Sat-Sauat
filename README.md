# 🇰🇿 Sauat — SAT Preparation Platform

### Prepare smarter. Understand deeper. Aim higher.

Sauat is an educational platform designed to make SAT preparation more accessible, structured, and personalized for students in Kazakhstan.

The platform brings exam practice, performance analytics, AI-assisted learning, and university admission information together in one place — helping students prepare more effectively and make informed decisions about their academic future.

---

## 🎯 The Problem

Preparing for university admission exams can be expensive, overwhelming, and difficult to organize.

Students often rely on scattered learning resources, separate practice websites, and costly preparation courses. As a result, they may struggle to identify knowledge gaps, track their progress, and understand their mistakes.

For students in Kazakhstan, finding preparation resources that also reflect local university admission requirements can be an additional challenge.

## 💡 Our Solution

Sauat aims to provide an integrated learning environment where students can prepare for exams, understand their performance, and plan their next steps.

The platform combines structured exam practice, personalized progress tracking, AI-assisted explanations, and information about universities in Kazakhstan.

## ✨ Key Features

- **📝 SAT-Style Mock Exams**  
  Practice with timed exams and receive automatic scoring.

- **🤖 AI-Assisted Learning**  
  Get explanations of incorrect answers and ask questions about challenging topics.

- **📊 Progress Analytics**  
  Track performance over time and identify topics that require additional practice.

- **🎯 Weak-Topic Detection**  
  Use performance data to identify knowledge gaps and guide further preparation.

- **🎓 University Information**  
  Explore universities in Kazakhstan and review admission requirements.

- **👤 Personalized Student Experience**  
  Keep student information, exam results, and learning progress organized in one place.

👥 Target Audience
- High school students preparing for SAT-style exams.
- Students in Kazakhstan exploring university admission opportunities.
- Students seeking a more structured and affordable approach to exam preparation.
🌱 Project Vision
Our goal is to make exam preparation more accessible and personalized by combining educational technology, data-driven insights, and AI-assisted learning.
Sauat is designed to support students throughout their preparation journey — from understanding their current level to identifying areas for improvement and exploring future academic opportunities.
👩‍💻 Team
Team Member	Role
Samal	Project Manager & Backend Developer
Asem	Frontend Developer
Symbat	AI/ML & Data
Amina	UI/UX Designer & QA


Sauat — a smarter path to your academic future.
## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend development |
| FastAPI | REST API |
| SQLAlchemy | Database models and ORM |
| SQLite | Local development database |
| PostgreSQL | Relational database and CI testing |
| External LLM API | AI-assisted explanations |
| Pytest | Automated testing |
| GitHub Actions | Continuous integration |

## 🏗️ Project Architecture

Sauat follows a client-server architecture.

The frontend communicates with the backend through API requests. The backend manages application logic, authentication, database operations, exam scoring, and communication with external AI services.

```text
          Student
             |
             v
          Frontend
             |
          REST API
             |
             v
       FastAPI Backend
        /     |      \
       v      v       v
   Database  Exam    AI Service
             Logic   (External API)







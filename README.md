# 💼 AI-Powered Resume Ranker

An intelligent resume screening backend app that uses OpenAI GPT API to evaluate and rank resumes based on job descriptions — helping recruiters and job seekers analyze resume–JD relevance in seconds.

---

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot 3.x**
- **PostgreSQL**
- **OpenAI GPT API**
- **React.js + Tailwind (frontend - coming soon)**
- **JWT Auth (Phase 2)**
- **Render / Railway for deployment**

---

## 📌 Features

- Upload Resume + Job Description
- AI-generated **match score** using GPT-4
- Stores results in PostgreSQL database
- Simple REST API (Spring Boot)
- Recruiter dashboard to rank resumes (coming soon)
- Deployed full-stack system (coming soon)

---

## 🚀 How It Works

1. **User uploads** their Resume and Job Description (JD)
2. Backend calls **OpenAI GPT API** with both inputs
3. GPT evaluates skills, context, and match → returns a **score**
4. Score and resume data saved to database
5. Recruiters can see ranked resumes for a specific JD

---

## 🔐 Authentication (Coming Soon)

- Signup/Login with JWT token
- Recruiter & applicant roles

---

## 📁 Folder Structure

resume-ranker-ai/
├── backend/
│ ├── src/
│ ├── pom.xml
├── frontend/ (upcoming)
├── README.md

---

## 🧪 APIs (Planned)

| Method | Route | Description |
|--------|-------|-------------|
| POST | `/api/resume/upload` | Upload resume & JD |
| GET  | `/api/resume/{id}` | Get score + resume |
| GET  | `/api/resume/rank/:jdId` | Ranked resumes for JD |
| POST | `/auth/signup` | Register user |
| POST | `/auth/login` | Login with JWT |

---

## 🌐 Deployment (Planned)

- Backend: Render / Railway
- Frontend: Netlify
- DB: Supabase or Railway PostgreSQL

---

## 📸 Preview

_(Coming soon: deployed link + dashboard screenshots)_

---

## 🙋‍♂️ Author

**Abhishek Yadav**  
Full-Stack Developer | Java | Spring Boot | AI Enthusiast  
[LinkedIn] www.linkedin.com/in/abhishek-yadav-4b30b0310


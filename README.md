# 🌾 Schemes Web Application for Rural People

A web application designed to bridge the gap between rural communities and government welfare schemes. It helps users discover relevant schemes, ask questions via a chatbot, connect with volunteers based on their location, and engage in discussions—all from a user-friendly interface.

---

## 🌟 Features

- 🧾 **Scheme Explorer**: Easily browse and filter central and state government schemes based on eligibility.
- 🧠 **Chatbot for Quick Info**: Ask a chatbot about schemes and eligibility in a conversational way.
- 🔐 **Google OAuth Login**: One-click login using Google account.
- 💬 **Discussion Forum** *(Spring Boot)*: Ask questions, reply to others, and learn from public discussions.
- 🙌 **Volunteer Connect**: Users can reach out to nearby volunteers for assistance with schemes.

---

## 🧱 Tech Stack Overview

### 🌐 Main Web App (MERN Stack + Google OAuth + Chatbot)

- **Frontend**: React.js (with React Router, Axios)
- **Backend**: Node.js + Express.js + Java(Spring Boot)
- **Database**: MongoDB (via Mongoose)
- **Auth**: Google OAuth 2.0
- **Chatbot**: Dialogflow or custom chatbot logic

### 💬 Discussion Forum (Spring Boot App)

- **Endpoints**: REST APIs for creating threads, replies, user discussions
- **Database**: MongoDB
- **Note**: No Spring Security is used — forum is connected to main app’s user base

---

# 🌾 Schemes Web Application for Rural People

A full-stack web application designed to bridge the gap between rural communities and government welfare schemes. It allows users to discover relevant schemes, chat with a bot for quick information, connect with volunteers, and participate in a discussion forum—all through a user-friendly interface.

---

## 🌟 Features

- 🧾 **Scheme Explorer**: Browse and filter central and state government schemes based on user eligibility.
- 🧠 **AI Chatbot**: Ask scheme-related questions using an integrated chatbot powered by a language model.
- 🔐 **Google OAuth Login**: Secure and seamless login with Google accounts.
- 💬 **Discussion Forum** *(Spring Boot)*: Public Q&A space where users can ask and answer scheme-related queries.
- 🙌 **Volunteer Connect**: Location-based support system to connect users with nearby volunteers.

---

## 🧱 Tech Stack

### 🌐 Main Web App (MERN Stack)

- **Frontend**: React.js, Axios, React Router
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)
- **Authentication**: Google OAuth 2.0
- **Chatbot**: Gemini API or custom AI logic

### 💬 Discussion Forum (Spring Boot)

- **Language**: Java (Spring Boot)
- **API**: RESTful endpoints for threads, replies, and discussions
- **Database**: MongoDB
- **Security**: Basic auth integration with main app (no Spring Security)

---

## 🚀 Project Setup & Running Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Sa-ran-raj/Schemes-for-Rural-People.git
cd Schemes-for-Rural-People

2️⃣ Run the Spring Boot Discussion Forum
Open the /RestApi directory in your IDE (e.g., IntelliJ or Eclipse).

Locate the main application class with the @SpringBootApplication annotation.

Click the Run button or use your IDE’s tool to start the backend server.

3️⃣ Run the Node.js Backend
cd backend
npm install


Before running, create a .env file inside the /backend folder with the following content:
# Backend Environment Variables

PORT=3000
NODE_ENV=development
MONGODB_URI=your_mongodb_connection_string
SECRET_KEY=your_jwt_secret_key

# Gemini API
GEMINI_API_KEY=your_gemini_api_key
GEMINI_API_URL=https://generativelanguage.googleapis.com/"your api url
OFFLINE_MODE=false
DEBUG=true

# Google OAuth
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

Then start the server:

bash
Copy
Edit
node server.js

4️⃣ Run the React Frontend

cd frontend
npm install
npm run dev



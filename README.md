# 🧠 ThinkEra — AI Chat Application

ThinkEra is a full-stack AI-powered chat application that enables users to interact with an intelligent assistant in real time. It leverages the OpenAI API for generating responses and is built with a modern web stack.

> 🚀 Features

💬 Real-time AI chat interface
🔐 Secure API handling using backend 
🧠 Context-based conversation (threads support)
⚡ Fast and responsive UI built with React + Vite
🌐 REST API integration between frontend and backend

> 🛠️ Tech Stack

### Frontend

* React (Vite)
* CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB 

### APIs

* OpenAI API

> 📂 Project Structure

ThinkEra/
│
├── Frontend/        # React frontend (Vite)
├── Backend/         # Node.js backend
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── server.js

> ⚙️ Setup Instructions

### 1. Clone the repository

git clone https://github.com/your-username/ThinkEra.git
cd ThinkEra

### 2. Setup Backend

cd Backend
npm install

Create a `.env` file:

OPENAI_API_KEY=your_api_key
MONGO_URI=your_mongodb_uri
PORT=5000

Run backend:

npm start

### 3. Setup Frontend

cd Frontend
npm install
npm run dev

> 🌐 Deployment

* Backend deployed on Render
* Frontend deployed on Vercel

> 🔐 Security

* API keys are stored securely using environment variables
* No sensitive data is exposed to the frontend

> 📌 Future Improvements

* User authentication (JWT)
* Chat history persistence
* Rate limiting
* UI enhancements

> 📬 Contact

Feel free to connect for collaboration or feedback!

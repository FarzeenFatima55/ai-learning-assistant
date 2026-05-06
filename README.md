# 🤖 Prepz — Your AI Study Companion

> Transform your PDFs into interactive, AI-powered learning experiences.

Prepz is a full-stack web application built with the **MERN stack** that helps you study smarter. Upload any PDF and instantly unlock AI-powered tools — chat, summaries, flashcards, and quizzes — all tailored to your document's content.

<img width="955" height="446" alt="Screenshot 2026-05-05 184000" src="https://github.com/user-attachments/assets/433ecbec-ac28-44fb-8f4a-a310a125c41c" />

<img width="956" height="509" alt="Screenshot 2026-05-05 184600" src="https://github.com/user-attachments/assets/0944502f-a5c2-43d6-b2a8-2906256f793b" />

<img width="956" height="464" alt="Screenshot 2026-05-05 184528" src="https://github.com/user-attachments/assets/66c49165-88ba-48e8-986e-51b37b2396a9" />



## ✨ Features

- 📄 **PDF Upload** — Upload any document and extract its content instantly
- 💬 **AI Chat** — Chat with your document using Google Gemini AI
- 📝 **Auto Summaries** — Get concise summaries of any document
- 🃏 **Flashcards** — Auto-generated flashcards for quick revision
- 🧠 **Quizzes** — Test your knowledge with AI-generated quizzes
- 📊 **Progress Tracking** — Monitor your learning and improvement over time
- 🌙 **Dark / Light Mode** — Clean, modern UI with theme toggle

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React, Tailwind CSS, Vite |
| Backend | Node.js, Express.js |
| Database | MongoDB Atlas |
| AI | Google Gemini AI |
| Auth | JWT (JSON Web Tokens) |

---

## 🚀 Project Setup

### Prerequisites

- Node.js
- MongoDB Atlas account
- Google Gemini AI API key

---

### 📦 Install Dependencies

**Frontend:**
```bash
cd frontend
npm install
npm i axios lucide-react moment react-hot-toast react-markdown react-router-dom react-syntax-highlighter remark-gfm
```

**Backend:**
```bash
cd backend
npm install
npm i bcryptjs cors dotenv express express-validator jsonwebtoken mongoose multer pdf-parse @google/genai
```

---

### 🔐 Environment Variables

Create a `.env` file in the `backend` directory and add the following:

```env
MONGODB_URI=your_mongodb_atlas_uri
PORT=8000
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=7d
NODE_ENV=development
MAX_FILE_SIZE=10485760
GEMINI_API_KEY=your_gemini_api_key
```

---

### ▶️ Running the App

**Start the backend:**
```bash
cd backend
npm run server
```

**Start the frontend:**
```bash
cd frontend
npm run dev
```

---

## 📁 Project Structure

```
Prepz/
├── backend/
│   ├── config/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env
└── frontend/
    ├── src/
    │   ├── components/
    │   ├── context/
    │   ├── pages/
    │   ├── services/
    │   └── App.jsx
    └── index.html
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ using MERN Stack + Google Gemini AI</p>

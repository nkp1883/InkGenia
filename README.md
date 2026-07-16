<div align="center">

# ✍️ InkGenia

**An AI-powered full-stack blogging platform — from topic to published post in seconds.**

Built with the MERN stack, Google Gemini AI, and ImageKit to explore how generative AI can be embedded into a real content workflow, not just bolted on as a chatbot.


</div>

---

## 📌 About the Project

InkGenia is a personal portfolio project built to demonstrate end-to-end full-stack development: a secure admin content-management system, RESTful API design, cloud image handling, and integration with a generative AI model to automate content creation.

The core idea: an admin enters a topic, InkGenia's AI drafts the blog post, the admin refines and publishes it — and visitors browse the result by category on a fast, responsive public site.

This project was built to strengthen practical skills in:
- Designing and consuming REST APIs with Express & MongoDB
- Integrating a third-party generative AI API (Google Gemini) into a real product flow
- Handling authentication and protected admin routes with JWT
- Managing cloud-based image uploads and optimization with ImageKit
- Building a responsive, production-style UI with React and Tailwind CSS

---

## ✨ Key Features

- 🤖 **AI-powered blog generation** — enter a topic, and Google Gemini drafts the full post
- 📝 **Admin dashboard** — create, edit, publish, or delete blogs
- 🖼️ **Cloud image uploads** — thumbnails and images handled via ImageKit
- 📂 **Category-based browsing** — readers filter posts by topic
- 💬 **Comments** — with admin moderation
- 🔐 **JWT-secured admin authentication**
- ⚡ **Fast, responsive UI** — React, Vite, and Tailwind CSS

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React 19, Vite, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB (Mongoose) |
| AI | Google Gemini API |
| Media | ImageKit |
| Auth | JSON Web Tokens (JWT) |

---

## 📁 Project Structure

```
InkGenia/
├── client/                # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── assets/
│   │   └── main.jsx
│   └── package.json
├── server/                # Node.js backend
│   ├── configs/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- A [MongoDB](https://www.mongodb.com/) database (local or Atlas)
- A [Google Gemini API key](https://ai.google.dev/)
- An [ImageKit](https://imagekit.io/) account (public key, private key, URL endpoint)

### 1. Clone the repository

```bash
git clone https://github.com/nkp1883/InkGenia.git
cd InkGenia
```

### 2. Set up the backend

```bash
cd server
npm install
```

Create a `.env` file inside `server/`:

```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=your_admin_password
GEMINI_API_KEY=your_gemini_api_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

Run the backend:

```bash
npm run server
```

### 3. Set up the frontend

```bash
cd ../client
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🔑 Admin Access

Log in at `/admin` using the `ADMIN_EMAIL` and `ADMIN_PASSWORD` set in the server `.env` file to generate, edit, and publish posts.

---




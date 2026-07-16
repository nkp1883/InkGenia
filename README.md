<div align="center">

# ✍️ InkGenia

### **AI-Powered Blogging Platform**

Turn a single idea into a publish-ready blog in seconds using **Google Gemini AI**.

<p>
  <a href="https://ink-genia.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-InkGenia-6C63FF?style=for-the-badge" />
  </a>
  <a href="https://github.com/nkp1883/InkGenia">
    <img src="https://img.shields.io/github/stars/nkp1883/InkGenia?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/MERN-FullStack-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Google-Gemini-blue?style=for-the-badge" />
</p>

**Built with React, Node.js, Express, MongoDB, Google Gemini AI & ImageKit**

</div>

---

# 🚀 Live Demo

### 🌐 https://ink-genia.vercel.app/

Experience AI-assisted blog generation, secure publishing, and category-based content browsing.

---

# 📌 About

InkGenia is an AI-powered full-stack blogging platform built as a portfolio project to demonstrate modern web development practices, secure backend architecture, and practical integration of generative AI.

Instead of simply chatting with an AI, InkGenia embeds Google Gemini directly into the content creation workflow.

An administrator enters a blog topic, AI generates a complete draft, the content can be refined, enriched with images, and published instantly for readers.

The project showcases:

- RESTful API development with Express & MongoDB
- Secure JWT-based authentication
- AI-powered content generation using Google Gemini
- Cloud image storage with ImageKit
- Responsive frontend built using React and Tailwind CSS

---

# ✨ Features

### 🤖 AI Blog Generation
Generate complete blog drafts from a simple topic using Google Gemini.

### 📝 Admin Dashboard
Create, edit, publish and manage blogs through a secure dashboard.

### 🔐 Authentication
JWT-protected admin login with secure API routes.

### 🖼 Cloud Image Storage
Upload and optimize blog thumbnails using ImageKit.

### 📂 Category Filtering
Browse articles by category for an organized reading experience.

### 💬 Comment System
Readers can comment while administrators moderate discussions.

### ⚡ Responsive UI
Fast and modern interface powered by React, Vite and Tailwind CSS.

---

# 🛠 Tech Stack

| Layer | Technologies |
|---------|-------------|
| **Frontend** | React 19 • Vite • Tailwind CSS |
| **Backend** | Node.js • Express.js |
| **Database** | MongoDB • Mongoose |
| **Authentication** | JSON Web Token (JWT) |
| **AI Integration** | Google Gemini API |
| **Media Storage** | ImageKit |
| **Deployment** | Vercel |

---

# 📂 Project Structure

```text
InkGenia
│
├── client
│   ├── src
│   ├── public
│   ├── package.json
│   └── vite.config.js
│
├── server
│   ├── configs
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

# ⚙️ Installation

## Clone the Repository

```bash
git clone https://github.com/nkp1883/InkGenia.git
cd InkGenia
```

---

## Backend Setup

```bash
cd server
npm install
```

Create a `.env`

```env
PORT=3000

MONGODB_URI=

JWT_SECRET=

ADMIN_EMAIL=

ADMIN_PASSWORD=

GEMINI_API_KEY=

IMAGEKIT_PUBLIC_KEY=

IMAGEKIT_PRIVATE_KEY=

IMAGEKIT_URL_ENDPOINT=
```

Run the backend

```bash
npm run server
```

---

## Frontend Setup

```bash
cd ../client

npm install

npm run dev
```

Visit

```
http://localhost:5173
```

---

# 🔑 Admin Access

Visit

```
/admin
```

Use the credentials defined inside your backend `.env` file.

---

# 💡 Future Improvements

- Rich Text Editor
- Draft Saving
- AI-powered Blog Summaries
- Search & Pagination
- User Authentication
- Reading Time Estimation
- Dark Mode
- Blog Analytics Dashboard

---

# 🤝 Contributing

Contributions, suggestions and feature requests are welcome.

Feel free to fork the repository and open a Pull Request.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further improvements.

---

<div align="center">

### Made with ❤️ by Nikhil kr. Pandey

**InkGenia • AI Meets Modern Blogging**

</div>
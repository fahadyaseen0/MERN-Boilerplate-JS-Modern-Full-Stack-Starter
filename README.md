<div align="center">

<h2>🚀 Fast MERN APP</h2>

<p>
  <a href="https://github.com/abdullahalsuad/mern-boilerplate-js">
    <img src="https://img.shields.io/github/stars/abdullahalsuad/mern-boilerplate-js.svg?style=flat-square" alt="GitHub stars"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT"/>
  </a>
  <a href="https://github.com/abdullahalsuad/mern-boilerplate-js/network">
    <img src="https://img.shields.io/github/forks/abdullahalsuad/mern-boilerplate-js.svg?style=flat-square" alt="GitHub forks"/>
  </a>
  <a href="https://discord.gg/hECbGhyY5b">
    <img src="https://img.shields.io/badge/Join%20Our%20Community-Discord-7289da?logo=discord&logoColor=white" alt="Join our Discord"/>
  </a>
</p>

<p>
  A powerful CLI tool that generates a complete MERN (MongoDB, Express, React, Node.js) boilerplate with modern tools, best practices, and zero configuration needed. Perfect for developers who want to skip the tedious setup and jump straight into building amazing applications.
</p>

</div>

> 🎯 **Stop wasting time on project setup!** Generate a production-ready MERN stack application with industry-standard folder structure in seconds.

## ✨ Why Choose Fast MERN APP?

- 🏗️ **Industry-Standard Architecture**: Pre-configured folder structure following best practices
- ⚡ **Zero Config**: Works out of the box - no time wasted on setup
- 🔧 **Modern Tools**: Latest versions with optimized configurations
- 🔐 **Auth Ready**: Firebase authentication pre-integrated
- 🚀 **Deploy Ready**: Configured for popular hosting platforms

## 🚀 Quick Start

> 💡 **Pro Tip**: Use `npx` for the latest version without global installation!

### One Command Setup

```bash
# 🎯 Recommended: Using npx (always latest version)
npx create-fast-mern my-awesome-app
cd my-awesome-app

# 🔧 Set up environment variables FIRST
# Frontend
cd frontend
cp .env.example .env  # Configure your Firebase and API settings

# Backend
cd ../backend
cp .env.example .env  # Configure MongoDB, Firebase Admin, and secrets

# 📂 Install dependencies for both frontend and backend
cd ..
npm install  # Install root dependencies if any
cd frontend && npm install
cd ../backend && npm install

# 🔥 Start development servers
# Terminal 1: Start backend
cd backend && npm run dev

# Terminal 2: Start frontend
cd frontend && npm run dev
```

## 📦 What You Get

### 🎯 Frontend (React + Vite)

```
frontend/
├── src/
│   ├── components/     # Reusable UI components
│   ├── context/        # React context providers
│   ├── firebase/       # Firebase client configuration
│   ├── hooks/          # Custom React hooks
│   ├── pages/          # Page components with routing
│   │   └── shared/     # Shared layout components
│   ├── routes/         # React Router configuration
│   └── utils/          # Helper utilities
├── public/             # Static assets
├── index.html          # Entry HTML
├── vite.config.js      # Vite configuration
└── tailwind.config.js  # Tailwind CSS configuration
```

### 🔧 Backend (Node.js + Express)

```
backend/
├── src/
│   ├── config/         # Database & Firebase config
│   ├── controllers/    # Business logic handlers
│   ├── middleware/     # Authentication & validation
│   ├── models/         # Mongoose data models
│   ├── routes/         # API endpoint definitions
│   └── server.js       # Express server entry point
├── package.json        # Backend dependencies
└── vercel.json         # Deployment configuration
```

## 🛠️ Tech Stack Overview

| Category      | Frontend                                  | Backend              | Database & Auth             |
| ------------- | ----------------------------------------- | -------------------- | --------------------------- |
| **Core**      | React 19, Vite 6.3                        | Node.js, Express 5.1 | MongoDB 6.16, Mongoose 8.15 |
| **Styling**   | Tailwind CSS 4.1                          | -                    | -                           |
| **State**     | React Query, Context                      | -                    | -                           |
| **Auth**      | Firebase SDK                              | Firebase Admin SDK   | Firebase Auth               |
| **HTTP**      | Axios                                     | CORS, Dotenv         | -                           |
| **Forms**     | React Hook Form                           | -                    | -                           |
| **UI/UX**     | Lucide Icons, React Toastify, SweetAlert2 | -                    | -                           |
| **Dev Tools** | ESLint, React DevTools                    | Nodemon              | -                           |

## 💻 Development Commands

### Frontend Commands

```bash
cd frontend
npm run dev      # Start development server
npm run build    # Build for production
npm run preview  # Preview production build
npm run lint     # Run ESLint
```

### Backend Commands

```bash
cd backend
npm run dev      # Start with Nodemon
npm start        # Start production server
```

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. 🍴 Fork the repository
2. 🌟 Create a feature branch
3. 💻 Make your changes
4. ✅ Test thoroughly
5. 📤 Submit a pull request

## 💬 Community & Support

- 🐛 [Report Issues](https://github.com/abdullahalsuad/mern-boilerplate-js/issues)
- 💡 [Feature Requests](https://github.com/abdullahalsuad/mern-boilerplate-js/discussions)
- ⭐ [Star on GitHub](https://github.com/abdullahalsuad/mern-boilerplate-js)
- 🐦 [Follow on Twitter](https://twitter.com/abdullahalsuad)

## 📄 License

MIT © [Abdullah Al Suad](https://github.com/abdullahalsuad)

---

<div align="center">

**Made with ❤️ by [Abdullah Al Suad](https://github.com/abdullahalsuad), for developers**

[🌟 Star on GitHub](https://github.com/abdullahalsuad/mern-boilerplate-js) • [📦 NPM Package](https://www.npmjs.com/package/mern-boilerplate-js) • [🐛 Report Bug](https://github.com/abdullahalsuad/mern-boilerplate-js/issues)

</div>

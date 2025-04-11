# Ai-Code-Review
# 🧠 AI Code Reviewer

A full-stack AI-powered code review tool built with **Node.js**, **React**, and **Google's Gemini API**. This app takes code input, analyzes it using an AI model, and returns professional-grade feedback based on best practices, maintainability, efficiency, and security.

## 🔍 Features

- 💬 Natural language-based code feedback
- ✅ Highlights bad code practices and offers recommended fixes
- 💡 Suggests improvements and optimizations
- 📚 Follows industry-standard coding principles
- 🚀 Fast development environment powered by Vite

## 🛠 Tech Stack

### Frontend
- React (with Vite)
- TailwindCSS *(optional based on UI)*
- JSX-based components

### Backend
- Node.js with Express
- Google Generative AI (Gemini API)
- Modular architecture (`routes`, `controllers`, `services`)

## 🔑 Key Files

- `src/services/ai.service.js` — Core logic to interact with the AI API and provide code review
- `app.js` — Sets up the Express server
- `Frontend/src/` — Contains React components for UI interaction
- `.env` — Stores the Gemini API key securely

## ⚙️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-code-review.git
cd ai-code-review


2. Install Dependencies
# Backend
cd BackEnd
npm install

# Frontend
cd ../Frontend
npm install


3. Environment Variables
GOOGLE_GEMINI_KEY=your_gemini_api_key

4. Run the App
cd BackEnd
npx nodemon

Start the frontend:
cd ../Frontend
npm run dev



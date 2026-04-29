# 🐛 BugZero - AI-Powered Bug Tracking System

BugZero is an advanced, real-world bug tracking application that leverages AI to help developers identify, categorize, and solve software issues efficiently.

## 🔗 Links
- **Live Link:** [bugzero.vercel.app](https://bugzero.vercel.app)
- **Repository:** [GitHub Link](https://github.com/dev-alauddin-bd/BugZero)

## 📸 Screenshot
![Project Screenshot](https://raw.githubusercontent.com/dev-alauddin-bd/BugZero/main/public/screenshot.png) *(Note: Replace with actual screenshot link)*

## 🚀 Tech Stack
- **Frontend:** React, Tailwind CSS, Lucide Icons.
- **Backend:** Node.js (Express), TypeScript, MongoDB.
- **AI Integration:** OpenAI, Anthropic, Google Gemini (via AI SDK).
- **Validation:** Zod.

## ✨ Main Features
- 🤖 **AI Bug Analysis:** Automatically analyzes error logs and suggests potential fixes.
- 📂 **Multi-Agent Support:** Integrates OpenAI, Anthropic, and Gemini for diverse AI insights.
- 🔍 **Web Crawling:** Integrated with Firecrawl for gathering relevant documentation.
- 🔐 **Secure Auth:** JWT-based user authentication and protected routes.
- 📊 **Real-time Status:** Track bug status from "Reported" to "Resolved" in real-time.

## 📦 Dependencies
- `express`, `mongoose`, `ai` (Vercel AI SDK), `@ai-sdk/openai`, `zod`, `bcryptjs`, `jsonwebtoken`.

## 🛠️ Local Setup Guide

### 1. Clone the repository
```bash
git clone https://github.com/dev-alauddin-bd/BugZero.git
cd BugZero
```

### 2. Install dependencies
```bash
# For Backend
cd backend
npm install

# For Frontend
cd ../frontend
npm install
```

### 3. Environment Variables
Create a `.env` file in the `backend` directory:
```env
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_secret
OPENAI_API_KEY=your_key
```

### 4. Run the project
```bash
# Backend
npm run dev

# Frontend
npm start
```

---
Built with ❤️ by [MD ALAUDDIN](https://github.com/dev-alauddin-bd)

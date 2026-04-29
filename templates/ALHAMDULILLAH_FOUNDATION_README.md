# 🤲 Alhamdulillah Foundation - Charity Management System

Alhamdulillah Foundation is a comprehensive charity management platform designed to streamline donations, project management, and volunteer coordination. It features a modern, multilingual interface and secure payment integration.

## 🔗 Links
- **Live Link:** [alhamdulillah-foundation.vercel.app](https://alhamdulillah-foundation.vercel.app)
- **Frontend Repo:** [GitHub Link](https://github.com/dev-alauddin-bd/Alhamdulillah-foundation-frontend)
- **Backend Repo:** [GitHub Link](https://github.com/dev-alauddin-bd/Alhamdulillah-foundation-backend)

## 📸 Screenshot
![Project Screenshot](https://raw.githubusercontent.com/dev-alauddin-bd/Alhamdulillah-foundation-frontend/main/public/screenshot.png) *(Note: Replace with actual screenshot link)*

## 🚀 Tech Stack
- **Frontend:** Next.js 16 (Latest), Tailwind CSS 4, Redux Toolkit, i18next (Multilingual), Radix UI.
- **Backend:** NestJS, MongoDB (Mongoose), Passport.js (JWT), Nodemailer.
- **Tools:** Firebase, SSLCommerz (Payment Gateway), Vercel.

## ✨ Main Features
- 🌍 **Multilingual Support:** Full support for English and Bengali.
- 💳 **Secure Payments:** Integrated with SSLCommerz for safe and easy donations.
- 🔐 **Advanced Auth:** Two-step verification using Email OTP and JWT-based authentication.
- 📊 **Dynamic Dashboard:** Real-time stats for donations, projects, and users.
- 📧 **Automated Emails:** Instant donation receipts and verification emails via Nodemailer.
- 📱 **Responsive Design:** Fully optimized for mobile, tablet, and desktop.

## 📦 Dependencies
### Frontend:
- `@reduxjs/toolkit`, `next`, `tailwindcss`, `i18next`, `lucide-react`, `sonner`.
### Backend:
- `@nestjs/core`, `@nestjs/mongoose`, `bcrypt`, `jsonwebtoken`, `sslcommerz-lts`, `nodemailer`.

## 🛠️ Local Setup Guide

### 1. Clone the repository
```bash
git clone https://github.com/dev-alauddin-bd/Alhamdulillah-foundation-frontend.git
cd Alhamdulillah-foundation-frontend
```

### 2. Install dependencies
```bash
npm install
```

### 3. Environment Variables
Create a `.env` file in the root and add necessary keys:
```env
NEXT_PUBLIC_API_URL=your_api_url
NEXT_PUBLIC_FIREBASE_CONFIG=your_config
```

### 4. Run the project
```bash
npm run dev
```

---
Built with ❤️ by [MD ALAUDDIN](https://github.com/dev-alauddin-bd)

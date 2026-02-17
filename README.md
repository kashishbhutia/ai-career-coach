# 🚀 AI Career Coach

A Full Stack AI-powered Career Coach built using modern web technologies.  
This platform helps users explore career paths, receive AI-driven guidance, and manage their professional growth efficiently.

---

## 🌟 Tech Stack

- ⚡ Next.js (App Router)
- 🗄️ Neon DB (PostgreSQL)
- 🔗 Prisma ORM
- 🎨 Tailwind CSS
- 🧩 Shadcn UI
- 🔐 Clerk Authentication
- 🤖 Google Gemini API
- ⚙️ Inngest (Background Jobs & Workflows)

---

## ✨ Features

- 🔐 Secure Authentication System
- 🤖 AI-based Career Recommendations
- 📊 Personalized Career Insights
- 📂 Database Management with Prisma & Neon
- ⚡ Background Job Processing
- 🎨 Clean & Modern Responsive UI

---

## 🛠️ Environment Variables

Create a `.env` file in the root directory and add the following:

```env
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

```

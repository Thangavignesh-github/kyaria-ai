# AI Career Coach

AI Career Coach is a **full-stack AI-powered career guidance platform** built with **Next.js, NeonDB, Prisma, Inngest, and Clerk**. It helps users identify career paths, enhance skills, and get personalized job recommendations.

## 🚀 Tech Stack
- **Frontend:** Next.js, Tailwind CSS, ShadCN UI
- **Backend:** Prisma, Inngest
- **Database:** NeonDB (PostgreSQL)
- **Authentication:** Clerk

## 🛠 Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/piyush-eon/ai-career-coach.git
cd ai-career-coach
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the root directory and configure the following:
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

### 4️⃣ Run the Development Server
```sh
npm run dev
```
Access the app at **http://localhost:3000**.

## 📌 About NeonDB
[NeonDB](https://neon.tech/) is a **serverless PostgreSQL database** that provides **instant provisioning, auto-scaling, and branching**. It is optimized for **modern serverless applications** like Next.js and offers:
- **On-demand scaling** with no downtime
- **Branching** to create isolated database environments
- **Low latency and high performance**

## 🔑 About Clerk
[Clerk](https://clerk.dev/) is an authentication and user management platform for modern web apps. It provides:
- **Prebuilt authentication UIs** (Sign-in, Sign-up, Multi-factor authentication)
- **User management dashboard**
- **Secure session handling**
- **Integration with Next.js and serverless environments**

## 📜 License
This project is licensed under the **MIT License**.

---
### 🎯 Contributing
Feel free to **fork** this repository, submit issues, or create **pull requests** to improve the project!

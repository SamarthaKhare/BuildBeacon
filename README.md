# 🚀 BuildBeacon

### A Community Platform to Showcase What You Build

**BuildBeacon** is a modern community platform where creators share their projects, discover new launches, and engage through real-time interactions.



---

## ✨ Features

### 📦 Product Management

* Product submission with **validation & moderation**
* Intelligent **categorization and tagging**
* Featured & recently launched feeds
* Support for:

  * Apps
  * AI Tools
  * SaaS
  * Creative Projects

### 🎨 User Experience

* Interactive product cards
* Fully responsive design
* Real-time voting (upvote / downvote)
* Creator dashboard
* Toast notifications
* SEO-friendly product pages

### 🔐 Admin & Authentication

* Admin panel for moderation
* Protected routes & API endpoints
* Secure authentication via **Clerk**

  * Passkeys
  * GitHub login
  * Google login

---

## 🛠 Tech Stack

| Layer              | Technology                         |
| ------------------ | ---------------------------------- |
| **Framework**      | Next.js 16 (App Router) + React 19 |
| **Authentication** | Clerk                              |
| **Database**       | NeonDB (PostgreSQL) + Drizzle ORM  |
| **UI**             | ShadCN UI + TailwindCSS 4          |
| **Validation**     | Zod + React Hook Form              |
| **Language**       | TypeScript                         |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-url>
cd buildbeacon
```

### 2️⃣ Setup Environment Variables

Copy the example file:

```bash
cp .env.example .env.local
```

Fill in:

* Clerk authentication keys
* NeonDB connection string

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Setup Database

```bash
npx drizzle-kit push
```

### 5️⃣ Run the Development Server

```bash
npm run dev
```

App will run at:

```
http://localhost:3000
```

---

## 🧠 Architecture Highlights

* App Router-based routing (Next.js 16)
* Type-safe database queries via Drizzle ORM
* Form validation using Zod schemas
* Fully typed codebase with TypeScript
* Secure API design with protected routes

---

## 🙌 Acknowledgements

* Clerk
* NeonDB
* Drizzle ORM
* ShadCN UI
* Next.js

---

If you'd like, I can also:

* Add badges (tech, license, deploy status)
* Add deployment section (Vercel / Railway / Render)
* Add screenshots section
* Add contribution guidelines
* Make it more “open-source polished” style



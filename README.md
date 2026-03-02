# BuildBeacon - A community platform to showcase your work

A community platform where creators share what they've built and discover what's launching.

Features
Product Management: Submission with validation & moderation, intelligent categorization/tagging, featured & recently launched feeds, and support for apps, AI tools, SaaS, and creative projects.

User Experience: Interactive product cards, responsive design, real-time voting (upvote/downvote), creator dashboard, toast notifications, and SEO-friendly product pages.

Admin & Auth: Admin panel for moderation, protected routes & API endpoints, secure authentication via Clerk (Passkeys, GitHub, Google).

Tech Stack
Layer    Tech
Framework    Next.js 16 App Router + React 19
Auth    Clerk
Database    NeonDB (PostgreSQL) + Drizzle ORM
UI    ShadcN UI + TailwindCSS 4
Validation    Zod + React Hook Form
Language    TypeScript
Getting Started
Fork & clone the repo
Copy .env.example → .env.local and fill in:
Clerk authentication keys
NeonDB connection string
npm install
npx drizzle-kit push
npm run dev
Acknowledgements
Clerk · NeonDB · Drizzle ORM · ShadcN UI · Next.js

License
MIT

Trimmed ~60% while keeping every feature, tech, step, and link intact. The main change was consolidating the bullet-heavy sections into prose + a table.




# Hi, I'm Lucas 👋

**Frontend / Full-Stack Developer** building real, production-used web applications 
— from database design to deployment, with enterprise-grade architecture.

I transitioned from a 6-year career in live TV production (audio & camera operation 
for TV Globo, Endemol Shine, Teleimage) into software development through hands-on, 
problem-driven learning. I don't just build features — I architect systems: designing 
multi-tenant architectures, implementing Row-Level Security (RLS) for data isolation, 
and shipping PWA applications that work offline.

🌍 **Based in São Paulo, Brazil** — open to remote-first roles with EU/Spain teams.
📧 **Reach out:** [LinkedIn](https://www.linkedin.com/in/lucas-soares-8942a4405/) 
| [Email](mailto:sslucassoares.s.s@icloud.com)

---

### 🛠️ Core Tech Stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🚀 Architecture & Specializations

- **Multi-tenant SaaS:** Row-Level Security (RLS), per-user data isolation, enterprise access control
- **Progressive Web Apps (PWA):** Service Workers, offline-first caching strategies, Web App Manifest
- **Real-time Sync:** Supabase Realtime subscriptions, optimistic updates, conflict resolution
- **Backend:** RESTful APIs, Node.js server-side logic, database migrations, environment management
- **Databases:** PostgreSQL schema design, normalized data structures, query optimization
- **Deployment:** Vercel (frontend), Supabase hosting (backend), automated CI/CD workflows

---

### 🚀 Featured Projects

#### 🔹 Planilha Inteligente — Route & Sales Management SaaS

**Multi-tenant web system for field sales representatives** managing 150+ store visits per day with persistent route planning.

**What it does:**
- Client management with per-client discounts (fixed R$ amounts, deducted once per visit)
- Per-partner-company commission rates (configurable per sale item)
- Drag-and-drop persistent route planner (mobile-optimized with SortableJS)
- Multi-item sales tracking per visit with timezone handling (UTC → Brazil UTC-3)
- Interactive analytics dashboard with client discount tracking
- City name deduplication (case-insensitive merging)
- Google Maps coordinate fields for client location

**Tech & Architecture:**
- Frontend: React, HTML5, CSS3, Vercel deployment
- Backend: Node.js, Supabase (PostgreSQL with Row-Level Security)
- Multi-tenant isolation via RLS policies across 7 tables
- Real-time data sync (Supabase Realtime)
- **Live in production** with real user (Caio Fernandes, 150+ stores)

**Try it:**
- 🔗 [Live App](https://planilha-inteligente-liart.vercel.app)
- 📧 Demo: `demo@planilhainteligente.com` / `Demo2026!`
- 💻 [GitHub Repo](https://github.com/sslucassoaresss-source/planilha-inteligente)

---

#### 🔹 Miriarte — Smart Inventory Management System

**Fully serverless PWA for jewelry inventory & sales**, in daily production use with offline-first architecture.

**What it does:**
- Real-time product catalog with image uploads (Supabase Storage)
- Stock movement tracking (additions, sales, consignments)
- Multi-tenant data isolation via Row-Level Security (RLS)
- Consignment control workflow with quote-to-sale pipeline
- Sales dashboard with charts and analytics
- Service Worker caching (offline-first, v6+ versioning)
- Batch backup/restore with retry logic for infrastructure resilience

**Tech & Architecture:**
- Frontend: React, PWA, Service Workers, HTML5, CSS3
- Backend: Supabase (PostgreSQL, Auth, Realtime, Storage)
- Multi-tenant RLS policies with per-user data isolation
- Optimistic updates & conflict resolution for offline sync
- Vercel deployment with automated builds
- **Live in production** with real business user (Miriam's jewelry business)

**Try it:**
- 🔗 [Live App](https://estoque-inteligente-pi.vercel.app/index.html)
- 📧 Demo: `demo@estoque.com` / `Demo2026!`
- 💻 *Private repo (business data sensitivity)*

---

#### 🔹 GameFix — E-commerce Store (Full Admin Access)

**Full-stack e-commerce platform showcasing modern SaaS patterns** — public demo with fictional game retail data and complete admin panel.

**What it does:**
- Product catalog with filtering & search
- Shopping cart with real-time updates
- Checkout workflow (mock payment integration)
- Order tracking dashboard
- Admin panel: product management, order tracking, analytics
- Role-based access control (public user vs admin)

**Tech & Architecture:**
- Frontend: React, Vercel deployment
- Backend: Node.js, Supabase (PostgreSQL, Auth)
- Multi-tenant ready (RLS patterns implemented)
- Real-time cart sync (Supabase Realtime)

**Try it:**
- 🔗 [Live App](https://game-fix-rust.vercel.app/)
- 📧 Admin: `admin@gamefix.com` / `Demo2026!`
- 💻 [GitHub Repo](https://github.com/sslucassoaresss-source/gamefix)
- *Explore the admin dashboard for full feature showcase*

---

### 🌱 Always Learning

I'm constantly deepening my expertise in:

- **JavaScript (ES6+):** Mastering advanced patterns — closures, higher-order functions, async/await flow, event loop optimization
- **React Fundamentals:** Hooks lifecycle, state management patterns, performance optimization (memoization, code splitting)
- **Backend Architecture:** API design, database normalization, caching strategies, rate limiting
- **Software Design Patterns:** MVC, composition over inheritance, SOLID principles applied to real projects
- **DevOps Basics:** CI/CD pipelines, environment configuration, debugging production issues

**Philosophy:** I don't just *learn about* new tech — I learn by **shipping things**. Most of what I know came from building production systems, hitting real problems, and figuring out solutions under constraints.

---

### ⭐ What Sets Me Apart

✅ **Real Production Experience**
- Not learning tutorials — building systems used by real people daily
- Shipped 3 production SaaS applications handling real business workflows
- Experience debugging infrastructure issues (Supabase outages, data integrity, performance)

✅ **Enterprise Architecture Thinking**
- Designed multi-tenant SaaS from the ground up (not bolted on later)
- Implemented Row-Level Security (RLS) correctly across all tables
- Understand trade-offs: normalization vs. denormalization, real-time vs. eventual consistency

✅ **Full-Stack Owner Mentality**
- Own the entire stack: database schema → frontend UX → deployment strategy
- Don't hand off problems — I debug and fix across layers
- Built PWA offline-first architecture (not just a buzzword)

✅ **Self-Taught Problem-Solver**
- Transitioned from zero code to shipping production systems in months
- Learn by doing, not by tutorials — research, experiment, iterate, ship
- Comfortable with ambiguity and shipping imperfectly

---

### 📊 GitHub Activity

[![Lucas's GitHub stats](https://github-readme-stats.vercel.app/api?username=sslucassoaresss-source&show_icons=true&theme=default&hide_border=true)](https://github.com/sslucassoaresss-source)

---

### 🎯 Ready to Work Together?

I'm open to:
- **Full-Stack / Frontend roles** with remote-first teams (especially EU/Spain-based)
- **Freelance projects** — SaaS, PWA, inventory systems, e-commerce
- **Technical discussions** about architecture, database design, or scaling challenges

**Let's connect:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-soares-8942a4405/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sslucassoares.s.s@icloud.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sslucassoaresss-source)

---

**⚡ Check out the featured projects above — all live and ready to explore!**

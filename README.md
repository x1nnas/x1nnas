<h1 align="center">Hi, I'm José Ferreira 👋</h1>

<p align="center">
  Full-Stack Web Developer • React • TypeScript • Node.js
</p>

<p align="center">
  I build clean, secure, and user-centered web applications
</p>

<br />

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" width="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" />
</p>

---

## 🚀 About Me
  
I am a **full-stack web developer** with a strong focus on clarity, maintainability, and real-world problem solving.

I build full-stack web applications across the entire stack — from interactive, accessible frontends to REST APIs, database design, authentication systems, and deployment. My work spans different tech choices depending on what the project calls for, and I care as much about the decisions behind an architecture as I do about the code itself.

I enjoy understanding *why* things are built the way they are — from API architecture and authentication flows to UX decisions and code structure.

---

## 🧠 Current Focus

- Completed the **first phase of an intensive full-stack bootcamp**
- Now in the **second phase**, focused on **Web3 development**
- Currently also sharpening my skills with **AI tools and LLM integration** — building with Claude Code and Codex daily, and working towards embedding AI into my own products
- Portfolio live at [josemsferreira.com](https://josemsferreira.com)

---

## 🛠️ Tech Stack

**Frontend**
- React
- TypeScript
- JavaScript
- HTML & CSS
- Mobile-first, accessible UI design

**Backend**
- Node.js
- Express
- Next.js (App Router, API routes, server actions)
- REST APIs
- JWT authentication
- Backend testing (Jest & Supertest)

**Databases**
- MongoDB
- PostgreSQL

**Tooling**
- Git & GitHub
- API testing
- Project structuring & documentation
- Claude Code
- Codex

---

## 🚀 Projects

### 🗺️ PitchBase — *v1 Completed*

A **full-stack football pitch management platform** built for scouting teams. Staff can log, classify, and manage pitches and venue complexes across Portugal on an **interactive map** — with rich detail panels, photo galleries, and real-time CRUD operations.

Built to replace spreadsheets in a real football scouting workflow.

**Features & concepts**

- **Mapbox GL JS** powered map with GeoJSON-native clustering — custom SVG markers per status, cluster zoom, flyTo animations, and satellite/streets layer toggle
- **Draggable pin relocation** — staff can drag any marker to correct its position, persisted immediately via PATCH
- **Three-state status workflow** per pitch: *Próprio* (owned), *Por visitar* (remotely scouted), *Visitado* (physically visited) — each with distinct map marker styling
- Full **CRUD** for pitches and venue complexes, with address reverse-geocoding via Mapbox Geocoding API on pin drop
- **Photo management** with client-side compression before upload (≤ 800px / ≤ 200KB), cover photo designation, and ordered gallery with lightbox
- **Role-based access control** (Admin / Editor / Leitor) via Supabase Auth JWT custom claims
- **Dual filter system** (status + pitch size) synced across the map and list drawer in real time
- **Shareable public pitch pages** (`/pitches/[id]`) rendered server-side with Open Graph metadata
- **Progressive Web App** — installable on iOS and Android
- Dashboard with profile photo upload (crop-to-circle), stat cards, and pitch breakdown by status

**Technical highlights**

- **Next.js 14 App Router** with server-side data fetching at the route level — no loading flash on initial map render
- **Full TypeScript** with return types derived via `ReturnType` inference — no manual type duplication
- **Drizzle ORM + PostgreSQL** via Supabase; Zod schemas shared between client and server for consistent validation
- **Mapbox marker lifecycle management** with explicit React root unmounting to prevent memory leaks; click handlers stored in refs to avoid stale-closure bugs
- **GeoJSON-level filtering** — filter state feeds into a `useMemo` that populates the Mapbox source directly, keeping filtering O(n) at the data level
- Tailwind CSS + shadcn/ui, React Hook Form, Supabase Storage

---

### 🧘 MindEase — *v1 Completed*

A **full-stack Progressive Web Application (PWA)** designed as an emotional wellness companion.  
MindEase allows users to **track their mood, write private journal entries, and interact with Serenity — an AI-powered chatbot** that provides supportive conversation.

The application focuses on **privacy, calm user experience, and accessibility**, combining modern frontend architecture with a secure backend and AI integration.

**Features & concepts**

- Secure authentication with **JWT-based login system**
- **Daily mood tracking** with visual history
- **Private journaling system** with full CRUD operations
- **AI-powered chatbot (Serenity)** using OpenAI for emotional support conversations
- **Progressive Web App** with installability and offline capabilities
- **Bilingual interface** (English + Portuguese 🇵🇹)
- **Responsive, ambient UI** designed for a calm experience

**Technical highlights**

- Full **TypeScript implementation** across frontend and backend
- **React + Vite frontend** with modern component architecture
- **Node.js + Express REST API**
- **MongoDB + Mongoose** for data modeling
- **Rate limiting and AI usage limits** to prevent abuse and manage costs
- **Production error monitoring with Sentry**
- Secure password storage with **bcrypt**

MindEase is my **first fully deployed end-to-end product**, built to practice real-world application architecture, authentication flows, API design, and AI integration.

---

### 🪟 NoiseWindow — *v1 Completed*

A Progressive Web App designed for shared living spaces to communicate **availability and quiet hours without interruption**.

**Features & concepts**
- Animated real-time status indicators (Lottie)
- Automatic schedule-based availability updates
- Installable Progressive Web App with offline support
- Bilingual interface (English & Portuguese)
- Admin panel with PIN-protected scheduling controls

Built with **Next.js, TypeScript, Tailwind CSS, and Supabase**, focusing on responsive design, offline functionality, and clear visual communication.

---

### ⏱️ Flow — Pomodoro Extension

A **minimal, reliable Pomodoro timer** built as a Chrome extension, focused on deep work and zero friction.

**Highlights**

- Background-driven timer using **Manifest V3 service worker + chrome.alarms**
- **Local-first persistence** (no backend required)
- Keyboard-first UX for fast interaction
- Daily stats, streak tracking, and 7-day progress view
- Clean separation between UI, hooks, and runtime logic

A small project focused on **reliability, simplicity, and intentional UX design**.

---

### 🔧 Practice Applications (Ongoing)

I'm currently focusing on **smaller projects** to practice and refine:

- Authentication flows
- API integrations
- Database modeling
- UI/UX patterns
- Application structure and state management

These projects help me iterate fast and improve intentionally.

---

### 🌐 Portfolio Website — *Completed*

My personal portfolio is live at **[josemsferreira.com](https://josemsferreira.com)**, showcasing finished projects, technical decisions, and what I've learned along the way.

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=x1nnas&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=x1nnas&layout=compact&theme=tokyonight" />
</p>

---

## 🎯 Goals

- Ship production-quality full-stack applications
- Deepen expertise in **React + TypeScript** and **Next.js**
- Improve backend architecture and testing practices
- **Integrate LLMs** into my own products and explore AI-powered application development
- Get better at building with AI tools as part of my everyday workflow
- Secure a **junior / trainee full-stack developer role**
- Contribute to open-source projects

---

## 📫 Let's Connect

<p>
  📧 <strong>Email:</strong> <a href="mailto:jmsfbusiness@gmail.com">jmsfbusiness@gmail.com</a><br />
  💼 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/jose-msferreira">José M.S. Ferreira</a><br />
  🌐 <strong>Portfolio:</strong> <a href="https://josemsferreira.com">josemsferreira.com</a>
</p>

---

<p align="center">
  Thanks for stopping by 👀<br />
  Always open to collaboration, feedback, or talking tech 🚀
</p>

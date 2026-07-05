# Nawwar Diab
Full-stack Engineer building RESTful APIs with Go and modern React/React Native frontends.
Based in Berlin, open to on-site and remote opportunities. AI-native workflow (Claude Code, Cursor).

---

## Currently
**Learning:** 42 Berlin — systems programming, C, Python, algorithms, Docker (Feb 2026–present)
**Building:** Moneypot — real-time iOS household budget app (Go + Echo + React Native + Supabase), architected from a full Technical Requirements Document before writing code

---

## Experience

**Full-Stack Developer Intern** | spaceSHIFT A. A. GmbH | 3 months
- Built authentication, address, products, orders and cart management APIs with Go and PostgreSQL
- Developed React/TypeScript frontends for API testing and validation
- Containerized applications with Docker
- Implemented clean architecture patterns with proper separation of concerns

**Web Development Tutor & Peer Mentor** | DCI Digital Career Institute GmbH | 7 months
Mentored 10+ students in JavaScript, React, and web development fundamentals through code reviews and pair programming sessions.

**42 Berlin** | Software Engineering | Feb 2026–Present
Peer-to-peer, project-based curriculum: C, Python, algorithms, systems programming, Docker, AI (LLMs, RAG, prompt engineering).

---

## Tech Stack
**Backend:** Go • Echo • PostgreSQL • Node.js • Express • MongoDB
**Frontend:** React • React Native • JavaScript/TypeScript • TailwindCSS
**DevOps:** Docker • Linux • Railway • Vercel
**AI Tools:** Claude Code • Cursor — daily development workflow

---

## Projects

### Moneypot — Real-Time Household Budget App (in development)
Real-time shared expense tracker for couples, architected from a complete Technical Requirements Document before implementation began. Includes a live architecture decision log (ADRs) and technical debt register maintained alongside the code.
- Go + Echo backend, strict layered architecture (Handler → Service → Repository) — client never touches the database directly
- React Native + Expo (bare workflow), TypeScript strict mode, PostgreSQL via Supabase
- All financial amounts stored as integer cents (int64) — avoids float precision errors in money handling
- Full spec and decision log available on request

**Stack:** Go, Echo, React Native, TypeScript, PostgreSQL, Supabase

### Auth Service – Production Authentication API
🌐 **[Live Demo](https://auth-frontend-react-ts.vercel.app)** | [Backend API](https://auth-service-backend-go-production.up.railway.app) | [Code: Backend](https://github.com/nawwardiab/auth-service-backend-go) • [Frontend](https://github.com/nawwardiab/auth-frontend-react-ts)

Full-stack authentication platform deployed on Railway and Vercel.
- JWT authentication with HTTP-only cookies and CSRF protection
- RESTful API with clean 4-layer architecture (Go + Echo + PostgreSQL)
- Address management CRUD operations
- React TypeScript frontend with Axios interceptors
- Docker containerized with multi-stage builds (5MB final image)
- **Deployed December 2025** – Production-ready with cross-site security

**Stack:** Go, Echo, PostgreSQL, React, TypeScript, Docker, Railway, Vercel

### MERN Expense Tracker
[Repository](https://github.com/nawwardiab/mern-expense-tracker)

Expense management platform with group splitting features (4-person team).
- Built 38+ REST API endpoints across 6 MongoDB collections
- Implemented automated expense splitting and balance calculations
- Developed React frontend with Context API and Chart.js visualizations
- Created invite system and payment settlement tracking

**Stack:** MongoDB, Express, React, Node.js

---

## Contact
[LinkedIn](https://linkedin.com/in/nawwar-diab)

Open to backend and full-stack opportunities in Berlin or remote.

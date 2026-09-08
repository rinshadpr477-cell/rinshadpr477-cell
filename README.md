# RINSHAD PR

**Software Engineer · Full-Stack Developer · Real-Time & AI Systems**

I build scalable web applications, real-time systems, and production-ready software with a focus on clean architecture, reliability, and developer experience.

Currently focused on **Next.js, TypeScript, Node.js, PostgreSQL, real-time/job-queue architectures, and applied AI (RAG, multi-agent systems).**

---

### Tech Stack

**Languages**
`JavaScript` `TypeScript` `Python` `Java` `SQL`

**Frontend**
`React` `Next.js` `Redux` `React Router` `React Hook Form` `Tailwind CSS` `Bootstrap`

**Backend**
`Node.js` `Express.js` `REST APIs` `WebSocket / Real-Time Streaming` `JWT` `OAuth 2.0` `RBAC` `Bcrypt`

**Databases**
`MongoDB` `Mongoose` `PostgreSQL` `Prisma`

**Real-Time & AI**
`Twilio Media Streams` `Gemini Live API` `Redis` `BullMQ` `Background Workers` `RAG Pipelines` `Qdrant` `Multi-Agent Systems` `Hugging Face` `Sentence-Transformers` `Prompt Engineering`

**Cloud & DevOps**
`Docker` `Docker Compose` `AWS EC2` `AWS IAM` `NGINX` `SSL/TLS` `GitHub Actions` `CI/CD`

**Testing & Tools**
`Jest` `Git` `GitHub` `Postman`

---

### Featured Engineering Work

#### 01 — Groundcrew — Autonomous RAG + Multi-Agent GitHub Issue Triage

Production-style RAG + multi-agent pipeline that triages real GitHub issues end-to-end: classifies, retrieves similar past issues via semantic search, drafts a grounded reply, and runs it through a critic agent that catches unsupported claims before anything reaches a human.

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `Qdrant` `Sentence-Transformers` `Hugging Face` `Ollama` `Docker` `GitHub Actions`

* Evaluated against **5,318 real issues** from a popular open-source repo — 3,181 embedded and indexed
* Critic-agent revision loop reaches **96.7% auto-approval** (29/30), with unverifiable drafts escalated to human review instead of shipped
* CI-gated eval harness enforces a **0.82 retrieval-relevance baseline** on every push, failing the build on regression
* Router classification accuracy: **72.5%** against real GitHub labels; API load-tested at 15.4 req/s with 0 errors
* Pluggable local (Ollama, free) or hosted (Hugging Face) LLM backend — runs at **$0 inference cost**

[View Repository →](https://github.com/rinshadpr477-cell/groundcrew)

---

#### 02 — Bank AI Calling Platform

Real-time AI-powered outbound calling platform for a banking client, live in production.

`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Redis` `BullMQ` `Twilio` `Gemini Live API` `Docker` `AWS`

* Built a real-time voice pipeline using **Twilio Media Streams** and **Google Gemini Live API** — 300+ calls/day, 82% call-answer rate
* Cut call-connect latency from 5s to 2.9s
* Designed **Redis + BullMQ** call-orchestration queues with RBAC auth and Razorpay billing — 1,000 transactions/month at 97% success
* Containerized and deployed on **AWS EC2** with NGINX, SSL/TLS, and GitHub Actions CI/CD
* Jest test coverage cut production incidents by 15% over 3 months

[View Repository →](https://github.com/rinshadpr477-cell/bank-ai-calling-platform)

---

#### 03 — AI Startup Guide

AI-powered application for exploring and analyzing startup opportunities.

`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Gemini`

* Built an AI-assisted startup discovery workflow
* Implemented full-stack application and database interactions
* Integrated AI capabilities into the application workflow

[View Repository →](https://github.com/rinshadpr477-cell/AI-STARTUP-GUIDE)

---

#### 04 — AI Refund Agent

AI-powered application focused on automating refund-related workflows.

`AI` `Next.js` `TypeScript` `Node.js`

* Designed an automated AI-driven refund workflow
* Integrated backend services with application logic
* Focused on workflow automation and reducing manual processing

[View Repository →](https://github.com/rinshadpr477-cell/AI-REFUND-AGENT)

---

#### 05 — LaundryNear

Full-stack service platform connecting customers, laundry shops, delivery agents, and administrators.

`React.js` `Node.js` `Express.js` `MongoDB` `JWT` `Razorpay`

* Designed and integrated RESTful APIs
* Optimized MongoDB schemas for efficient data storage and retrieval
* Implemented JWT authentication and role-based middleware
* Integrated Razorpay payment processing with transaction verification
* Designed and modeled **6+ MongoDB collections** using Mongoose
* Deployed frontend on **Vercel** and backend on **Render**

[View Repository →](https://github.com/rinshadpr477-cell/LaundryNear-Frontend)

---

### Security & DevOps

#### NPM Dependency Security

Security-focused work involving dependency auditing, vulnerability remediation, testing, and production build validation.

`Next.js` `npm` `Prisma` `Jest` `GitHub Actions`

* Audited project dependencies for security vulnerabilities
* Resolved vulnerable packages and dependency issues
* Validated Prisma client generation and production builds
* Executed automated tests after dependency changes

[View Repository →](https://github.com/rinshadpr477-cell/NPM_dependency)

---

### Experience

**Full Stack Developer — AIKING Software Solutions**
`June 2026 – Present`

Own two production platforms end-to-end (solo): a real-time AI voice pipeline for banking calls (Twilio + Gemini Live API) and a CSV-driven bulk SMS platform for logistics. Designed Redis/BullMQ job queues, RBAC auth, and Razorpay billing; containerized and deployed to AWS EC2 with NGINX and GitHub Actions CI/CD.

**Full Stack Developer Intern — Luminar Technolab**
`Sep 2025 – June 2026 · Kerala`

Independently shipped 10+ full-stack apps end-to-end, several with real-time features. Designed RESTful APIs and schemas for a service marketplace platform with Razorpay integration, and owned deployment — Dockerized services, NGINX/SSL, CI/CD pipelines.

---

### Connect

[LinkedIn](https://www.linkedin.com/in/rinshadpr477-cell/) · [GitHub](https://github.com/rinshadpr477-cell) · [Portfolio](https://portfolio-rinshad.vercel.app/) · [Email](mailto:rinshadpr477@gmail.com)

---

<sub>Building systems. Learning continuously. Shipping consistently.</sub>

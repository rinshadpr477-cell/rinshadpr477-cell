# RINSHAD PR
**Software Engineer · Real-Time, Distributed & AI Systems**

Software engineer with professional experience delivering production systems for banking and logistics clients[cite: 1]. Core focus on **Java 21 / Spring Boot 3**, **TypeScript / Node.js**, **Apache Kafka**, **PostgreSQL**, distributed transaction patterns, and applied AI (multi-agent systems, RAG pipelines)[cite: 1].

[LinkedIn](https://linkedin.com/in/rinshadpr477-cell) · [GitHub](https://github.com/rinshadpr477-cell) · [Portfolio](https://portfolio-rinshad.vercel.app/) · [Email](mailto:rinshadpr477@gmail.com)[cite: 1]

---

### Tech Stack

- **Languages:** Java (11/17/21), TypeScript, JavaScript (ES6+), Python, SQL[cite: 1]
- **Backend & Distributed Systems:** Spring Boot 3, Spring Data JPA, Hibernate, Node.js, Express.js, FastAPI, RESTful APIs, Microservices, Dependency Injection, SOLID Principles, WebSocket, JWT, OAuth 2.0, RBAC, Razorpay Integration[cite: 1]
- **Messaging & Real-Time:** Apache Kafka (KRaft), Transactional Outbox Pattern, Dead-Letter Queues (DLQ), Idempotent Consumers, Redis, BullMQ, Background Workers, Twilio Voice API & Media Streams, Google Gemini Live API[cite: 1]
- **Databases & Persistence:** PostgreSQL, MongoDB, Mongoose, Prisma ORM, Flyway, Indexing Strategies, Avoiding N+1 Queries, Schema Design, Batch Processing[cite: 1]
- **AI & ML Engineering:** Multi-Agent Systems, RAG Pipelines, Vector Databases (Qdrant), LLM Orchestration, Hugging Face, Sentence-Transformers, Evaluation Harnesses, Prompt Engineering[cite: 1]
- **DevOps, Cloud & Tooling:** Docker, Docker Compose, AWS EC2, AWS IAM, NGINX, SSL/TLS, GitHub Actions (CI/CD), Git, GitHub Copilot[cite: 1]
- **Testing:** JUnit 5, Mockito, Jest, Unit Testing, Jacoco[cite: 1]

---

### Featured Engineering Work

#### 01 — Enterprise Bank Communication & Collections Platform
Distributed, event-driven banking communication and recovery platform engineered on Spring Boot 3, Apache Kafka, and PostgreSQL for financial-grade reliability[cite: 1].
`Java 21` `Spring Boot 3` `PostgreSQL 16` `Apache Kafka (KRaft)` `Transactional Outbox` `Flyway` `Docker` `JUnit 5`[cite: 1]

- **Transactional Outbox & Idempotency:** Implemented an autonomous lock-free publisher (`FOR UPDATE SKIP LOCKED`) combined with consumer-side idempotency (`processed_events`) to eliminate dual-write hazards and guarantee exactly-once processing across 1,000+ simulated events[cite: 1].
- **Resilient Recovery Queues:** Built an automated multi-channel debt collections workflow leveraging exponential-backoff retries and Dead Letter Queues (DLQ) so failing notifications are isolated without message loss[cite: 1].
- **Concurrency & Compliance:** Leveraged PostgreSQL row-level locks for concurrent batch scheduling, PII masking (`CustomerMapper`), immutable audit logging (`audit_records`), and strict `BigDecimal` / `NUMERIC(19,4)` precision to prevent rounding discrepancies.
- **Security & Quality:** Secured with stateless JWT role-based access control (RBAC), Flyway-versioned database migrations, and a comprehensive JUnit 5/Mockito test suite achieving 70%+ coverage[cite: 1].

[View Repository →](https://github.com/rinshadpr477-cell/Enterprise-Bank-Communication-Platform)

---

#### 02 — Groundcrew — Autonomous RAG + Multi-Agent GitHub Issue Triage
Production-style RAG and multi-agent system (router, retriever, draft generator, critic) automating end-to-end issue classification and grounded resolution drafts[cite: 1].
`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `Qdrant` `Sentence-Transformers` `Hugging Face` `Ollama` `Docker` `GitHub Actions`[cite: 1]

- **High-Volume Retrieval:** Indexed and embedded 3,181 issues across a dataset of 5,318 real GitHub issues using Qdrant vector search[cite: 1].
- **Self-Refining Critic Loop:** Built an automated critic-agent revision loop achieving 96.7% auto-approval (29/30), escalating unverifiable claims directly to human review[cite: 1].
- **CI-Gated Evaluation:** Enforced a 72.5% router accuracy baseline and a 0.82 retrieval-relevance threshold on every commit via GitHub Actions to prevent prompt and model regressions[cite: 1].
- **Zero-Cost Inference:** Pluggable local (Ollama) or hosted (Hugging Face) LLM backends running at $0 inference cost.

[View Repository →](https://github.com/rinshadpr477-cell)

---

#### 03 — Bank AI Calling Platform
Live outbound AI-powered voice calling SaaS built for a banking client[cite: 1].
`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Redis` `BullMQ` `Twilio Media Streams` `Gemini Live API` `Docker` `AWS EC2`[cite: 1]

- **Voice Pipeline Optimization:** Built bidirectional real-time audio streams using Twilio Media Streams and Gemini Live API, cutting connection latency from 5s down to 2.9s across 300+ calls/day (82% answer rate)[cite: 1].
- **Queue Orchestration & Billing:** Engineered Redis and BullMQ job queues, RBAC authorization, and Razorpay subscription billing handling 1,000+ transactions/month at 97% success[cite: 1].
- **Deployment & Reliability:** Deployed to AWS EC2 using Docker, NGINX reverse proxying, and automated GitHub Actions CI/CD; added Jest coverage to reduce production incidents[cite: 1].

[View Repository →](https://github.com/rinshadpr477-cell/bank-ai-calling-platform)

---

#### 04 — AI Startup Guide
Full-stack AI-driven discovery engine for evaluating startup market viability and opportunities[cite: 1].
`Next.js` `TypeScript` `PostgreSQL` `Prisma` `Gemini API`

- Developed structured discovery workflows integrating Gemini AI with interactive querying.
- Implemented persistent database schemas and server actions using Prisma ORM.

[View Repository →](https://github.com/rinshadpr477-cell/AI-STARTUP-GUIDE)

---

#### 05 — LaundryNear
Full-stack on-demand service marketplace linking customers, local vendors, and logistics drivers[cite: 1].
`React.js` `Node.js` `Express.js` `MongoDB` `Mongoose` `JWT` `Razorpay`

- Modeled 6+ normalized Mongoose collections and optimized queries with strategic database indexing.
- Engineered role-based JWT middleware and Razorpay payment verification with automated webhooks.

[View Repository →](https://github.com/rinshadpr477-cell)

---

### Professional Experience

**Associate Software Engineer — AIKING Software Solutions**  
*June 2026 – Present · Pune*[cite: 1]
- Engineered two production platforms alongside a team of 5 developers, 1 senior developer, and 2 DevOps engineers: an AI voice calling platform (banking) and a bulk SMS platform (logistics)[cite: 1].
- Contributed to a real-time voice pipeline (Twilio Media Streams + Gemini Live API) serving 300+ calls/day at ~3s connect latency[cite: 1].
- Developed the backend for a CSV-driven bulk SMS platform featuring template personalization, batching, and idempotent retries (15,000+ messages/campaign at 98.5% delivery success, zero duplicates)[cite: 1].
- Built Redis/BullMQ job queues, RBAC auth middleware, Razorpay billing integrations, and PostgreSQL/Prisma schemas[cite: 1].
- Containerized microservices with Docker, configured NGINX reverse proxies, and automated builds using GitHub Actions CI/CD to AWS EC2[cite: 1].

**Full Stack Developer (MERN) — Luminar Technolab**  
*September 2025 – June 2026 · Kerala*[cite: 1]
- Built and shipped 10+ full-stack web applications on the MERN stack with mentors and teammates, incorporating real-time communication and clean architecture[cite: 1].
- Designed RESTful APIs and schemas for a service marketplace platform supporting 500+ registered users and Razorpay checkout[cite: 1].
- Engineered JWT and OAuth authentication flows with granular role-based access control[cite: 1].
- Deployed production services using Docker, NGINX with SSL/TLS termination, and CI/CD automation pipelines[cite: 1].

---

### Education

**B.Tech in Computer Science and Engineering**  
*Visvesvaraya Technological University (2021 – 2025) · Bangalore, India*[cite: 1]
- **Relevant Coursework:** Object-Oriented Programming (Java), Data Structures & Algorithms, Database Management Systems (RDBMS/SQL, Distributed DBs), Operating Systems[cite: 1].

---

<p align="center">
  <sub>Clean Code · Event-Driven Architecture · Resilient Distributed Systems</sub>
</p>

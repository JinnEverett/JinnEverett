# Vu Bao Minh — Backend Engineer

📧 jinneverett@gmail.com · 🐙 [github.com/JinnEverett](https://github.com/JinnEverett) · 📍 Hanoi, Vietnam

---

## About Me

I'm an Information Technology graduate from **Hanoi University of Science and Technology (HUST)** working as a **Backend Developer**. My foundation is **Java / Spring Boot** and **NestJS**, building backend systems on top of **PostgreSQL / MySQL** — from microservices and real-time data pipelines to serverless game backends on the edge.

I enjoy clean, well-structured architectures (Clean Architecture, CQRS, Hexagonal / Ports & Adapters) and event-driven systems. I make heavy use of **Claude Code** throughout my workflow to ship faster and with higher quality.

---

## Tech Stack

- **Languages & Frameworks:** Java, Spring Boot, Spring Cloud, NestJS, Bun, Python, JavaScript, ReactJS
- **Databases:** PostgreSQL, MySQL, MongoDB, Redis, Supabase
- **Messaging & Protocols:** Kafka, BullMQ, gRPC / Protocol Buffers, WebSocket, NTRIP
- **Cloud & DevOps:** Docker, Git, AWS (EC2, S3), Cloudflare Workers & Durable Objects
- **AI:** Claude Code, OpenAI, Google Gemini, Groq API

---

## Experience

**Backend Developer — Teaser Software** *(Mar 2026 – Present)*
- **Phong Nha-Ke Bang tourism management system** — NestJS/Bun backend with Clean Architecture + CQRS + Hexagonal Architecture; dual JWT auth flows (email/password for admins, OAuth via Zalo MiniApp SDK) and RBAC with CASL on PostgreSQL/TypeORM.
- **AI tour-booking chatbot** — swappable multi-provider design (OpenAI / Gemini / Groq behind a Port/Adapter) that extracts order details from natural conversation; SePay webhook payments processed asynchronously with BullMQ/Redis and the Outbox Pattern for reliable event delivery.
- **Night of Werewolves** — real-time backend for a Werewolf party-game companion app (6–30 players/room) on Cloudflare Workers + Durable Objects, with a server-authoritative state machine (night/day phases, voting, win detection) and Supabase RLS policies protecting players' secret roles.

**Backend Developer — LifeTex** *(Dec 2025 – Mar 2026)*
- Built integration middleware with WSO2 Micro Integrator bridging legacy local government systems to a centralized national platform — 30+ API proxy and transformation flows.
- JSON/XML transformation and routing across reporting, document management, and administrative procedure domains.

**Backend Intern — Viettel VDT2025** *(Apr 2025 – Jul 2025)*
- Built a real-time chat application with Spring Boot and WebSocket, owning message routing and backend logic.
- Practiced enterprise workflows: Git branching, Docker containerization, and code review.

---

## Featured Projects

### [Microservices E-commerce System](https://github.com/JinnEverett/Micro-Ecommerce) *(May 2026 – Present)*
`Spring Boot` · `Spring Cloud` · `gRPC` · `Kafka` · `PostgreSQL` · `Docker`

An e-commerce platform built across 9 independent microservices (auth, user, product, order, payment, notification, and more).

- Spring Cloud Gateway for routing and JWT authentication with asymmetric RSA (RS256)
- Internal service-to-service calls over gRPC + Protocol Buffers
- Event-driven order flow with Kafka: `order-service` publishes `ORDER_CREATED`, `payment-service` processes it and publishes `PAYMENT_SUCCESS`

---

### Real-Time GNSS Quality Monitoring System *(Nov 2025 – Mar 2026)*
`Spring Boot` · `Kafka` · `WebSocket` · `NTRIP` · `AWS EC2` · `ReactJS`

A monitoring platform for GNSS signal data streamed in real time via the NTRIP protocol.

- Kafka buffers high-throughput streams between a Python client and the backend
- Raw signal data converted to spectrum images and fed to AI models to detect anomalies and classify jamming types
- Automated alerts on anomaly detection, pushed over WebSocket

---

## Education

**Hanoi University of Science and Technology (HUST)**
Information Technology — Computer Engineering (IT2) · GPA: 3.4 / 4.0 · Oct 2021 – Mar 2026

**TOEIC:** 685 (Listening & Reading)

---

*Always building. Always learning.*

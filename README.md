<h1 align="center">Vu Bao Minh</h1>

<p align="center">
  <b>Backend Engineer</b> · Hanoi, Vietnam<br/>
  <a href="mailto:jinneverett@gmail.com">jinneverett@gmail.com</a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,spring,nestjs,ts,postgres,kafka,redis,docker&perline=8" alt="Java, Spring, NestJS, TypeScript, PostgreSQL, Kafka, Redis, Docker" />
</p>

I build the part of a product users never see but always depend on: **APIs, data, and the workflows between services**. I care about systems that stay correct under retries, concurrency and failure, and about code a team can still change a year later. Java/Spring Boot and NestJS are my main tools; I use Claude Code daily to move faster without lowering the bar.

## What I work on

| Area | What I build |
|---|---|
| **API & architecture** | REST and gRPC/Protobuf services; Clean Architecture, CQRS and Hexagonal (ports and adapters); an API gateway with Spring Cloud Gateway |
| **Data** | PostgreSQL (TypeORM, Row Level Security), MySQL, MongoDB, Redis; schemas designed around access patterns and integrity |
| **Async & event-driven** | Kafka-based sagas, BullMQ/Redis job queues, the Outbox pattern for reliable delivery, idempotent payment webhooks |
| **Real-time** | WebSocket and Cloudflare Durable Objects; server-authoritative state machines for multiplayer rooms of 6–30 players |
| **Security** | JWT (including RS256), two auth flows side by side (admin login and OAuth via Zalo MiniApp), RBAC with CASL, secret data protected at the database layer |
| **AI in the backend** | A provider-agnostic LLM layer (OpenAI, Gemini, Groq behind one port) that turns chat into structured orders |
| **Delivery** | Docker, Git workflows and code review, AWS (EC2, S3) |

## Where I've done it

**Teaser Software** · Backend Developer · *Mar 2026 – now*

- **Phong Nha-Ke Bang tourism platform** — backend for a national-park management system on NestJS/Bun: Clean Architecture with CQRS and Hexagonal design, two JWT flows (admin login and Zalo MiniApp OAuth), and RBAC with CASL on PostgreSQL/TypeORM.
- **AI tour-booking chatbot** — OpenAI, Gemini and Groq swappable behind a port/adapter; extracts order details from natural conversation; SePay payment webhooks processed through BullMQ/Redis with the Outbox pattern for reliable event delivery.
- **Night of Werewolves** — real-time backend for an offline Werewolf party-game companion app (6–30 players per room) on Cloudflare Workers and Durable Objects: a server-authoritative state machine drives the whole game (night/day phases, voting, win detection); Supabase Row Level Security protects secret roles, with Supabase Realtime for the lobby and a dedicated Durable Object WebSocket during play.

**Earlier and personal**

- **Viettel Digital Talent 2025** · Backend Intern · *Apr – Jul 2025* — a real-time chat application on Spring Boot and WebSocket.
- Personal: [**Micro-Ecommerce**](https://github.com/JinnEverett/Micro-Ecommerce), 9 Spring Cloud microservices with gRPC and a Kafka order saga. Also a real-time GNSS signal-quality monitoring pipeline (NTRIP, Kafka, anomaly and jamming detection).

## Education

**Hanoi University of Science and Technology** — B.Eng. Information Technology (Computer Engineering), GPA 3.4 / 4.0, 2021 – 2026 · TOEIC 685

Currently deepening PostgreSQL performance, NestJS and system design.

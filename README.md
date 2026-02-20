# Hey, I'm Rushikesh Bhavsar 👋

**Backend Systems Engineer | LeetCode Knight | Distributed Systems**

I build resilient, high-throughput backend services and real-time systems. My focus is on event-driven microservices, concurrency, and fault-tolerant architectures using **Go, gRPC, and Kubernetes**.

## What I Architect
- ⚙️ **Distributed Systems** – Microservices, Message Queues (RabbitMQ), RPC frameworks
- ⚡ **Real-Time Infrastructure** – WebSockets, event pipelines, low-latency streaming
- 🧠 **Algorithmic Problem Solving** – Top 4.6% globally on LeetCode
- 📊 **Observability** – Distributed tracing (OpenTelemetry, Jaeger), system metrics

## Tech Stack
- **Core Languages:** Go, C++, Java, TypeScript, SQL
- **Backend & Systems:** gRPC, Protocol Buffers, RabbitMQ, Docker, Kubernetes
- **Web & Databases:** Node.js, Next.js, MongoDB (Indexing), Prisma, REST APIs
- **Observability:** OpenTelemetry, Jaeger

## Featured Architecture

### 1. 🚗 RideSync – Cloud-Native Ride-Sharing Platform
**Tech:** Go | gRPC | RabbitMQ | Kubernetes (GKE) | Docker | Jaeger

Architected an event-driven microservices platform handling high-performance inter-service communication.
- Engineered a fault-tolerant message pipeline across 8+ distributed queues using RabbitMQ.
- Verified zero message loss under node failure via a 3-retry Dead Letter Queue (DLQ) mechanism.
- Implemented end-to-end distributed tracing using OpenTelemetry and custom AMQP context propagation.

[View Architecture & Source](https://github.com/RushikeshBhavsar3605/RideSync) 

### 2. 📝 Bloks – Real-Time Collaborative Editor
**Tech:** Next.js | TypeScript | Socket.IO | Docker | MongoDB

A production-ready collaborative editor sustaining **100 edits/sec** with p90 latency <350ms.
- Reduced database writes by ≥95% by formally proving and implementing a debounced persistence algorithm (O(1) per 2s window).
- Architected a 4-layer RBAC enforced consistently at WebSocket, API, and UI layers.
- Load-tested with a custom harness to simulate target concurrent edit rates.

[Live Demo](https://bloks.onrender.com/) · [Source Code](https://github.com/RushikeshBhavsar3605/Bloks)

### 3. 💬 Converge – Real-Time Messaging Infrastructure
**Tech:** Next.js | TypeScript | Socket.IO | MongoDB | Prisma

A low-latency chat system built for high-throughput message delivery.
- Achieved low-latency delivery via 10-message batching and cursor-based pagination.
- Designed permission-aware Server→Channel DM architecture with 3-layer RBAC to prevent data leakage.
- Optimized query performance using indexed MongoDB schemas for scalable authorization boundaries.

[Live Demo](https://converge-chat.onrender.com/) · [Source Code](https://github.com/RushikeshBhavsar3605/Converge)

## Proof of Work (Competitive Programming)

🏆 **LeetCode Knight Badge** (Rating: 1881)
- **Global Rank:** 37,818 / 809,286 (Top 4.67%)
- **Volume:** 750+ problems solved with a 350+ day active streak
- **Contest Peak:** Biweekly Contest #465 Global Rank 735 (All-India Rank 263)

📂 **[Explore my Algorithmic Problem Solving Vault](https://github.com/RushikeshBhavsar3605/Algorithmic-Problem-Solving)** *(Link your DSA repo here)*

## Currently Deep-Diving Into
- **Distributed Consensus:** Exploring Raft implementation details.
- **Database Internals:** Storage engines, B-Trees, and write-ahead logging (WAL).

## Let's Connect
[![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/rushikesh-bhavsar-swe/)
[![LeetCode](https://img.shields.io/badge/LeetCode-%23FFA116?style=flat&logo=leetcode&logoColor=white)](https://leetcode.com/u/rushikesh-bhavsar/)
[![Portfolio](https://custom-icon-badges.demolab.com/badge/Portfolio-000000?style=flat&logo=globe&logoColor=white)](https://rushikesh-bhavsar.vercel.app/)

> "Understand the system constraints first, identify the network bottlenecks, then architect the solution."

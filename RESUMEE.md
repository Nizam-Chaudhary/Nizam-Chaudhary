# Nizam Chaudhary

**Software Engineer** 

📍 Valsad, Gujarat, India
📞 +91 9313234732
✉️ ChaudahryNizam10@gmail.com

🔗 [LinkedIn](https://linkedin.com/in/nizam-chaudhary-b092202b0) | 🔗 [GitHub](https://github.com/Nizam-Chaudhary)

---

### 📝 Professional Summary
- Software Engineer with 1.5+ years of experience specializing in Full Stack Development, high-performance backend systems, and distributed architectures.

- Technical Expert in Node.js, TypeScript, and React, with a proven track record of successfully migrating monolithic systems to scalable Microservices.

- Fintech Specialist with deep expertise in Escrow transaction platforms, secure banking proxies, and digital signature integrations (UAEPASS).

- Systems Architect experienced in IoT data ingestion via custom TCP servers and implementing robust DevOps/monitoring via Kubernetes and the LGTM stack.

---

### 🛠 Technical Skills

* **Backend:** Node.js, Bun, NestJS, Fastify, Platformatic, Hono, Express, Microservices, Monorepos, Effect, ElysiaJS
* **Frontend:** React, Next.js, TanStack (Router, Query, Form), Shadcn UI, Tailwind CSS, Ant Designs, SASS Css, Zustand
* **Databases & Messaging:** PostgreSQL, MySQL, MongoDB, Redis, Apache Kafka
* **Infrastructure & DevOps:** Linux, Docker, Kubernetes (EKS), AWS (S3, EC2, SES, CloudFront), GitHub Actions, OpenTelemetry (LGTM Stack)
* **Tooling:** TypeScript, Zod, Drizzle, Prisma, Biome, ESLint, pnpm

---

### 💼 Professional Experience

#### **IT IDOL TECHNOLOGIES** | *Software Engineer* | **Aug 2025 – Present**

* **Fintech & Blockchain:** Integrated 3rd-party blockchain APIs into an Escrow system for real-time data synchronization across services via Apache Kafka.
* **Distributed Systems:** Engineered a high-availability Job Scheduler using Redis expiry notifications and Kafka to handle recurring and one-time tasks with distributed locking.
* **Observability:** Implemented full-stack monitoring using OpenTelemetry (Grafana, Loki, Tempo, Prometheus) to ensure production stability and rapid debugging.
* **Core Banking Infrastructure:** Developed internal fund transfer APIs and Bank Adapters to maintain a consistent interface across disparate 3rd-party banking providers.

#### **IT IDOL TECHNOLOGIES** | *Associate Software Engineer* | **Aug 2024 – Aug 2025**

* **IoT & Networking:** Architected a custom TCP server for real-time hardware communication, processing location and status data for device tracking.
* **Geographical Logic:** Implemented Geofencing alerts and automated trip tracking logic based on real-time device movement.
* **Data Engineering:** Authored complex PostgreSQL queries using nested joins and unions for granular E-commerce business intelligence reporting.

---
### 🚀 Projects & Architecture

#### **1. Escrow Transaction Platform (Flagship Project)**

*A comprehensive fintech solution involving a transition from Legacy to Microservices.*

**A. Microservices Rewrite (Current)**

* **Tech:** Platformatic (Fastify), Kubernetes, MySQL, MongoDB, Kafka, Redis, Docker.
* **Escrow Service:** Managed full transaction lifecycles, document verification, and automated dispute/refund handling.
* **Job & Webhook Management:** Built a resilient retry system for failed client notifications and transfer failures using the centralized job scheduler.
* **Data Access:** Developed a custom MySQL repository pattern to optimize complex data retrieval and filtering.

**B. Bank Service (Shared Infrastructure)**

* **Tech:** Node.js, Express, MongoDB, GPG Encryption, MTLS.
* **Architecture:** Serves both legacy and microservice layers. Migrated v1 synchronous transfers to v2 asynchronous processing with secure HMAC-authenticated webhooks.
* **Bank Proxy:** Designed a secure gateway for 3rd-party banks handling MTLS and payload encryption/decryption via GPG keys.

**C. Legacy Platform Service (Production Reference)**

* **Tech:** NestJS, PostgreSQL, Redis, Mongodb, Swagger.
* **Impact:** Integrated UAEPASS for digital signatures and vaulting to secure user onboarding and transactions.

**D. Frontend Ecosystem (Admin & User Interface)**

* **Tech:** React, TanStack Suite, Monorepo Architecture, Shadcn UI, Biome.
* **Role:** Lead Frontend Developer. Optimized performance via TanStack Query caching and preload-on-hover logic. Implemented complex transaction history views with milestone tracking.

#### **2. Locshark (IoT Tracking)**

* **Tech:** Node.js, Express, MongoDB, Stripe, TCP Server.
* **Impact:** Built an end-to-end device management platform. Created the ingestion layer for device status via TCP and integrated Stripe for subscription-based access.

#### **3. E-commerce**

* **Tech:** Node.js, PostgreSQL, Stripe, Sequelize.
* **Impact:** Developed a robust RBAC permission system and an automated shipping module for delivery partner assignment based on volumetric packaging calculations.

---

### 🎓 Education

* **Bachelor of Computer Applications (BCA)**
* VNSGU, Class of 2024 | **GPA: 9.3/10.0**

# Hi, I'm Arup Halder

I build **AI applications and backend services** with Python and Java, focusing on model evaluation, reliable APIs, and data correctness.

Master of Applied Computer Science student at **Dalhousie University**, based in **Halifax, Canada**. Open to **junior AI engineering and backend software engineering roles in Canada**.

[Portfolio](https://beaprogram.github.io/) · [LinkedIn](https://www.linkedin.com/in/arup-halder) · [Email](mailto:aruphalder4602@gmail.com)

## Selected projects

### [OceanSight — applied computer vision](https://github.com/beaprogram/OceanSight)
Marine-debris detection with video-disjoint data splits, model comparison, and a FastAPI inference service. Compared FP32 and INT8 ONNX deployment: model files shrink from **12.14 MB to 3.35 MB**, with accuracy and CPU-latency tradeoffs documented.

**Python · PyTorch · ONNX Runtime · FastAPI**  
[Run the demo](https://github.com/beaprogram/OceanSight#quick-start-for-reviewers) · [Measured results and limitations](https://github.com/beaprogram/OceanSight/blob/main/docs/RESULTS.md)

### [DecisionRail — reliable Java backend](https://github.com/beaprogram/Decision-Rail)
A synthetic payment system built around safe retries, concurrent requests, and balanced accounting. Includes durable idempotency, a transactional outbox, ordered Kafka delivery, and integration tests for broker outages and recovery.

**Java · Spring Boot · PostgreSQL · Kafka**  
[Architecture](https://github.com/beaprogram/Decision-Rail/blob/main/docs/architecture.md) · [Verification evidence](https://github.com/beaprogram/Decision-Rail/blob/main/docs/verification.md) · [Recorded walkthrough](https://github.com/beaprogram/Decision-Rail/releases/tag/v0.10.0)

### [Homebase — retrieval-augmented housing search](https://github.com/beaprogram/Homebase)
A housing-search application connecting a React interface and Spring Boot API to a Python retrieval service. Uses sentence embeddings, PostgreSQL/pgvector, and Claude to answer questions using retrieved listing context.

**Python · FastAPI · pgvector · Spring Boot · React**  
[AI service](https://github.com/beaprogram/Homebase/tree/main/ai-service) · [API tests](https://github.com/beaprogram/Homebase/blob/main/ai-service/app/tests/test_ask.py)

### [HFX Connect — community-services backend](https://github.com/beaprogram/hfx-connect)
An actively developed Halifax services directory with PostGIS nearby search, authenticated sessions, and moderated community contributions. Database integration tests cover authorization, ownership, and concurrent moderation decisions.

**Java · Spring Boot · PostgreSQL/PostGIS · Next.js · Testcontainers**  
[API documentation](https://github.com/beaprogram/hfx-connect/blob/main/docs/api/README.md) · [Integration tests](https://github.com/beaprogram/hfx-connect/tree/main/backend/src/test/java/com/hfxconnect)

## More engineering work

- **[Agent Platform](https://github.com/beaprogram/agent-platform)** — AWS coursework: a Python agent loop, document ingestion and semantic retrieval, with Lambda, DynamoDB, Cognito, and Terraform.
- **[Joule Ledger](https://github.com/beaprogram/Joule-Ledger)** — Python/SQLite pipeline and Streamlit dashboard for 2022–2024 energy-program actuals, with source traceability and data validation.

## Tools I use

**AI & backend:** Python, FastAPI, Java, Spring Boot, REST APIs  
**Data:** PostgreSQL, pgvector, PostGIS, SQL  
**Testing & delivery:** pytest, JUnit, Testcontainers, Docker, GitHub Actions  
**Interfaces:** TypeScript, React, Next.js

My project documentation includes setup instructions, design decisions, tests, and known limitations so you can inspect the engineering behind each project.

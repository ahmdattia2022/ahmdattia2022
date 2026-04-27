# Ahmed Attia — Full Stack Software Engineer

**Backend-focused · .NET + Angular · Cairo, Egypt**

4+ years building and shipping production .NET systems. Currently at [Appenza Studio](https://www.linkedin.com/company/appenza/) working on AI-powered EdTech platforms for the Egyptian Ministry of Education.

📧 official.ahmed.attia@gmail.com · [LinkedIn](https://linkedin.com/in/ahmed-attia-dev) · [Portfolio](https://ahmed-attia-portfolio.pages.dev) · [WhatsApp](https://wa.me/201027495862)

---

## Stack

**Primary:** C#, .NET 8, ASP.NET Core Web API, Entity Framework Core, SQL Server, LINQ  
**Frontend:** Angular, TypeScript, HTML/CSS, Bootstrap  
**Databases:** SQL Server · MySQL · PostgreSQL · MongoDB · Redis  
**Cloud:** Azure (Container Apps, ACR, Blob Storage, OpenAI, Text-to-Speech, AI Search) · AWS S3 · Docker  
**DevOps:** GitHub Actions · Azure DevOps · IIS · Azure CLI  
**Architecture:** Clean Architecture · N-Layer · Repository + Unit of Work · SOLID · Dependency Injection  
**Auth:** Microsoft Identity · JWT · OAuth 2.0 · IdentityServer4 (integrated)  
**Other:** Hangfire · SignalR · Python (Flask-RESTX, aiohttp) · Swagger/OpenAPI  

---

## Work

### Appenza Studio · Mid Level Full Stack Software Engineer · Nov 2023 – Present

#### Faheem AI — Adaptive Learning Platform · [faheem-ai.app](https://www.faheem-ai.app/)
Ministry of Education Egypt · ~10K students in pilot

Primary backend developer. Systems I owned end-to-end:

**Adaptive learning chat** — 5-state machine persisted per session in SQL Server. Azure OpenAI with session-scoped conversation history. RAG retrieval via Azure AI Search grounding responses in curriculum content.

**Subscription system** — bundle and subject grouping, semester-scoped one-time voucher codes, role-based content access control, and the admin panel to manage it all. Designed independently from business requirement to production.

**Platform-wide audio narration** — Azure Text-to-Speech integration, Blob Storage for audio delivery, ~20 API endpoints refactored across lessons, units, and capsules to support playback.

**Cross-system sync service** — scheduled job bridging Faheem (SQL Server) and Question Bank (MySQL) with bidirectional ID mapping. Keeps content consistent across two independent production databases.

**Azure infrastructure** — managed via Azure CLI across DEV, STAG, and PROD. Container Apps, ACR, Blob Storage, Redis, PostgreSQL. IIS deployments for multiple backend services.

**Junior mentoring** — designed the image and voice upload feature architecture end-to-end, mentored 2 junior developers through implementation, reviewed all pull requests to production.

---

#### Question Bank Platform · Sole Backend Developer
Production · private platform

- 30+ REST APIs in .NET 8 — question creation, quiz management, admin operations, student quiz sessions
- Designed ~40% of the database schema
- JWT auth and role-based authorization via Microsoft Identity
- Angular admin panel and student quiz portal, isolated from an existing codebase

---

#### Madrasatna Plus — National E-Learning Platform · [madrasetnaplus.eg](https://madrasetnaplus.eg/)
1M+ users

- Integrated Question Bank with Madrasatna Plus in 2 weeks: backend-to-backend API, iframe-embedded quiz player, result callback API
- Prototyped Elasticsearch (ELK stack) content search — Logstash + SQL Server input
- Prototyped multi-quality video streaming (AWS Elemental MediaConvert) and bulk S3 download via .NET AWS SDK
- Resolved production bugs across .NET backend and Angular/Ionic mobile clients

---

### ELSquare (ESquares GenieSys) · Backend .NET Developer · Mar 2023 – Nov 2023

Real-time factory monitoring for Coca-Cola (5 factories) and EIPICO:

- SignalR dashboards processing ~1,350 reads/min from 450 IoT sensors — production KPIs, energy, water, CO2
- SQL Server stored procedures, CTEs, and views for per-shift aggregations and KPI computation
- SAP integration and mobile barcode scanner APIs for production line weight tracking
- Background jobs for automated factory data aggregation

---

### Watanya Company · Junior Software Developer · Jan 2022 – Dec 2022
*(Military Service)*

Windows Forms management system for shop rental contracts and utilities billing — electricity, water, rent. ADO.NET + SQL Server. RDLC reports for contract documentation. Written entirely by hand, no AI tooling.

---

## Education

**BSc Computer Science** — Faculty of Computer and Information, Menoufia University · 2021

---

## Open to

Full-time backend or fullstack engineer roles (remote or Cairo) at a structured company with clear role definitions. Mid-level or growing toward senior .NET.


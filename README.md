# Ahmed Attia — Full Stack Software Engineer

Backend-focused · **.NET 8 + Angular** · Cairo, Egypt · 4+ years

Currently at [Appenza Studio](https://www.linkedin.com/company/appenza/) — primary backend developer on AI-powered EdTech platforms for the Egyptian Ministry of Education, reaching 1M+ users.

---

### What I build

**Backend (primary):** Production .NET 8 / ASP.NET Core Web APIs following Clean Architecture, N-Layer, Repository + Unit of Work, SOLID. EF Core data layers with SQL Server stored procedures, CTEs, and views for complex aggregations. JWT auth and role-based authorization via Microsoft Identity. Also built .NET Framework desktop apps (Windows Forms, WPF) in production environments.

**AI integration:** Azure OpenAI + Azure AI Search for RAG pipelines. Azure Text-to-Speech integrated into platform-wide narration. Worked inside production Python aiohttp AI proxy services — moved prompt configuration from hardcoded files to database, eliminating redeployments.

**Cloud & DevOps:** Azure Container Apps, ACR, Blob Storage, Redis, PostgreSQL — managed via Azure CLI across DEV, STAG, and PROD. Docker, GitHub Actions, Azure DevOps CI/CD, IIS deployments.

**Real-time & integration:** SignalR live dashboards (built for Coca-Cola and EIPICO industrial monitoring — ~1,350 IoT reads/min from 450 sensors). Converted SQL views to stored procedures and optimized queries for real-time IoT reads — **10× faster** per-shift aggregation; these SPs back SignalR for live current-shift reads. Cross-system sync services bridging independent SQL Server and MySQL databases. SAP and barcode scanner integrations.

**Frontend (secondary):** Angular + TypeScript + HTML/CSS/JavaScript/Bootstrap — admin panels, student portals, lazy modules, typed forms. ASP.NET Core MVC for server-rendered views. Not my primary focus but I ship it.

---

### Things I've shipped

- **5-state adaptive learning chat** — state machine persisted in SQL Server, Azure OpenAI with session-scoped history, RAG retrieval via Azure AI Search over Egyptian curriculum content
- **Full subscription + voucher system** — bundle grouping, semester-scoped one-time codes, role-based access, admin panel — designed from business requirement to production independently
- **Platform-wide TTS narration** — Azure Text-to-Speech + Blob Storage across ~20 API endpoints refactored for audio playback
- **30+ REST APIs** as sole backend developer for a quiz platform now embedded in a 1M+ user national e-learning platform
- **Real-time factory dashboards** for Coca-Cola (5 factories) and EIPICO — SignalR + converted SQL views to stored procedures, optimizing real-time IoT reads **10× faster**; SPs called directly for live current-shift reads, SAP integration
- **Cross-database sync service** — bidirectional ID mapping between two independent production databases on a scheduled job

---

### Stack

| Area | Technologies |
|---|---|
| **Backend** | C#, .NET 8, .NET Framework, ASP.NET Core, ASP.NET Core MVC, EF Core, SQL Server, LINQ, Hangfire, Windows Forms, WPF |
| **Databases** | SQL Server · MySQL · PostgreSQL · Redis · MongoDB |
| **Architecture & Patterns** | Clean Architecture · N-Layer · Repository + UoW · SOLID · DI · Singleton · MVVM · Factory · Builder · Observer |
| **Auth** | Microsoft Identity · JWT · OAuth 2.0 · IdentityServer4 (integrated) |
| **Cloud** | Azure (Container Apps, ACR, Blob Storage, OpenAI, AI Search, TTS) · AWS S3 · Docker |
| **DevOps** | GitHub Actions · Azure DevOps · IIS · Azure CLI |
| **Frontend** | Angular · TypeScript · HTML · CSS · JavaScript · Bootstrap |
| **Python** | Flask-RESTX · SQLAlchemy · aiohttp |
| **Real-time** | SignalR · cross-platform API integration · webhook/callback APIs · SAP · IoT |
| **Dev Tools** | Git · GitHub Copilot · Cursor · Claude Code · Postman · Swagger |

---

📧 [official.ahmed.attia@gmail.com](mailto:official.ahmed.attia@gmail.com) · [LinkedIn](https://linkedin.com/in/ahmed-attia-dev) · [Portfolio](https://ahmed-attia-portfolio.pages.dev) · [WhatsApp](https://wa.me/201027495862)

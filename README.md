<div id="header" align="center">
  <h1>Hi, I'm Mohammad Ghabin</h1>
  <p><b>Software Engineer II, Microsoft (via ASAL Technologies)</b><br>
  I design, build and own C#/.NET services on Azure: backend, platform, reliability and identity. Full-stack with React and TypeScript.</p>

  <div id="badges">
    <a href="https://www.linkedin.com/in/mohammad-ghabin/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="mailto:mghabin98@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
    </a>
  </div>
</div>

---

### 👨‍💻 About Me

Software Engineer II, Microsoft (via ASAL Technologies). 5 years on Microsoft products, most recently Microsoft 365 tools inside school learning platforms and, before that, AI-powered meeting preparation for bankers. Backend and cloud engineer, full-stack with React and TypeScript: I design, build and own production .NET services on Azure end to end, from high-level and low-level design and C#/.NET code to CI/CD, infrastructure as code, deployment, traffic, telemetry, monitoring and on-call, plus the React screens on top. I use GitHub Copilot and AI coding agents every day to ship faster, and check their work against tests and telemetry.

**Open to** Senior Software Engineer roles in backend, platform and cloud, and Senior Full-Stack Engineer roles (.NET, React): remote from Ramallah, Palestine (UTC+2/+3), as a contractor or through an employer of record, or relocation with visa sponsorship.

How I work: I write the design and review it with the team before I build, release behind feature flags and staged rollouts, and check telemetry in every production region before I call a change done.

- 🏗️ **Current:** I build and own the production backend of **Microsoft 365 LTI**, which lets teachers and students use Microsoft 365 tools inside their school's learning platform. It works with any learning platform that supports the LTI 1.3 standard, including Canvas, Blackboard, Brightspace (D2L), Schoology and Moodle, and is used by hundreds of thousands of students and teachers every month. That backend merged six education tools into one platform, live in six months and adopted by close to a thousand education organisations in its first two months.
- 🛠️ **Cloud and delivery:** I ship LTI service changes on AKS (Helm) in several production regions, with multi-region Azure DevOps release pipelines, Application Gateway, Traffic Manager and CDN, and ran the classic service on Service Fabric until its retirement
- ⚡ **Reliability:** Since July 2026, I own the reliability and performance of the LTI services and clients (hundreds of millions of requests a month) and I'm on call, with 35 production Grafana dashboards, OpenTelemetry instrumentation and end-to-end correlation ids
- 🖥️ **Frontend:** I build React and TypeScript screens on my own APIs (Fluent UI, MSAL.js, Playwright tests): class meetings with a rich text editor, OneDrive file picker limits, a pop-out student viewer and course migration screens
- 🤖 **AI-native:** I use GitHub Copilot (CLI and agent mode) and AI coding agents every day for code, tests, reviews, pipelines and docs, and I wrote AI agent skills that encode my team's telemetry and dashboard conventions. I build AI features too: for **Financial Meeting Prep**, a Microsoft Teams app made with **LSEG** that helped bankers prepare for client meetings (retired in October 2025), I designed, built and owned the news service around Azure OpenAI summaries (with source links), with Semantic Kernel
- 🔧 **Core:** C#/.NET 6 to 10, ASP.NET Core, Azure, Docker, Kubernetes, Helm. Also TypeScript and React, Python, Java and SQL, with Cosmos DB, SQL Server, PostgreSQL, MongoDB and Redis
- 🔐 **Security:** Secure sign-in with OAuth 2.0, OpenID Connect and Microsoft Entra ID, plus shared token validation, least-privilege permissions, and certificate and signing-key rotation
- 👥 **Mentorship:** Wrote a backend training plan and mentored six ASAL university interns across two cohorts, from interview to final demo, with 90% of features delivered on time

<details>
<summary>More about me &rarr;</summary>
<br>

- 📡 **Observability:** OpenTelemetry, Grafana, Kusto/KQL, Application Insights, monitors and alerts, on-call
- 🚀 **Full-stack:** React, TypeScript, Fluent UI, HTML and CSS at work; React Native and NestJS on side projects. I take a feature from the API to the screen
- 📊 **Background:** Bachelor's in Computer Engineering, Birzeit University (Accounting minor requirements completed)

</details>

---

### 🔭 What I'm Working On

My professional work lives in company-internal repositories, so it is not public. The public repositories here hold personal projects, learning experiments and reusable samples. Start with these:

- [entra-auth-patterns-dotnet](https://github.com/mghabin/entra-auth-patterns-dotnet): Microsoft Entra ID auth in .NET 10 with no client secrets (Managed Identity and federated credentials), deployed to Azure Container Apps with Bicep and GitHub Actions
- [refund-autopay-race](https://github.com/mghabin/refund-autopay-race): a store refund racing an autopay charge, in Python. Version-checked saves, idempotency keys and a test of every order of the steps show nobody is charged twice
- [platform-doctrine](https://github.com/mghabin/platform-doctrine): which cloud and building blocks a multi-product organisation should start on, with decision records
- Companion guides: [dotnet-engineering-guide](https://github.com/mghabin/dotnet-engineering-guide) and [infra-engineering-guide](https://github.com/mghabin/infra-engineering-guide)

---

<details>
<summary><b>📌 Highlights: the detail behind each area</b></summary>
<br>

| | |
|---|---|
| 🏗️ **Production Services** | I design, build and run production .NET services end to end: more than ten services and components across two product groups since 2023, from high-level and low-level design documents to APIs, background jobs, data models, tests, pipelines and releases. Built and own the production backend that merged six Microsoft education tools into Microsoft 365 LTI (Teams meetings on Microsoft Graph, assignments, OneDrive files, roster sync, settings), live in six months and adopted by close to a thousand education organisations in its first two months |
| 🛠️ **Cloud Infrastructure & Delivery** | Ship LTI service changes on AKS (Helm) in several production regions, with multi-region Azure DevOps release pipelines, Application Gateway, Traffic Manager and CDN. Ran the classic service (the older OneDrive LTI tool) on Service Fabric, then retired it in every production region, routing its traffic to a retirement page. Architected and own a reusable CDN deployment pattern for very large files, reused by other Microsoft Education apps, and fixed the .NET 10 build and release path of an internal operations tool |
| ⚡ **Observability & Reliability** | I own the reliability and performance of the LTI services and clients (hundreds of millions of requests a month): I present LTI reliability in the monthly service review and take on-call. Built 35 production Grafana dashboards, OpenTelemetry instrumentation, operation-level success tracking and end-to-end correlation ids, work my engineering manager credited with a significant reduction in alert noise. Root-caused a migration timeout on very large courses, and caught a broken production deployment before any alert fired. The core LTI launch service ran at five-nines availability through the 2026 back-to-school peak |
| 🔐 **Identity & Integrations** | Built secure sign-in features with OAuth 2.0, OpenID Connect and Microsoft Entra ID for more than a thousand education organisations, including launches that keep working when browsers block third-party cookies. LTI 1.3 and LTI Advantage (roster sync and deep linking) on any LTI 1.3 platform, with platform-specific handling for Canvas, Blackboard, Brightspace and Schoology, plus Microsoft Graph and LSEG partner APIs. Led a signed-token design for launch content too large for a URL through security review to a kill-switch release. Shared token validation, least-privilege permission reviews, certificate rotation, Secure Future Initiative work and a .NET 8 upgrade with region-by-region signing-key rotation. Roster paging and safeguards for very large classes |
| 🔄 **Data & Migration** | Cosmos DB, SQL Server, PostgreSQL, MongoDB, Redis, Azure Tables, Blob storage, Service Bus and Event Hubs. Architected and built the course migration engine: background jobs with saved progress and resume, Canvas rate limits, admin bulk migration, and one class group per course, even when a teacher and students launch it at the same moment (an ETag-guarded lease in Cosmos DB). Fixed its timeout incident so courses with 20,000+ links could move. Repaired more than a thousand courses split across two sites after a full dry run and a small pilot run (canary) |
| 🤖 **AI** | Use GitHub Copilot (CLI and agent mode) and AI coding agents every day to ship faster, and wrote AI agent skills, merged with a dashboard panel library and telemetry contract docs, that encode my team's telemetry and dashboard conventions. Built backend services for **Financial Meeting Prep**, a Microsoft Teams app made with **LSEG** for bankers: designed, built and owned the news service around Azure OpenAI summaries (with source links), plus Semantic Kernel work, a provider-neutral data layer with a mock LSEG service, Polly resilience and a shared .NET library, and wrote the Bicep for its Azure environments. Reached 95% test coverage with 200+ tests and cut deployments from 26 to 15 minutes by promoting the build already tested in the pull-request pipeline instead of rebuilding it |
| 🖥️ **Full-stack** | Built React and TypeScript features of Microsoft 365 LTI end to end, with the APIs behind them: meeting series and cancellation with a rich text editor, OneDrive file picker limits, a pop-out assignment viewer for students and the course migration screens, with Fluent UI, MSAL.js and Playwright end-to-end tests |
| 🚀 **Startup** | Co-founded Watani and built a loyalty-app demo (React Native, NestJS, NX monorepo), presented to investors |

</details>

---

### 🧰 Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat&logo=powershell&logoColor=white)

**Backend & Cloud**

![.NET](https://img.shields.io/badge/.NET_6_to_10-512BD4?style=flat&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AKS](https://img.shields.io/badge/AKS-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![Azure Container Apps](https://img.shields.io/badge/Container_Apps-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![App Service](https://img.shields.io/badge/App_Service-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Service Fabric](https://img.shields.io/badge/Service_Fabric-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Azure Functions](https://img.shields.io/badge/Functions-0062AD?style=flat&logo=azurefunctions&logoColor=white)
![Service Bus](https://img.shields.io/badge/Service_Bus-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Event Hubs](https://img.shields.io/badge/Event_Hubs-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Bicep](https://img.shields.io/badge/Bicep/IaC-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)

**AI**

![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat&logo=openai&logoColor=white)
![Semantic Kernel](https://img.shields.io/badge/Semantic_Kernel-512BD4?style=flat&logo=dotnet&logoColor=white)
![GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-000000?style=flat&logo=githubcopilot&logoColor=white)
![AI Agents](https://img.shields.io/badge/AI_coding_agents-555555?style=flat)

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Fluent UI](https://img.shields.io/badge/Fluent_UI-0078D4?style=flat&logo=microsoft&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

**Observability**

![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat&logo=opentelemetry&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Application Insights](https://img.shields.io/badge/App_Insights-68217A?style=flat&logo=microsoftazure&logoColor=white)
![KQL](https://img.shields.io/badge/Kusto/KQL-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Auth & Security**

![OAuth2](https://img.shields.io/badge/OAuth2/OIDC-000000?style=flat&logo=openid&logoColor=white)
![Microsoft Entra ID](https://img.shields.io/badge/Entra_ID-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)
![LTI](https://img.shields.io/badge/LTI_1.3-333333?style=flat)

**Databases**

![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Cosmos DB](https://img.shields.io/badge/Cosmos_DB-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

---

<div align="center">
  <i>Let's talk systems, architecture, or AI.</i>
</div>

<div id="header" align="center">
  <h1>
    Hey there, I'm Mohammad
    <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
  </h1>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=false&width=760&height=40&lines=Software+Engineer+II,+Microsoft+(via+ASAL+Technologies);I+design,+build+and+run+C%23%2F.NET+services+on+Azure;Backend,+platform,+reliability,+identity" alt="Typing SVG" />
  </a>
  <div id="badges">
    <a href="https://www.linkedin.com/in/mohammad-ghabin/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="mailto:mghabin98@gmail.com">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge"/>
    </a>
  </div>
  <br>
</div>

---

### 👨‍💻 About Me

Software Engineer II, Microsoft (via ASAL Technologies). Almost 5 years on Microsoft products, most recently Microsoft 365 tools inside school learning platforms and, before that, AI-powered meeting preparation for bankers. Backend and cloud engineer: I design, build and run production .NET services on Azure end to end, from high-level and low-level design and C#/.NET code to CI/CD, infrastructure as code, deployment, traffic, telemetry, monitoring and on-call.

Product-minded and pragmatic: I challenge unnecessary complexity and optimise for reliability, delivery speed, and maintainability.

- 🏗️ **Current:** I build and run the backend services behind **Microsoft 365 LTI**, which lets teachers and students use Microsoft 365 tools inside their school's learning platform. It works with any learning platform that supports the LTI 1.3 standard, including Canvas, Blackboard, Brightspace (D2L), Schoology and Moodle, and is used by hundreds of thousands of students and teachers every month. I built the backend that merged six education tools into it, live in six months and adopted by close to a thousand education organisations in its first two months.
- 🛠️ **Cloud and delivery:** Deployed and ran services on AKS (Helm) and Service Fabric in several production regions, with multi-region Azure DevOps release pipelines, Application Gateway, Traffic Manager and CDN
- ⚡ **Reliability:** Responsible for reliability and performance of the LTI services and clients (hundreds of millions of requests a month) and on call, with 35 production Grafana dashboards, OpenTelemetry instrumentation and end-to-end correlation ids
- 🤖 **AI:** Built backend services for **Financial Meeting Prep**, a Microsoft Teams app made with **LSEG** that helped bankers prepare for client meetings (retired in October 2025), including the news service I designed and built around Azure OpenAI summaries (with source links), with Semantic Kernel
- 🔧 **Core:** C#/.NET 8 and .NET 10, ASP.NET Core, Azure, Docker, Kubernetes, Helm. Also TypeScript, Python, Java and SQL, with Cosmos DB, SQL Server, PostgreSQL, MongoDB and Redis
- 🔐 **Security:** Secure sign-in with OAuth 2.0, OpenID Connect and Microsoft Entra ID, plus shared token validation, least-privilege permissions, and certificate and signing-key rotation
- 👥 **Mentorship:** Wrote a backend training plan and mentored six ASAL university interns across two cohorts, from interview to final demo, with 90% of features delivered on time

<details>
<summary>More about me &rarr;</summary>
<br>

- 📡 **Observability:** OpenTelemetry, Grafana, Kusto/KQL, Application Insights, monitors and alerts, on-call
- 🚀 **Full-stack when needed:** React, TypeScript, React Native, NestJS. I step in across the stack to unblock teams
- 📊 **Background:** Computer Engineering + Accounting minor, analytical by nature, engineer by choice
- 🔒 Most of my professional work lives in private repositories. Public ones here hold personal projects, learning experiments and reusable samples.

</details>

---

### 🔭 What I'm Working On

- Exploring polyglot monorepo patterns (Bazel + NX), building a reference architecture as a side project

---

### 📌 Highlights

| | |
|---|---|
| 🏗️ **Production Services** | I design, build and run production .NET services end to end: more than ten services and components across two product groups and hundreds of production code changes in ten repositories since 2023, from high-level and low-level design documents to APIs, background jobs, data models, tests, pipelines and releases. Built the backend that merged six Microsoft education tools into Microsoft 365 LTI (Teams meetings on Microsoft Graph, assignments, OneDrive files, roster sync, settings), live in six months and adopted by close to a thousand education organisations in its first two months |
| 🛠️ **Cloud Infrastructure & Delivery** | Deployed and ran services on AKS (Helm) and Service Fabric in several production regions, with multi-region Azure DevOps release pipelines, Application Gateway, Traffic Manager and CDN. Retired the classic service (the older OneDrive LTI tool) in every production region, routing its traffic to a retirement page. Built a reusable CDN deployment pattern for very large files, used by Learning Zone and Reflect, and fixed the .NET 10 build and release path of an internal operations tool |
| ⚡ **Observability & Reliability** | Responsible for reliability and performance of the LTI services and clients (hundreds of millions of requests a month): I present LTI reliability in the monthly service review and take on-call. Built 35 production Grafana dashboards, OpenTelemetry instrumentation, operation-level success tracking and end-to-end correlation ids, work my engineering manager credited with a significant reduction in alert noise. Root-caused a migration timeout that hit dozens of organisations, and detected a website-file delivery failure within 15 minutes, before any alert fired. The core LTI launch service ran at five-nines availability through the 2026 back-to-school peak |
| 🔐 **Identity & Integrations** | Extended secure sign-in with OAuth 2.0, OpenID Connect and Microsoft Entra ID for more than a thousand education organisations, including launches that keep working when browsers block third-party cookies. LTI 1.3 and LTI Advantage (roster sync and deep linking) on any LTI 1.3 platform, with platform-specific handling for Canvas, Blackboard, Brightspace and Schoology, plus Microsoft Graph and LSEG partner APIs. Led a signed-token design for launch content too large for a URL through security review to a kill-switch release. Shared token validation, least-privilege permission reviews, certificate rotation, Secure Future Initiative work and a .NET 8 upgrade with region-by-region signing-key rotation. Roster paging and safeguards for very large classes |
| 🔄 **Data & Migration** | Cosmos DB, SQL Server, PostgreSQL, MongoDB, Redis, Azure Tables, Blob storage, Service Bus and Event Hubs. Designed and built the course migration engine: background jobs with saved progress and resume, Canvas rate limits, admin bulk migration, and one class group per course, even when a teacher and students launch it at the same moment (an ETag-guarded lease in Cosmos DB). Fixed its timeout incident so courses with 20,000+ links could move. Repaired more than a thousand courses split across two sites after a full dry run and a small pilot run (canary) |
| 🤖 **AI** | Built backend services for **Financial Meeting Prep**, a Microsoft Teams app made with **LSEG** for bankers: designed and built the news service around Azure OpenAI summaries (with source links), plus Semantic Kernel work, a provider-neutral data layer with a mock LSEG service, Polly resilience and a shared .NET library, and wrote the Bicep for its Azure environments. Reached 95% test coverage with 200+ tests and cut deployments from 26 to 15 minutes by promoting the build already tested in the pull-request pipeline instead of rebuilding it |
| 🚀 **Startup** | Co-founded Watani and built a loyalty-app demo (React Native, NestJS, NX monorepo), presented to investors |

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

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_8-512BD4?style=flat&logo=dotnet&logoColor=white)
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

**Frontend & Mobile**

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)

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

**Architecture**

![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-555555?style=flat)
![Microservices](https://img.shields.io/badge/Microservices-555555?style=flat)
![Event-Driven](https://img.shields.io/badge/Event--Driven-555555?style=flat)
![System Design](https://img.shields.io/badge/System_Design-555555?style=flat)
![Multi-tenant SaaS](https://img.shields.io/badge/Multi--tenant_SaaS-555555?style=flat)

---

<div align="center">
  <i>Let's talk systems, architecture, or AI.</i>
</div>

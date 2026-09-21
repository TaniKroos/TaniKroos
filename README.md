# **TANISH SAINI**

### Backend Software Engineer | Cloud-Native Systems & GenAI | C#, Python| Azure

---

## 📞 **Contact Information**

📍 **Location:** New Delhi, India  
📱 **Phone:** +91-8447951790  
📧 **Email:** tanishsaini26@gmail.com  
🔗 **LinkedIn:** [Tanish Saini](https://www.linkedin.com/in/tanish-saini-90410822a/)  
🐦 **Twitter:** [@tanish2731](https://twitter.com/tanish2731)  
💻 **LeetCode:** [tanikroos](https://www.leetcode.com/tanikroos)  

---

## 👋 **Professional Summary**

Backend Software Engineer focused on building **scalable GenAI systems** and **distributed, cloud-native architecture** on **Azure**. Experience spans **RAG pipelines**, semantic search over large vector datastores, and — most recently — building **Steve**, an autonomous AI coding agent that runs in isolated cloud sandboxes and ships real pull requests end-to-end. Comfortable owning a system from **backend design** through **CI/CD** and deployment, with a focus on making distributed systems resilient to real-world failure (crash recovery, horizontal scaling) rather than just happy-path correct.

---

## 💼 Professional Experience

### Associate Programmer | Xceedance
*Jan 2025 – Present*

#### AI Skills MCP Framework
*.NET 8 · C# · Azure Functions · Azure OpenAI · Azure AD*
- Proposed and prototyped a lightweight, Markdown-based **MCP** server for sharing reusable AI skills across teams; it became the platform the team shipped, now serving **100+ skills** to **800+ engineers**.
- Secured it with **Azure AD (Entra ID)** using **OAuth 2.0 / OIDC**: app registrations, JWT bearer validation, and scope and app-role claims mapped to per-resource authorization across **10+ client applications**.
- Own it in production: releases, breaking-change upgrades, and first-line support for the engineers using it.

#### Intelligent Test Generation & Automation Platform
*.NET 8 · Azure OpenAI · Cosmos DB · Azure DevOps · E2B*
- Designed and shipped the backend for AI-driven test generation: an LLM turns user stories into test cases, producing **500+ cases per project** with **87%** needing no manual edit.
- Built retrieval over **100K+ historical test cases** using **Cosmos DB** vector embeddings, passing the most relevant past cases to the LLM as context (**RAG**) and cutting manual authoring time by **80%**; integrated into existing **Azure DevOps** workflows.
- Extended the platform with an **agentic loop** that turns test cases into complete UI automation frameworks in **Selenium**, **Playwright** or **Cypress**, writing, running and fixing code in an isolated **E2B sandbox** until the framework works. Generated frameworks follow the page object model with assertions in place; the platform is now used by **20+ QA teams** and **100+ QA engineers**.

#### AI Log Summarization & Evaluation Platform
*.NET 8 · C# · Azure OpenAI · Cosmos DB*
- Engineered a serverless service processing **50,000+ log entries daily** at **sub-50ms latency**, with RAG-based summarization over production logs.
- Built a structured logging library and summarization pipeline instrumenting **15 production workflows**, which became the team's shared method for evaluating model accuracy and driving later accuracy improvements.

#### Production Reliability
- Diagnosed a full outage of a serverless application after a deployment, with no logs to go on: every request was failing during dependency resolution, before our logging started. Traced it to an environment variable missing from the deployment, then helped implement a **global exception handler** so startup and dependency failures are logged instead of failing silently.

#### Collaboration & Delivery
- Gathered requirements directly from multiple QA and product teams, then designed a single platform serving all of them rather than one tool per team; present working demos to internal and prospective client stakeholders.
- Deliver iteratively in an **Agile/Scrum** team: sprint planning, user stories, regular code reviews, and cross-functional work with product and QA.
---

## 🚀 **Projects**

### **Steve** — Cloud-Native Autonomous AI Coding Agent
🌐 **Live Demo:** [Steve](https://www.smudgee.xyz/)

- Architected a full-stack platform (**Python**, **FastAPI**, **React**, **TypeScript**) where an AI agent autonomously edits code inside an isolated **E2B** sandbox and opens a real GitHub pull request — end-to-end, no manual steps.
- Designed a **multi-provider LLM abstraction** (Anthropic Claude, Azure OpenAI, OpenAI-compatible hosts) behind one interface, enabling provider swaps with zero changes to the agent's 15+ tool-calling loop.
- Built a **distributed, crash-recoverable session-ownership system** (Redis-backed instance registry, sticky routing) enabling the agent service to run as multiple horizontally-scaled instances with no session lost to a crash.
- Real-time streaming via **Redis pub/sub** + **Server-Sent Events**, delivering live agent output and tool-call status to the browser.

---

## 🎓 **Education**

### **Bhagwan Parshuram Institute of Technology (BPIT)** | Delhi
**B.Tech in Electronics & Communication Engineering**  
📊 **CGPA:** 8.35 | 📅 **Duration:** 2021–2025 | 📍 **Rohini, Delhi**

### **S.M. Arya Public School** | Delhi
- 🎖️ **Class XII (CBSE):** 93.6% (2020–2021)
- 🎖️ **Class X (CBSE):** 91% (2018–2019)

---
## 🛠️ **Technical Skills**

### **Languages & Core**
**C#** • **.NET 8** • Java • Python • **Node.js** • **C++** • JavaScript • TypeScript

### **Cloud Architecture**
**Microsoft Azure** • Serverless Design • Distributed Systems • **AWS**

### **GenAI & Vectors**
**RAG** • Vector Embeddings • Semantic Search • **Azure OpenAI** Integration • Prompt Engineering

### **Data & Observability**
**Azure Cosmos DB** (SQL/Vector APIs) • **MongoDB** • **PostgreSQL** • **Application Insights**

### **DevOps & Tools**
**Docker** • **Kubernetes** • **Git** • **CI/CD Pipelines** • **Jenkins** • Linux

### **Web Technologies**
**Express.js** • **Next.js** • **React** • **Socket.io** • **JWT** • **Prisma ORM**

### **Badges & Visual Stack**
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230078d4.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![Selenium](https://img.shields.io/badge/-selenium-%23043B02?style=for-the-badge&logo=selenium&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-%232EAD33.svg?style=for-the-badge&logo=playwright&logoColor=white) ![Cypress](https://img.shields.io/badge/Cypress-%2369D3F3.svg?style=for-the-badge&logo=cypress&logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white)

---

---
[![](https://visitcount.itsvg.in/api?id=TaniKroos&icon=0&color=0)](https://visitcount.itsvg.in)

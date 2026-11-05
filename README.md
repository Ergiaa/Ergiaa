<h1 align="center">Viera Tito Virgiawan</h1>
<p align="center">Backend developer focused on authentication, encryption, and data and document pipelines.</p>

<p align="center">
  <a href="mailto:titovirgiawan21@gmail.com">Email</a> &middot;
  <a href="https://linkedin.com/in/viera-tito">LinkedIn</a>
</p>

---

I build backend systems where getting the security and data model right matters more than shipping another CRUD layer. Most recently that meant a document management platform for the Ministry of Foreign Affairs of the Republic of Indonesia, spanning a central office and overseas posts, where I worked on the encryption layer, access control, and cross-site synchronisation.

I work mainly in TypeScript, with Python for retrieval and ML services and Java from teaching Algorithms and Data Structures at ITS. I am comfortable owning a system end to end, from relational schema through API design to infrastructure and deployment.

- Currently deploying **Scholar Seek**, my undergraduate thesis, for continued use by a lab at ITS
- Going deeper on **clean architecture**
- Open to collaborating on backend systems, API design, and anything involving auth, encryption, or search
- Ask me about TypeScript, Node.js, PostgreSQL schema design, background job architecture, Terraform and CI/CD, or why your editor should be Neovim

## Featured work

| Project | What it is | Stack |
| --- | --- | --- |
| **[Scholar Seek](https://github.com/Ergiaa/scholar-seek)** &middot; [ML service](https://github.com/Ergiaa/scholar-seek-ml) | Bilingual academic search across ArXiv, Semantic Scholar, and DOAJ. Query decomposition and pseudo-relevance feedback fused with Reciprocal Rank Fusion, so reformulation can only add candidates and never scores below plain query search. Evaluated with a self-built 47-query gold standard and a 4-condition ablation study, with a 44-test pytest suite over the retrieval service. | Elysia, Bun, FastAPI, Stanza, BM25, pgvector, PostgreSQL, React |
| **[Portify](https://github.com/Ergiaa/portify)** | Portfolio and cross-platform analytics for a content creator. I owned the database, application design, and deployment: full schema, three-tier RBAC, OAuth2 token custody with application-layer encryption, and a JSON-configurable page builder. Running on Azure. | Bun, Hono, oRPC, Astro, Drizzle ORM, PostgreSQL, Azure |
| **Government Document Management Platform** | Document lifecycle across a central office and overseas posts: drafting through approval, digital signing, and archiving. End-to-end encryption between sites, OIDC/SSO with TOTP MFA, and queue-backed multi-site sync. Covered by an NDA, so no repository. | TypeScript, C#, Express.js, PostgreSQL |
| **[Book Library Platform](https://github.com/dzaky-pr/fp-pso)** | Serverless CRUD app on AWS, built as a four-person team project. I owned the Terraform infrastructure as code for the whole environment (Lambda, DynamoDB with auto-scaling, API Gateway, S3, EC2, VPC, least-privilege IAM, encrypted remote state) and contributed to the GitHub Actions pipeline: lint, unit and end-to-end tests, build, deploy to staging and production, post-deployment smoke tests, and a SonarCloud quality gate. | Terraform, AWS, GitHub Actions, DynamoDB, Next.js, Jest, Playwright |
| **[Survey and Estimation Tooling](https://github.com/jasmrntha/nuii-backend)** (NUII, for PT PLN (Persero) Distribusi Jawa Timur) | Turns a route plotted on a map into pole types, construction requirements, and the Excel reports planners and field engineers work from, replacing an on-site survey plus one to two hours of report preparation per route. | Express, TypeScript, ExcelJS |

## Tech

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-E36002?style=flat-square&logo=hono&logoColor=white)
![Elysia](https://img.shields.io/badge/Elysia-0F172A?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Data**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logoColor=white)

**Platform**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Testing**
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logoColor=white)
![SonarCloud](https://img.shields.io/badge/SonarCloud-F3702A?style=flat-square&logo=sonarqubecloud&logoColor=white)

**Also work with:** AES-256-GCM and envelope encryption, RSA key management, OIDC/SSO, TOTP MFA, JWT, RBAC, OAuth2, Bull job queues, Puppeteer, Tesseract.js, ExcelJS, Astro, React, TailwindCSS, Turborepo.

## Where I work

![Arch Linux](https://img.shields.io/badge/Arch%20Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white)
![Omarchy](https://img.shields.io/badge/Omarchy-1E1E2E?style=flat-square)
![Hyprland](https://img.shields.io/badge/Hyprland-00A4CC?style=flat-square&logo=hyprland&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![LazyVim](https://img.shields.io/badge/LazyVim-2E7DE9?style=flat-square)
![fish](https://img.shields.io/badge/fish-34C534?style=flat-square)

I daily drive **Arch Linux** with **Omarchy** on Hyprland, and most of my day happens in a terminal: foot, fish, Atuin for shell history, and **Neovim with LazyVim** for everything I write, from TypeScript services to Python ML code. I like the tinkering that comes with it. Tuning a tiling window manager, remapping keys with Makima, reshaping btrfs volumes and boot config, and fixing whatever a rolling release decides to break this week all count as fun to me.
## Ways of working

Alongside the engineering work I have run delivery as Scrum Master: sprints and backlog with the Product Owner at BETA U through March 2026, and on a university competition project. I also spent a term as a teaching assistant for Algorithms and Data Structures at ITS, running lab sessions in Java and reviewing student code. I care about clean, testable architecture and systems the next person can maintain.

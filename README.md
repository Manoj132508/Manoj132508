# Manoj Palanisamy

### Full-Stack Software Engineer

React · TypeScript · Next.js · Node.js · Python · FastAPI · AWS

[Portfolio](https://manojdevai.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/manojpalanisamydev/) · [Email](mailto:manojpalanisamy46@gmail.com)

I’m a Full-Stack Software Engineer based in the United Kingdom, working at **Maverick Technologies since March 2025**. I build and maintain a **B2B AI document intelligence platform for legal and HR teams**, covering React interfaces, secure HTTP APIs, document ingestion and application data.

My commercial work includes tenant-scoped PostgreSQL and ChromaDB access, document-approval transactions, JWT authentication, RAG processing and container delivery on AWS. I collaborate with a Lead Engineer, Product Manager and Customer Success; the independent repositories below provide separate public examples of my engineering work.

## What I work on

- **Tenant isolation and access:** authenticated JWT tenant context, parameterised PostgreSQL tenant conditions and ChromaDB metadata filters in shared application services.
- **Document ingestion:** presigned Amazon S3 URLs for direct browser uploads and background Python processing, with exponential-backoff retries for embedding API rate limits.
- **Secure HTTP APIs:** Python/FastAPI and TypeScript/Node.js/Express, Pydantic validation, structured errors, JWT refresh handling and role-based access control.
- **Transactional workflows:** PostgreSQL transactions and `SELECT FOR UPDATE` row locks for concurrent document approvals, including commit/rollback handling and concurrent-request checks.
- **AI applications:** RAG, paragraph-aware recursive text splitting with LangChain, embeddings, metadata validation and retrieval using ChromaDB.
- **Product interfaces:** React and TypeScript dashboards, TanStack Query for server state, Redux Toolkit for client state, and a Next.js marketing/onboarding portal.
- **Testing:** Vitest and React Testing Library for frontend behaviour, pytest and mocked API interactions for Python, Jest/Supertest for Express authentication, and Postman for request investigation.
- **Cloud and delivery:** Docker Compose for local development; Docker images in ECR and ECS tasks on EC2; GitHub Actions checks, automatic staging deployment and approval-gated production releases.
- **Investigation and teamwork:** CloudWatch logs, Datadog dashboards, reproducible debugging, pull requests and code reviews with the engineering team.

## Technical toolkit

| Area | Technologies and practices |
|---|---|
| Languages | JavaScript, TypeScript, Python, SQL, HTML, CSS |
| Frontend | React, Next.js, server-side rendering, Redux Toolkit, TanStack Query, Axios |
| Backend and access | Node.js, Express.js, FastAPI, Pydantic, HTTP/REST APIs, JWT, RBAC, tenant-scoped access |
| Data | PostgreSQL, transactions, row locking, MongoDB, Mongoose, ChromaDB metadata filters |
| AI applications | RAG, LangChain RecursiveCharacterTextSplitter, embeddings, vector retrieval, metadata validation, API retry handling |
| Testing | Vitest, React Testing Library, Jest, Supertest, pytest, unittest.mock, Postman |
| Cloud and delivery | AWS S3, ECR, ECS on EC2, Docker, Docker Compose, GitHub Actions |
| Monitoring and collaboration | CloudWatch, Datadog, browser developer tools, Git/GitHub, code reviews, technical documentation |

## Selected projects

These repositories provide examples of my project work alongside my commercial full-stack experience.

| Project | Engineering focus | Explore |
|---|---|---|
| [E-commerce modernization (review branch)](https://github.com/Manoj132508/Ecommerce-project/tree/portfolio-week/ecommerce-modernization) | Staged Express/MongoDB-to-PostgreSQL modernization, versioned migrations and transactional import; **264 PostgreSQL tests** in verified CI | [Migration evidence](https://github.com/Manoj132508/Ecommerce-project/blob/portfolio-week/ecommerce-modernization/docs/portfolio-evidence.md) |
| [FinTrack](https://github.com/Manoj132508/FinTrack) | Expense analytics with React, Redux Toolkit, Chart.js, Express and SQLite; per-user accounts, budgets, reports and CSV export | [Architecture notes](https://github.com/Manoj132508/FinTrack#-architecture-notes) |
| [AI Knowledge Assistant](https://github.com/Manoj132508/ai-) | Document Q&A using React, Express, FastAPI, MongoDB and ChromaDB, with source citations and retrieval thresholds | [Case study](https://github.com/Manoj132508/ai-/blob/main/docs/case-study.md) |
| [AI Career & ATS Platform](https://github.com/Manoj132508/ai-career-platform) | React/JavaScript, Express and FastAPI with deterministic matching and grounded tailoring; **140 passing tests** | [Architecture and CI evidence](https://github.com/Manoj132508/ai-career-platform/blob/main/docs/portfolio-evidence.md) |
| [AI Support Desk](https://github.com/Manoj132508/support-desk) | ChromaDB retrieval, deterministic policy, explicit confirmation and Docker Compose; **871 passing tests** across API, frontend and AI layers | [Architecture and CI evidence](https://github.com/Manoj132508/support-desk/blob/main/docs/portfolio-evidence.md) |

### Verified project results

These results describe independent projects and specific source revisions; they are not Maverick customer or production metrics.

- Support Desk: **586 Node + 151 Vitest + 134 pytest = 871 passes**, rerun locally on 26 October 2026; [matching CI run](https://github.com/Manoj132508/support-desk/actions/runs/35281304010). The separate dependency-audit workflow currently fails and is disclosed in the project README.
- Career Platform: **55 Node + 26 Vitest + 59 pytest = 140 passes**, rerun locally on 26 October 2026; [matching CI run](https://github.com/Manoj132508/ai-career-platform/actions/runs/34167883667). The public frontend is JavaScript; a local TypeScript conversion remains in progress.
- E-commerce: **264 PostgreSQL integration tests** at review revision `bb2944f`; [CI run](https://github.com/Manoj132508/Ecommerce-project/actions/runs/39941498302). The implementation remains staged and unmerged; a zero-downtime production cutover is not established.

## How I approach engineering

- Reproduce the problem, trace the request or state change, and identify the cause before changing code.
- Keep authentication, validation, business rules and data access clear and testable.
- Check failure paths as well as successful operations, then verify the fix against related workflows.
- Describe AI capabilities and limitations clearly, with source evidence and controlled actions where appropriate.

## Education

- **MSc Computer Science**, University of East London — 2025
- **Bachelor of Computer Applications**, K.S. Rangasamy College of Arts and Science — 2022

## Connect

Interested in full-stack and backend software engineering opportunities in the UK.

[Portfolio](https://manojdevai.netlify.app/) · [LinkedIn](https://www.linkedin.com/in/manojpalanisamydev/) · [Email](mailto:manojpalanisamy46@gmail.com) · [All repositories](https://github.com/Manoj132508?tab=repositories)

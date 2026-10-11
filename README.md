# Mehedi Hasan

**Software Engineer · Full Stack** — building SaaS platforms, AI products and enterprise CRM systems.

I design and ship end-to-end products: web frontends, backend services, data pipelines, and the cloud infrastructure they run on. My work powers sales, campaign and customer-engagement operations for large telecom and FMCG companies.

## Experience

| Role | Company | Period |
|---|---|---|
| **Software Engineer** | [V2 Technologies LTD](https://github.com/V2-Technologies-LTD) — AI-powered products and enterprise platforms | Nov 2024 – Present |
| **Software Engineer** | [X Solutions Ltd](https://github.com/X-Solutions-Ltd) — sales-force and distribution management systems | Jan 2025 – Present |

## Featured work

### 🤖 AI document generation engine — *conversational AI platform*
Owner of the generation service in an 11-microservice NestJS platform.
- The LLM calls a tool that emits a typed document model, which I render to **PDF, DOCX, PPTX and HTML**
- Hand-written OOXML writer for Word and PowerPoint, with embedded Bangla fonts and native PowerPoint charts built from numeric tables
- Detects malformed model output and repairs it or retries once within the token budget; web search with citations and editing of existing documents

### 🧭 LLM model routing & token billing — *conversational AI platform*
- In-house prompt-complexity classifier in the API gateway that picks the model tier for every request
- Tokens are reserved before the call and settled after it, billed on the model that actually answered
- Admin controls: maker-checker approvals, hash-chained audit log, legal holds and dual-control refunds

### 📡 High-volume field-force CRM — *for a leading telecom operator*
Lead on the location, login, report and upload services of a multi-tenant Node.js / PostgreSQL microservice platform.
- Streams **~400k geo-tagged rows (~190 MB)** in one response: PostgreSQL cursor → gzip → HTTP with backpressure, cached in Redis until the next import
- Fault-tolerant bulk CSV import: background batches of 2,000 rows, per-row error reports, recovery of stuck imports, and materialized-view refresh only when the whole import succeeds
- Mobile auth across services: JWT + Redis sessions, one device per user per day, OTP, lockout, app-version gating and face-recognition check-in
- Led the move of every service to PgBouncer for connection stability

### 🎵 Music & video distribution SaaS — *sole developer*
- Royalty revenue engine: imports store reports, normalizes ISRCs, applies label revenue shares and tax, and powers per-track / per-label / per-platform analytics
- Fine-grained, database-backed access scoping for staff, enforced by guards and a scoped-query registry
- Zero-downtime Docker Swarm deploys, Redis/Bull job queues with retries, presigned direct-to-S3 uploads and audio-fingerprint copyright checks

### 🏫 Multi-tenant school management SaaS — *top contributor*
- Attendance pipeline: a queue worker computes on-time / late / absent with SQL window functions, pulls data from attendance devices and sends SMS to guardians
- Bulk and template SMS and voice messaging with Unicode-aware segment counting and a credit ledger
- ~90-model data schema covering fees, invoices, online payments across branches and bulk admission

### 📝 Assessment platform — *sole author, running for two companies*
- NestJS + Drizzle exam service with timed multi-section exams, partial-credit scoring in a single transaction, and resumable chunked uploads to Azure Blob and S3

### 📄 Print-accurate document builders
- Resume builder with measured pagination shared by preview and print, auto-fit to one page, and a drag-and-drop layout editor — WCAG AA, Vitest + Playwright tests
- [Bengali/English biodata builder](https://github.com/mehedihasansumit/bio-data) (open source) with A4 page layout and 8 print templates

## Tech stack

![TypeScript](assets/badges/typescript.svg)
![JavaScript](assets/badges/javascript.svg)
![React](assets/badges/react.svg)
![Next.js](assets/badges/next-js.svg)
![Node.js](assets/badges/node-js.svg)
![NestJS](assets/badges/nestjs.svg)
![Python](assets/badges/python.svg)
![Go](assets/badges/go.svg)
![MongoDB](assets/badges/mongodb.svg)
![PostgreSQL](assets/badges/postgresql.svg)
![MySQL](assets/badges/mysql.svg)
![Tailwind CSS](assets/badges/tailwind-css.svg)
![Docker](assets/badges/docker.svg)
![Kubernetes](assets/badges/kubernetes.svg)
![Helm](assets/badges/helm.svg)
![Nginx](assets/badges/nginx.svg)
![Amazon S3](assets/badges/amazon-s3.svg)
![Azure Blob Storage](assets/badges/azure-blob-storage.svg)
![Cloudflare R2](assets/badges/cloudflare-r2.svg)

## Connect

[![LinkedIn](assets/badges/linkedin.svg)](https://www.linkedin.com/in/mehedi-hasan-sumit-103621210/)
[![Email](assets/badges/email.svg)](mailto:mehedihasansumit@gmail.com)

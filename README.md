<div align="center">

# Hi, I'm Beka 👋

### Senior Full-Stack Engineer · TypeScript · Angular · NestJS · Next.js

*Building national-scale government systems in Tbilisi and shipping my own product, [Fixon](https://fixon.ge), end to end*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beka-jorjikia-1517a6257/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:beka.jorjikia@gmail.com)
[![Fixon](https://img.shields.io/badge/fixon.ge-live-111111?style=for-the-badge)](https://fixon.ge)

📍 Tbilisi, Georgia (GMT+4) · 🌍 Open to remote and relocation

</div>

---

## 🧑‍💻 About Me

Full-stack TypeScript engineer with **5 years of commercial experience**, the last three on **national-scale government systems** at MSDA (Tbilisi City Hall):

- **MSMap** ([maps.tbilisi.gov.ge](https://maps.tbilisi.gov.ge)): the city's GIS platform, handling **~13M requests a day** and **48K monthly active users**
- **Social Transfers**: a social-benefits platform integrated with **6+ government and financial systems**

I also co-founded **[Fixon](https://fixon.ge)**, an on-demand car-service product that I designed, built and run in production.

> 🔒 Most of my professional work lives in a private, VPN-only GitLab, which is why the contribution graph looks quiet. The case studies below describe that work without exposing code.

---

## 🛠️ Tech Stack

**Frontend**

![Angular](https://img.shields.io/badge/Angular_19-DD0031?style=flat-square&logo=angular&logoColor=white)
![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat-square&logo=reactivex&logoColor=white)
![NgRx](https://img.shields.io/badge/NgRx_Signals-BA2BD2?style=flat-square&logo=ngrx&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

**DevOps, Observability & Testing**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI/CD-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square)

**Architecture:** event-driven workflows · transactional outbox · cache-aside · retry · circuit breaker

---

## 🚀 Featured Work

### 🔧 [Fixon](https://fixon.ge): Co-Founder & Founding Engineer *(Mar 2026 – present · live in production)*

> On-demand oil-change service in Tbilisi with real orders and card payments

I designed, built and run the entire technical product end to end, from product design and architecture to production operations.

**Tech:** Next.js (App Router) · TypeScript · PostgreSQL / Prisma · Zod · Vitest · Vercel · Sentry · Ably

- 💳 **Bank of Georgia card payments:** callback handling, reconciliation polling and abandoned-checkout recovery (retry or cash fallback), on a transactional outbox with race-free order completion
- 🚗 **Vehicle and oil fitment engine:** VIN decoding, photo capture, ambiguous-match recovery and engine-code rules that return the exact oil viscosity and volume for each vehicle
- 📍 **Real-time courier GPS tracking** (Ably); OTP auth, admin actions and public routes hardened with rate limiting
- 📈 **Sentry** error and cron-heartbeat monitoring

---

### 🏛️ Social Transfers: MSDA *(private GitLab)*

> B2G platform covering the full social-benefit cycle: beneficiary identification, eligibility checks, payment statements, bank disbursement and document workflow

This is the pre-production successor to a system already in use, built by a team of six. It integrates **6 government and financial systems** (civil registry, social service agency, Ministry of Health, bank, document flow and HR) and runs on event-driven processing with **10+ Kafka and RabbitMQ consumers**.

**Tech:** Angular 19 · NestJS · MongoDB · GraphQL · Kafka · RabbitMQ · Redis · Kubernetes · GitLab CI/CD

- 👥 **Lead contributor** to the Angular admin console for program operators; I review and merge most of the team's frontend changes (**138 merge requests in 2026**)
- 🔁 **Payroll and register workflow:** a multi-step wizard on a draft/upgrade state machine, with stale-lock detection and watchdog recovery for long-running jobs
- 📤 **Async XLSX export pipeline** that I designed and built alone: Kafka workers, cursor-based streaming, crash recovery, cleanup of old files and real-time progress over WebSockets, sized for datasets of **~1M records**
- 🩹 Removed two failure modes on large exports, self-cancelling jobs and jobs stuck at 99%, using a finalize timeout, a separate finalizing phase and automatic cleanup of stuck jobs
- 🩺 Co-built a dedicated microservice that verifies disability status against the Ministry of Health registry

---

### 🗺️ MSMap: [maps.tbilisi.gov.ge](https://maps.tbilisi.gov.ge) *(MSDA)*

> Tbilisi's municipal GIS platform: **~13M requests a day** and **48K monthly active users** across municipal services, architects and the public

I develop and maintain the frontend of the map application, and I maintain the **shared Angular UI component library** used by **10+ internal production apps**.

**Tech:** Angular · TypeScript · OpenLayers · GeoServer · microservices

---

## 🧪 Open Source & Side Projects

| Project | What it is | Stack |
|---|---|---|
| [**miora**](https://github.com/bekajorjikia/miora) · [live](https://miora-eight.vercel.app) | QR digital menu for restaurants: bilingual EN/KA menu and staff admin panel, with tag-based cache invalidation | Next.js · Supabase · Tailwind · Vitest |
| [**currency-converter**](https://github.com/bekajorjikia/currency-converter) | Currency conversion API with Redis cache-aside, retry with backoff, circuit breaker and stale-cache fallback | NestJS · Redis · Docker · Swagger |
| [**ms-maps-ui-libs**](https://github.com/bekajorjikia/ms-maps-ui-libs) | Angular components for OpenLayers maps with WKT geometry support, published on npm | Angular 20 · OpenLayers |
| [**p2p-file-transfer**](https://github.com/bekajorjikia/p2p-file-transfer) | Serverless peer-to-peer file transfer with one-click AI summaries of received files | Pear Runtime · JavaScript · OpenAI |
| [**WebRTC Messenger**](https://github.com/bekajorjikia/msda-chat) | Real-time chat and video calls with a custom signaling server | Angular · WebRTC · Node.js |
| [**Weather × AI Outfit Advisor**](https://github.com/bekajorjikia/Weather-Clothing--Front) | AI outfit recommendations based on current weather | TypeScript · OpenAI |

---

## 💼 Experience

| Period | Role | Company |
|--------|------|---------|
| Sep 2023 – Present | Full-Stack Engineer | **MSDA** (Municipal Services Development Agency, Tbilisi City Hall) |
| Mar 2026 – Present | Co-Founder & Founding Engineer | **[Fixon](https://fixon.ge)** |
| May 2025 – Sep 2025 | Frontend Engineer (React Native) | **Noxtton** (Rumble Wallet, Rumble Inc.) |
| May 2023 – Dec 2023 | Full-Stack Engineer | **Bnollar** (blockchain / fintech) |
| Jul 2022 – Feb 2023 | Full-Stack Engineer | **Kross Georgia** (first version of the oil-change app that later evolved into Fixon) |
| Feb 2021 – Jan 2022 | Freelance Web Developer | Small-business clients |

---

<div align="center">

📬 **Open to remote roles, relocation and interesting collaborations**

[![Email](https://img.shields.io/badge/beka.jorjikia@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:beka.jorjikia@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/beka-jorjikia-1517a6257/)

</div>

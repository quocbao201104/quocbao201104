<h1 align="center">Bảo</h1>

<p align="center"><sub>@baodev</sub></p>

<p align="center">
  <a href="https://github.com/quocbao201104">
    <img src="https://readme-typing-svg.demolab.com/?lines=Backend+Engineer;AI+Systems+Builder;Security-minded+Builder&font=Fira+Code&size=22&pause=1200&color=0F6E56&center=true&vCenter=true&width=440&height=45" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  I build backend systems and AI pipelines for real operational use — designed with failure in mind, secured from the start.
</p>

<p align="center">
  <a href="https://baodev.me/">
    <img src="https://img.shields.io/badge/Portfolio-baodev.me-0F6E56?style=for-the-badge&logo=googlechrome&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:quocbao201104@gmail.com">
    <img src="https://img.shields.io/badge/Email-contact-534AB7?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://github.com/quocbao201104">
    <img src="https://img.shields.io/badge/GitHub-quocbao201104-24292e?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## ⟡ About

Most of my work sits at the intersection of **backend infrastructure** and **AI workflows** — routing, validation, failover, and observability. I design for the unhappy path, not just the demo. Auth, access control, and data integrity aren't bolted on later; they're part of the foundation.

<table>
<tr>
<td valign="top" width="50%">

**What I focus on**

- Reliable backend systems under real load
- AI pipelines with explicit quality control
- Security as a default, not an afterthought
- Observability so failures surface early

</td>
<td valign="top" width="50%">

**How I work**

- Failure-first system design
- Clear routing over black-box decisions
- Graceful degradation & failover
- Ship for operations, not for show

</td>
</tr>
</table>

---

## ⟡ Capabilities

| Area | Stack |
|------|-------|
| **Languages & Runtime** | ![Node.js](https://img.shields.io/badge/Node.js-0F6E56?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-0F6E56?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-0F6E56?style=flat-square&logo=python&logoColor=white) |
| **Backend & Security** | ![Express](https://img.shields.io/badge/Express-534AB7?style=flat-square&logo=express&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-534AB7?style=flat-square&logo=fastify&logoColor=white) ![JWT](https://img.shields.io/badge/Auth-JWT_·_OAuth2_·_RBAC-534AB7?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **Data & Processing** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F6FEB?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-1F6FEB?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-1F6FEB?style=flat-square&logo=redis&logoColor=white) ![Queues](https://img.shields.io/badge/Queue_Systems-1F6FEB?style=flat-square) |
| **AI & Pipelines** | ![LLM](https://img.shields.io/badge/LLM_Pipelines-7F77DD?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-7F77DD?style=flat-square) ![Agents](https://img.shields.io/badge/Agent_Orchestration-7F77DD?style=flat-square) |
| **Infra & Storage** | ![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-F38020?style=flat-square&logo=cloudinary&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-F38020?style=flat-square&logo=vercel&logoColor=white) |

---

## ⟡ GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=quocbao201104&theme=radical" alt="GitHub contribution activity" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=quocbao201104&theme=radical" height="165em" alt="GitHub statistics" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=quocbao201104&theme=radical" height="165em" alt="Repositories by language" />
</p>

---

## ⟡ Selected Work

### 🤖 OmniPilot — AI Sales Agent for Shopee

> My main project: a seller-controlled AI sales agent that chats with Shopee buyers 24/7 — reads new messages, understands intent, answers from shop knowledge, and auto-replies on the seller's behalf.

- Grounded replies from shop catalog and policies, with guardrails so the agent stays factual and on-policy
- Safety-first: risky buyers and off-platform requests are filtered out before any automated reply
- Built to run unattended — resilient to interruptions, with seller-controlled auto-send and a global kill-switch

<sub>`TypeScript` · `Chrome Extension` · `Node.js` · `LLM + RAG`</sub> &nbsp;·&nbsp; 🔒 Private

---

### 📊 MarketGap — Product Opportunity Intelligence

> Finds market gaps: products with strong demand on 1688 (China) that still face little competition on Shopee Vietnam — telling sellers what's worth importing before the market gets crowded.

**Engine** — Crawls source marketplaces, groups duplicate products, matches them against Shopee listings, and scores each opportunity on demand, margin, competition, and risk. <sub>`Python` · `Web Crawling` · `Market Intelligence`</sub>

**SaaS** — Dashboard where sellers explore scored opportunities, view product and competitor detail, get market alerts, and save or reserve picks. <sub>`Next.js` · `TypeScript` · `PostgreSQL` · `payOS`</sub>

<sub>🔒 Private</sub>

---

### 📄 Arbitext — AI Document Translation Pipeline

> Production AI workflow for document translation — the goal was quality control, not speed.

- Multi-stage pipeline: analyze → draft → QA → repair → review
- Provider failover and telemetry so the system degrades gracefully when a model is unavailable
- Explicit routing decisions instead of black-box behavior

<sub>`Node.js` · `TypeScript` · `LLM APIs` · `Queue Systems` · `Redis`</sub> &nbsp;·&nbsp; 🌐 [arbitext.com](https://arbitext.com/) &nbsp;·&nbsp; 🔒 Private

---

### 🎧 TruyenVietHay — Content & Audio Platform

> Vietnamese content platform built for scale — CDN-backed media delivery, real-time features, and content-heavy workloads.

- Optimized media pipeline with object storage + CDN
- Secure auth flows with JWT and RBAC
- Queue-based ingestion for reliable asynchronous processing

<sub>`Node.js` · `TypeScript` · `MySQL` · `Redis` · `Cloudflare R2` · `Cloudinary`</sub> &nbsp;·&nbsp; 🌐 [truyenviethay.id.vn](https://truyenviethay.id.vn/) &nbsp;·&nbsp; 🔒 Private

---

## ⟡ Other Projects

- **[Audio Ingest](https://github.com/quocbao201104/Audio-Ingest)** — YouTube audio processing pipeline with queue-based ingestion.
- **[Crawl Novel](https://github.com/quocbao201104/Crawl-Novel)** — content crawler with deduplication and queue orchestration.
- **[Portfolio source](https://github.com/quocbao201104/quocbao201104.github.io)** — source for my personal website, [baodev.me](https://baodev.me/).

---

<p align="center">
  <sub>Open to backend / AI systems roles where reliability actually matters &nbsp;·&nbsp; <a href="mailto:quocbao201104@gmail.com">reach out</a></sub>
</p>

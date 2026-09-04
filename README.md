<h1 align="center">Bảo</h1>

<p align="center"><sub>@baodev</sub></p>

<p align="center">
  <a href="https://github.com/quocbao201104">
    <img src="https://readme-typing-svg.demolab.com/?lines=Backend+Engineer;AI+Systems+Builder;Reliability-first+Engineer&font=Fira+Code&size=22&pause=1200&color=0F6E56&center=true&vCenter=true&width=440&height=45" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  I build backend and AI systems for real operational use — explicit state, bounded decisions, and failure-aware automation.
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

Most of my work sits at the intersection of **backend systems**, **AI workflows**, and **operational reliability**. I care about what happens outside the happy path: retries, restarts, stale state, partial failure, authorization boundaries, and whether a system can explain why it made a decision.

<table>
<tr>
<td valign="top" width="50%">

**What I focus on**

- Reliable backend systems under real workloads
- AI pipelines with explicit quality and policy gates
- Durable state, recovery, and idempotent execution
- Security and observability as system properties

</td>
<td valign="top" width="50%">

**How I work**

- Design for failure before polishing the demo
- Prefer explicit routing and state transitions
- Bound model authority with deterministic controls
- Treat evidence, telemetry, and recovery as first-class

</td>
</tr>
</table>

---

## ⟡ Building

### 🔮 Shoracle — AI Copilot for Shopee Sellers

> My main commercial project: a suggestion-first copilot that turns approved shop knowledge and relevant buyer context into reviewable replies inside the Shopee workflow — while the seller keeps final authority.

- **Suggestion-first workflow** — captures the right conversation context, retrieves shop-approved evidence, generates a bounded suggestion, and lets the seller accept, edit, reject, or handle the reply manually
- **Grounded and fail-safe** — answers from approved facts, FAQ, policy, product specs, and tone; weak evidence, wrong-shop state, stale context, or insufficient authority stops the path instead of encouraging a guess
- **Clear trust boundaries** — the MV3 extension owns the Shopee browser session, local state, seller-visible UI, and final decision; the Fastify backend owns signed LLM/RAG, knowledge processing, license/config, and never needs marketplace session material
- **Evidence-driven rollout** — local-first runtime state plus accept/edit/reject signals support real-shop dogfooding and a small design-partner cohort; broader automation remains separately gated by seller opt-in, per-intent thresholds, canary rollout, kill-switch, and rollback

<sub>`TypeScript` · `Chrome MV3` · `Fastify` · `IndexedDB/Dexie` · `LLM + RAG`</sub> &nbsp;·&nbsp; **Active private development** &nbsp;·&nbsp; 🔒 Private source

### 🧭 [Marketing Practitioner](https://github.com/quocbao201104/marketing-practitioner) — Decision-first Marketing for AI Agents

> An installable open-source Agent Skill for marketing work that needs stronger decision discipline: preserve what is already resolved, identify the open decision, load only relevant knowledge, and keep outputs inside the available evidence.

- **Decision-first runtime** — classifies the current job, freezes approved state, names the unresolved decision, and avoids reopening strategy just because the final artifact is copy, email, a platform post, or a commerce task
- **Addressable JIT knowledge** — logical knowledge IDs route agents to the smallest useful handbook, platform, commerce, or adaptation section; the current index validates at **252 routes / 225 evidence sources**
- **Evidence and claim discipline** — keeps observation, interpretation, attribution, causality, commercial state, platform signals, local evidence, and product truth distinct instead of silently upgrading weak evidence into stronger claims
- **Portable and locally extensible** — host-aware guidance covers Claude Code, ChatGPT, Cursor, and Codex, while scoped adaptation units specialize existing decisions without turning the repository into country packs or a cultural encyclopedia
- **Research with explicit limits** — adversarial reviews, routing checks, and behavioral pilots report what they actually establish; the project records unresolved or non-advantage results instead of treating passing tests as universal proof

<sub>`Agent Skill` · `Python tooling` · `JIT Knowledge Routing` · `Marketing Research` · `Localization` · `Evaluation`</sub> &nbsp;·&nbsp; **v1.2.0 · Building in public** &nbsp;·&nbsp; 🌐 [MIT-licensed open source](https://github.com/quocbao201104/marketing-practitioner)

---

## ⟡ Shipped

### 🎧 [TruyenVietHay](https://github.com/quocbao201104/TruyenVietHay) — Content & Audio Platform

> A completed full-stack Vietnamese reading and audio platform built around CDN-backed content delivery, realtime features, background processing, and mobile-first UX.

- Static chapter/audio delivery through object storage + CDN while the API serves metadata and application state
- Redis-backed background jobs for batched counters, statistics, reconciliation, cleanup, rewards, and ranking workloads
- Realtime chat/notifications, PWA support, JWT + Google OAuth, rate limiting, and production deployment tooling
- Separate media/content paths for image, JSON, and audio-heavy workloads instead of pushing everything through the application server

<sub>`Vue 3` · `TypeScript` · `Node.js` · `MySQL` · `Redis` · `Cloudflare R2` · `Cloudinary`</sub> &nbsp;·&nbsp; **Completed system** &nbsp;·&nbsp; 🌐 [Public source](https://github.com/quocbao201104/TruyenVietHay)

---

## ⟡ Researching

### 🔬 Trustworthy Agentic Systems

> An ongoing research track on state integrity in long-lived AI agents: provenance, authority, temporal correctness, durable execution, and the gap between rich runtime traces and governance-relevant interfaces.

- Separates established foundations from agent-specific hypotheses instead of assuming novelty
- Uses falsification-first gates: weak ideas are narrowed or abandoned rather than rescued after the fact
- Current benchmark work studies whether an already-produced action can still be bound to the exact committed external effect occurrence after crash/recovery boundaries
- Freezes claims, implementation, held-out evaluation, and adjudication rules before observing authoritative results

<sub>`Python` · `Agent Runtimes` · `Durable Execution` · `Provenance` · `Benchmarking`</sub> &nbsp;·&nbsp; **Research in progress** &nbsp;·&nbsp; 🔒 Private until release

---

## ⟡ Explored

### 📊 MarketGap — Product Opportunity Intelligence

> A paused product/R&D track for finding products with promising source-market signals on 1688 that still face limited competition on Shopee Vietnam.

- Engine pipeline: source crawling → deduplication → translation → Shopee image/market matching → supply enrichment → evidence-backed scoring and decisions
- Opportunity scoring combines demand, visual gap, estimated margin, local-market gap, competition pressure, data confidence, and explicit risk signals
- Separate SaaS consumes a versioned engine contract and provides auth, subscriptions, billing, opportunity exploration, watch/reserve workflows, and market radar

<sub>`Python` · `Vision / pHash` · `Next.js` · `TypeScript` · `PostgreSQL` · `payOS`</sub> &nbsp;·&nbsp; **Paused** &nbsp;·&nbsp; 🔒 Private source

---

## ⟡ Open Engineering

These are smaller or more inspectable public artifacts that show additional engineering work beyond the primary projects above.

- **[BAO.OS / Portfolio](https://github.com/quocbao201104/quocbao201104.github.io)** — interactive portfolio with command routing, multiple RAG modes/personas, Supabase pgvector retrieval, local deterministic embeddings, an OpenAI-compatible API surface, and server-side redaction boundaries; live LLM/RAG is currently disabled on the public deployment.
- **[CD1-2](https://github.com/quocbao201104/CD1-2)** — Linux security monitoring lab combining Suricata, Wazuh, deterministic correlation/risk scoring, local IsolationForest signals, evidence-aware explanations, and controlled response policy.
- **[Audio Ingest](https://github.com/quocbao201104/Audio-Ingest)** — queue-based YouTube audio ingestion pipeline using Redis workers, FFmpeg, object storage, recovery paths, and database synchronization.

---

## ⟡ Capabilities

| Area | Stack |
|------|-------|
| **Languages & Runtime** | ![Node.js](https://img.shields.io/badge/Node.js-0F6E56?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-0F6E56?style=flat-square&logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-0F6E56?style=flat-square&logo=python&logoColor=white) |
| **Backend & Security** | ![Express](https://img.shields.io/badge/Express-534AB7?style=flat-square&logo=express&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-534AB7?style=flat-square&logo=fastify&logoColor=white) ![JWT](https://img.shields.io/badge/Auth-JWT_·_OAuth2_·_RBAC-534AB7?style=flat-square&logo=jsonwebtokens&logoColor=white) |
| **Data & Processing** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1F6FEB?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-1F6FEB?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-1F6FEB?style=flat-square&logo=redis&logoColor=white) ![Queues](https://img.shields.io/badge/Queue_Systems-1F6FEB?style=flat-square) |
| **AI & Agents** | ![LLM](https://img.shields.io/badge/LLM_Pipelines-7F77DD?style=flat-square) ![RAG](https://img.shields.io/badge/RAG-7F77DD?style=flat-square) ![Agents](https://img.shields.io/badge/Agent_Runtimes-7F77DD?style=flat-square) |
| **Infra & Storage** | ![Cloudflare R2](https://img.shields.io/badge/Cloudflare_R2-F38020?style=flat-square&logo=cloudflare&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-F38020?style=flat-square&logo=cloudinary&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-F38020?style=flat-square&logo=vercel&logoColor=white) |

---

## ⟡ GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=quocbao201104&theme=radical" alt="GitHub contribution activity" />
</p>

---

<p align="center">
  <sub>Open to backend / AI systems roles where reliability actually matters &nbsp;·&nbsp; <a href="mailto:quocbao201104@gmail.com">reach out</a></sub>
</p>
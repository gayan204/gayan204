<h1 align="center">G.P.K. Gunawardana</h1>

<p align="center">
  Full-stack developer from Sri Lanka — I build and run the software small businesses operate on.
</p>

<p align="center">
  <a href="https://yaga.lk"><img src="https://img.shields.io/badge/yaga.lk-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="yaga.lk" /></a>
</p>

---

### About

I design, build and operate business systems end to end — point-of-sale, licensing,
messaging automation, and the infrastructure underneath them. Most of my work lives in
private client repositories, so this page is a summary of what I build rather than a
gallery of public code.

I prefer owning the whole stack: writing the application, containerising it, shipping it
through CI, and keeping it alive in production.

---

### What I build

**🛒 Multi-tenant POS platform**
Point-of-sale for retail shops, with an isolated database per tenant, a web front end, and
automated nightly backups. Adding a new shop is a deployment, not a rewrite.

**🔑 Software licensing portal**
Issues and validates licences for deployed products, with its own admin interface and database.

**💬 WhatsApp automation**
Order confirmations, billing notifications and chatbot flows built on self-hosted
WhatsApp HTTP APIs.

**⚙️ Workflow automation**
n8n pipelines connecting POS, messaging and internal tools — with separate staging and
production environments so changes are tested before customers see them.

**📋 Internal tooling**
Kanban board, document/PDF generation services, and the company website.

---

### Infrastructure

I run production myself rather than leaning on managed platforms:

| | |
|---|---|
| **Containers** | Docker Compose — ~25 services on a single Linux host |
| **Web** | Nginx · Nginx Proxy Manager · Let's Encrypt TLS · Cloudflare |
| **Data** | PostgreSQL · encrypted nightly backups synced off-site |
| **Delivery** | GitHub Actions deploying over SSH to production |
| **Security** | UFW · Fail2ban · key-only SSH · per-service isolation |

---

### Tech

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

<p align="center">
  <sub>Building from Sri Lanka 🇱🇰 · <a href="https://yaga.lk">yaga.lk</a></sub>
</p>

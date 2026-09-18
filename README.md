<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=650&height=70&lines=Hey+there%2C+I'm+Uday+Shankar+Purbey+%F0%9F%91%8B;Angular+%26+Node.js+Developer;Full+Stack+Developer;Tech+Enthusiast+%F0%9F%9A%80" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://github.com/udayshankarpurbey"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/uday-shankar-purbey"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/udayshankarpurbey"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="https://udaykumarpurbey.netlify.app/"><img src="https://img.shields.io/badge/Portfolio-36BCF7?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio" /></a>
</p>

---

## 🧑‍💻 About Me

I'm a passionate **Frontend + Backend Developer** who loves turning clean code into powerful, scalable applications. I specialize in **Angular** on the frontend, and I also work on the backend using **Node.js**, **Express**, and **MySQL**.

Since **October 2023** I've been at **Naxtre Technologies Pvt. Ltd.** as a **Software Developer**, contributing to production-grade web apps across election analytics, logistics, field-service operations, lead generation and content platforms.

---

## 🚀 What I Do

- Build **SPA**s and server-rendered apps with **Angular**, **React** and **Next.js**
- Develop and maintain **REST APIs** with Node.js & Express, in JavaScript and TypeScript
- Design and manage databases across **MySQL**, **SQL Server**, **MongoDB** and **PostgreSQL**
- Integrate **third-party and AI services** — Claude, OpenAI, Ollama, Apollo.io, payment and telephony gateways
- Write **Python** for scraping, data extraction and automation pipelines
- Collaborate in Agile teams to deliver clean, scalable code

---

## 💼 Career Timeline

### 🏢 Naxtre Technologies Pvt. Ltd.

**Software Developer** &nbsp;·&nbsp; 📍 Mohali, India &nbsp;·&nbsp; 🗓️ `Oct 2023 – Present`

Shipped full-stack features across **15+ production products** — election analytics and campaign tooling, logistics, field-service operations, lead generation and content platforms — owning Angular/React frontends and Node.js backends in agile teams.

**Impact at a glance**

| Area | Result |
|---|---|
| 🚀 Products shipped | 15+ production client applications |
| ⚡ API performance | ~35% faster average response time |
| 🧩 UI development | 30% faster via shared, lazy-loaded component libraries |
| 🔗 Team integration | 40% fewer integration bugs through defined API contracts |
| 📈 Scale | REST APIs handling 1,000+ daily requests |
| 🔐 Security | RBAC + JWT authentication for tier-specific data access |

<br>

#### 📂 Project timeline

<details>
<summary><b>🗳️ Voter Campaign Dashboard</b> &nbsp;·&nbsp; <code>2023 – 2026</code> &nbsp;·&nbsp; <i>Angular · Node.js · SQL Server · MongoDB · Redis · Python</i></summary>
<br>

**Role:** started by assisting a senior developer on an in-flight platform, then took ownership of the campaign, calling, scraping and reporting modules across the frontend and backend. This is the core of Naxtre's election-intelligence work; the **PeoplesInsight platform** below — including Bengal War Room, PI Command Center and the Punjab media-intelligence backend — is the sister programme, where I built the AI analysis layers on the **Claude API** and local LLMs via Ollama.

- Integrated **four third-party OBD / IVR calling panels** behind one interface — **VoiceNSMS**, **Smartping Trans-Promo**, **Smartping Autodialer** and **Vi CPaaS** — with webhook handling, voice-file upload and per-provider report reconciliation.
- Built the **OTPSP / OBD outbound-calling pipeline**: CSV ingestion, batch splitting for large number groups, campaign-name generation, bulk pause/stop/resume, and **DND staging with retry** for failed campaigns.
- Built the **volunteer marketing module** end to end as its sole author — a separately-guarded portal for bulk SMS outreach via the Smartping SPARC gateway, with **TRAI DLT compliance** (registered content and principal-entity IDs), per-message delivery tracking in SQL Server, campaign reports and volunteer sign-up capture behind short-link CTAs.
- Built the **data-extraction layer** pulling live results from the ECI site, state result portals and SECC sources — round-wise votes, postal votes and counting-day status — so the analysis team always had current numbers.
- Owned the **data-cleaning pipeline**: party and state abbreviation normalisation, DTMF response modification, and short-form converters that turn inconsistent multi-source feeds into one queryable schema.
- Added **background job processing** with real-time progress tracking, persistence and resume, plus Redis caching, bulk SQL insertion and activity logging for throughput and auditability.

🔗 [Voter portal](http://voter.peoplesinsight.in/)

</details>

<details>
<summary><b>📊 PeoplesInsight — Election Intelligence Platform</b> &nbsp;·&nbsp; <code>2024 – 2026</code> &nbsp;·&nbsp; <i>Angular · React · Node.js · SQL Server · MongoDB · Claude API · Ollama</i></summary>
<br>

**Role:** full-stack across the whole product family — **seven applications**. Sister programme to the Voter Campaign Dashboard above; together they make up Naxtre's election-intelligence stack.

---

**🌐 Website & Content API** &nbsp;·&nbsp; `2024 – 2026` &nbsp;·&nbsp; [live](https://peoplesinsight.in/)

- Built assembly, booth, candidate and constituency pages, election results and press coverage, with a `ReadMoreButton` pattern for progressive loading.
- Added **unique SEO-slug validation** on blog create *and* update in the Node API, and built press-release CRUD end to end.
- Replaced the `ngx-wrapper-tiny-slider` dependency with a custom slider and migrated image delivery to a new **S3 bucket**.
- Authored the site's `llms.txt` so AI crawlers get an accurate company and services overview.

**🗂️ Self-service CMS** &nbsp;·&nbsp; `2024 – 2026` &nbsp;·&nbsp; [admin](https://admin.peoplesinsight.in/)

- Delivered CRUD modules for blog, press release, gallery, video and election results, with **drag-and-drop ordering**.
- Added **lazy-loaded routes** to cut initial bundle size and refactored services for stronger type safety.
- Hardened the build by **removing hardcoded AWS credentials** from environment files.

**🎙️ Voice Dashboard** &nbsp;·&nbsp; `2024 – 2026` &nbsp;·&nbsp; [dashboard](https://dashboard.peoplesinsight.in/)

- Contributed to the dashboard used to build and configure automated voice campaigns — dynamic script builder, **Sarvam TTS** integration and Excel-driven campaign lists.

**📈 Prediction Tracker** &nbsp;·&nbsp; `Jun – Dec 2025` &nbsp;·&nbsp; *sole developer* &nbsp;·&nbsp; [live](http://prediction.peoplesinsight.in/)

- Built **round-wise and assembly-wise prediction analysis**, a statewise round analysis page and an AC-wise round component.
- Implemented result maps and live-result views with round conclusions and winning-margin summaries.
- Wrote the **Excel parser service** and configurator that ingest prediction datasets.

**🧭 PI Command Center** &nbsp;·&nbsp; `Mar 2026` &nbsp;·&nbsp; *sole developer*

- Bootstrapped an Express + Redis backend with **Claude API integration** and MSSQL-backed authentication.
- Built the **manifesto tracker**, voter-concerns, party-position-matrix, party-narrative and leader-meeting endpoints.
- Implemented **async prompt processing with job tracking** so long AI generations run off the request cycle.
- Built the React client — intelligence module, analytics, alerts, sitrep and media pages behind protected routes.

**🗺️ Bengal War Room** &nbsp;·&nbsp; `Mar 2026` &nbsp;·&nbsp; *sole developer*

- Built the war-room dashboard: **AC intelligence grid**, vote-share visualisation, seat projection and a battleground watch panel with live refresh.
- Modelled the domain end to end — AC sentiment, battlegrounds, demographics, swing analysis, force deployment, intel feed and strategy.
- Used the **Claude API** to generate battleground status, swing and vote-share analysis and demographic breakdowns as structured political insight.
- Implemented winner calculation across the 2021 and 2026 elections over SQL Server, plus an embedded Power BI tab.

**📡 Punjab — Media Intelligence Backend** &nbsp;·&nbsp; `May – Jun 2026` &nbsp;·&nbsp; *sole developer*

- Built ingestion and analysis across **Twitter, YouTube and news sources**, with tag mapping, party surveys and virality scans.
- Ran **sentiment analysis through Ollama** (local LLMs), adding generic sentiment plus extra dimensions, with **concurrency control** on tweet classification.
- Optimised emotion-count retrieval using **CTEs and pivoting**, with region-based breakdowns and percentage calculations.
- Built the alerting layer with trend analysis and detailed emotion alerts, plus promise-tracking (`vachan`) runs.

</details>

<details>
<summary><b>🚛 RoseRocket — Transport Management System</b> &nbsp;·&nbsp; <code>Oct 2024 – Jan 2025</code> &nbsp;·&nbsp; <i>Angular · TypeScript</i></summary>
<br>

**Role:** frontend — primary developer on the Angular client.

- Built the order section and order-mapping screens, member management (profiles, status, detail editing) and the broker/supplier views.
- Built the **notification system** UI — add-user notifications, the all-notifications feed and report notifications.
- Delivered quotes, billing and make-payment screens, plus map views for dispatch tracking.
- Added a global content-loader pattern and CSV/Excel export hooks used across the dashboard.

🔗 [Case study](https://www.naxtre.com/case-study/texpress-transport-management-solution)

</details>

<details>
<summary><b>🧹 Cleaning Staff Management</b> &nbsp;·&nbsp; <code>May – Jun 2025</code> &nbsp;·&nbsp; <i>Angular · Node.js · Express · MySQL</i></summary>
<br>

**Role:** full-stack — effectively sole developer across frontend and backend.

- Built **QR-based attendance** with check-in/check-out records and automated validation.
- Delivered checklists, questionnaires and questionnaire responses, certificates and training-material modules, each with assignment flows.
- Added site and client **category filters**, bulk file upload, and a client-facing certificate view.
- Built the report service and image generator used for site inspection summaries.

</details>

<details>
<summary><b>🎯 Lead Scouting & Konneto CRM</b> &nbsp;·&nbsp; <code>Jun – Oct 2025</code> &nbsp;·&nbsp; <i>Angular · Node.js · Python · Selenium · OpenAI · Apollo.io</i></summary>
<br>

**Role:** full-stack — primary developer on the Angular scouting client and its Python scraping backend, and **backend developer on Konneto**, the sales CRM the leads feed into, where I owned the lead module and its data integrations.

- Built the lead dashboard, lead table and lead-profile views, with client details and Clutch-sourced company data.
- Wrote Python extractors for **LinkedIn, Clutch reviews, sitemaps and company-name-by-tag** lookups to build the lead database.
- On **Konneto**, owned the lead controller, model and routes, and built the **Apollo.io integration** — company search, organisation lookup by ID and people search — enriching every lead with firmographic and contact data.
- Integrated the **OpenAI API** (GPT-5) to qualify scraped leads and generate tailored outreach mail, with runtime model selection for generation.
- Added a **scheduler** for scouting runs with extended timeouts, plus CSV download, Excel parsing and templated mail with test-send support.

</details>

<details>
<summary><b>👥 Staff / Task Management Dashboard</b> &nbsp;·&nbsp; <code>Dec 2025 – Feb 2026</code> &nbsp;·&nbsp; <i>Node.js · Express · MySQL · React</i></summary>
<br>

**Role:** backend — owned the Node/Express API behind the internal staff portal.

- Built modules for employees, clients, **daily tasks**, projects and project categories, and employee-project assignment.
- Added **milestones and objectives** tracking for performance review, plus a notice board and sticky notes for team communication.
- Built the email-template engine and the aggregated dashboard endpoint powering the charts.
- Delivered paginated, filterable endpoints to keep data-fetch latency low across 100+ employees.

🔗 [Live portal](http://emp.naxtre.com/)

</details>

<details>
<summary><b>🛠️ ServiceOps — Field Service & Safety Inspection</b> &nbsp;·&nbsp; <code>Jun – Jul 2026</code> &nbsp;·&nbsp; <i>Next.js · TypeScript · Node.js · MongoDB · AWS S3</i></summary>
<br>

**Role:** full-stack — worked across the TypeScript backend and Next.js CMS of this safety-inspection platform.

- Implemented **timezone-aware site scheduling** end to end: timezone support on sites, a `Time-Zone` header driven by the user's locale, and duration formatting to match.
- Made **geocoding best-effort** on client create/update so a geocoding failure can never block the write.
- Migrated the **AWS SDK to v3** and removed static credentials in favour of an **EC2 IAM role** for S3 access; fixed Cloudinary config and validation error handling.
- Reworked checklist mandatory-item logic, added questionnaire versioning redirects, and handled the Safety Inspection → **ServiceOps rebrand** across the CMS.

🔗 [ServiceOps](https://serviceops.naxtre.com/)

</details>

<details>
<summary><b>🏢 Naxtre — Company Website, Admin & Backend</b> &nbsp;·&nbsp; <code>Jun – Sep 2026</code> &nbsp;·&nbsp; <i>Angular · Node.js · Express · MongoDB · AWS</i></summary>
<br>

**Role:** contributor across the three repos (website, admin CMS and Node backend) of an established codebase.

- Built the **digital marketing services page** with SEO optimisation, a lead form and audit-request submission, and added it to the sitemap.
- Built the **IoT landing page** with SEO and theme handling, and implemented **route-based theme switching** across the site.
- Restructured the header navigation categories and added Google site verification.
- On the admin and backend side: improved deck **PDF upload validation**, and moved AWS access off hardcoded credentials onto environment variables and an **EC2 IAM role**.

🔗 [naxtre.com](https://www.naxtre.com/)

</details>

<details>
<summary><b>📖 The Perfect Stories</b> &nbsp;·&nbsp; <code>Jul – Sep 2026</code> &nbsp;·&nbsp; <i>WordPress · PHP · Node.js · TypeScript · PostgreSQL</i></summary>
<br>

**Role:** sole developer of the admin agent, plus the contributor platform.

- Built the contributor flow on the WordPress site: **registration, login and a contributor dashboard** for submitting stories.
- Built a **rules-based admin agent** (deterministic, no LLM) that reviews submissions against the contribution guidelines, applies internal-link and SEO fixes, and marks valid posts *Ready for Publication* — batched, with confirmation before anything is trashed.
- Built the **Instagram automation pipeline**: a nightly image queue, an AI image worker with ranking, a reels pipeline with Cloudinary upload and GPU render queue, and trending-audio selection with music beds ranked by tone.
- Automated the daily digest and IG scheduling on `node-cron`, backed by PostgreSQL with email delivery via Nodemailer.

🔗 [theperfectstories.com](https://www.theperfectstories.com/)

</details>

<br>

### 🚀 Independent / Freelance

Work taken on outside of Naxtre.

<details>
<summary><b>🪔 Mahamaya — Incense Brand Website</b> &nbsp;·&nbsp; <code>Jul – Sep 2026</code> &nbsp;·&nbsp; <i>Next.js · React · next-intl</i></summary>
<br>

**Role:** sole developer — built and shipped independently.

- Built a **five-language storefront and content site** (English, Hindi, Arabic, German and French) on Next.js with `next-intl`, including language and currency switchers for international visitors.
- Built a **markdown-driven content system** (`gray-matter` + `react-markdown`) publishing SEO content clusters on incense craft, festivals and rituals across every locale.
- Built the collections browser, enquiry form, newsletter signup and chat widget that drive enquiries.
- Added **JSON-LD structured data**, consent-aware analytics and systematic internal-linking passes to grow organic search visibility.

🔗 [Repo](https://github.com/udayshankarpurbey/mahamaya-website)

</details>

<details>
<summary><b>🖨️ DevkalaPrint — Online Printing Service</b> &nbsp;·&nbsp; <code>Jun 2026</code> &nbsp;·&nbsp; <i>React · Node.js · Express · MongoDB · Razorpay · Cloudinary</i></summary>
<br>

**Role:** helped a friend ship the payment layer of his printing-service platform.

- Integrated **Razorpay checkout** end to end: order creation on the Express backend and payment handling wired through the `ServiceDetails` and `OrderSuccess` React pages.
- Replaced the hardcoded Razorpay script tag with a **dynamic loader**, so the SDK loads on demand instead of on every page.
- Added a **payment-in-progress guard** preventing duplicate submissions during checkout.
- Handled **dynamic pricing and GST** in the payment flow, and fixed the build scripts that were breaking the Render deploy.

🔗 [Repo](https://github.com/udayshankarpurbey/DevkalaPrint)

</details>

<details>
<summary><b>🚗 Vehicle Info PUC</b> &nbsp;·&nbsp; <i>Backend Developer</i></summary>
<br>

**Role:** backend developer on the Android app's server side — an independent engagement, outside my work at Naxtre.

- Built and maintained the REST API layer backing the mobile client.

🔗 [Play Store (internal test track)](https://play.google.com/apps/test/vehcileinfoPUC.com/4)

</details>

<br>

### 🎓 Gandhi Institute for Education and Technology

**B.Tech in Computer Science & Engineering** &nbsp;·&nbsp; BPUT, Odisha &nbsp;·&nbsp; 🗓️ `2020 – 2024` &nbsp;·&nbsp; **CGPA 8.21**

---

## 🛠️ Tech Toolbox

**Frontend:**

![Angular](https://img.shields.io/badge/-Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![RxJS](https://img.shields.io/badge/-RxJS-B7178C?style=flat&logo=reactivex&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat&logo=next.js&logoColor=white)

**Backend:**

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/-Express.js-000000?style=flat&logo=express&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Tools & Platforms:**

![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)
![npm](https://img.shields.io/badge/-npm-CB3837?style=flat&logo=npm&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Postman](https://img.shields.io/badge/-Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![VSCode](https://img.shields.io/badge/-VSCode-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

---

## 🌟 Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**EHealthVault**](https://github.com/udayshankarpurbey/EHealthVault) | Digital platform to securely store, manage and share personal medical history and documents. | Node.js · Astro |
| [**WalletIQ**](https://github.com/udayshankarpurbey/WalletIQ) | Smart personal-finance app to track expenses, savings and money habits. | Full Stack |
| [**Trycoon-Trails**](https://github.com/udayshankarpurbey/Trycoon-Trails) | Lightweight trials platform for sharing and reviewing product try-on experiences. | Full Stack |
| [**random-color-picker**](https://github.com/udayshankarpurbey/random-color-picker) | Lightweight npm utility that generates random colors for your applications. | npm package |
| [**todo_sample**](https://github.com/udayshankarpurbey/todo_sample) | Full-stack todo app built with Angular 21 and Node.js. | Angular · Node.js |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=udayshankarpurbey&show_icons=true&theme=tokyonight" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=udayshankarpurbey&layout=compact&theme=tokyonight" width="48%" />
</p>

---

## 🌱 Currently Exploring

- **Flutter** — building cross-platform apps (state persistence, animations, local storage with sqflite) 📱
- Building & publishing reusable npm packages 📦
- Python (for scripting and automation) 🐍
- Clean Code, Design Patterns
- Backend architecture with Node.js
- Modern Angular (Signals, standalone components)

---

## 📫 Let's Connect

- 🐙 **GitHub** — [github.com/udayshankarpurbey](https://github.com/udayshankarpurbey)
- 💼 **LinkedIn** — [linkedin.com/in/uday-shankar-purbey](https://linkedin.com/in/uday-shankar-purbey)
- 🧩 **LeetCode** — [leetcode.com/u/udayshankarpurbey](https://leetcode.com/u/udayshankarpurbey)
- 🌐 **Portfolio** — [udaykumarpurbey.netlify.app](https://udaykumarpurbey.netlify.app/)
- 📧 **Email** — purbeyudaykumar@gmail.com

---

## ✨ Fun Facts

- 👨‍🎓 Proud BPUT grad
- 🎨 UI/UX minimalist
- 🧩 Loves debugging weird edge cases
- 🎮 Gaming + tech podcasts are my go-to weekend ritual

---

> _"First, solve the problem. Then, write the code."_ – John Johnson

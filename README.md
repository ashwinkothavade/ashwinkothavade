<h1 align="center">Ashwin Kothavade</h1>
<h3 align="center">Software Engineer @ Akatsuki AI Technologies, Tokyo · Owning AI products end-to-end on GCP</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ashwinkothavade-696a21257/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://ashwinkothavadeportfolio.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=netlify&logoColor=white" />
  </a>
  <a href="mailto:ashwinkothavade@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/ashwin190304/">
    <img src="https://img.shields.io/badge/LeetCode%20Knight%202043-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://drive.google.com/file/d/1godoh0kkJkSwrpWOL-TszM2D2pIGuKHk/view?usp=sharing">
    <img src="https://img.shields.io/badge/Resume-2F855A?style=for-the-badge&logo=googledrive&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ashwinkothavade&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### About

Software Engineer at **Akatsuki AI Technologies (Tokyo)**, where I own **two flagship AI products end-to-end** — from the first line of code to production and operations on Google Cloud.

I joined as an intern when annual revenue was **¥10M**; the products I built and now lead helped grow it to **¥280M within a year — a 28× jump**. The throughline of my work: turning promising prototypes into products that hold up in production and move revenue.

- Final-year **B.Tech CSE @ IIITDM Jabalpur** (2022–2026), CPI **8.9**
- **Knight on LeetCode** — rating 2043, top **2.5%**, **850+** problems solved
- Building in **AI · Cloud · DevTools · Infra** — open to full-time and contract work
- Reach me at **ashwinkothavade@gmail.com**

---

### Experience

**Software Engineer — [Akatsuki AI Technologies](https://aktsk.jp/) (Talendy Holdings)**, Tokyo · _Jun 2026 – Present_

Own two flagship products end-to-end — from first feature to production on Google Cloud. These products helped grow annual revenue **28× (¥10M → ¥280M)**.

- **Honyaku** ([honyaku.aktsk.ai](https://honyaku.aktsk.ai)) — took an AI translation tool from single-tenant prototype to a production **multi-tenant SaaS** that translates English↔Japanese text, images, and PDFs inside Slack. Built the multi-tenancy layer (Slack OAuth, **AES-256** encrypted tokens, JWT), **Stripe** subscription billing, per-workspace usage metering, an event-driven **Gemini + Cloud Vision** pipeline, an internal ops console, and the full monitoring stack on **GCP Cloud Run**.
- **Red Baron** (client) — a full-stack **AI motorcycle appraisal + flyer platform** (**Vertex AI Gemini, YOLOv8, Playwright**) that renders print-ready **30-vehicle PDF flyers in under a minute**, deployed on GCP via **Terraform** behind Google Workspace SSO.

**Software Engineer Intern — Akatsuki AI Technologies**, Tokyo · _Oct 2025 – May 2026_

Built the platform, security, and data foundations the company's revenue products shipped on.

- **KDDI AI marketing platform** (client) — led the DevOps workstream: **2,400+ lines of Terraform** for a secure multi-environment GCP setup (Cloud Run, private Cloud SQL, VPC, **Cloud Armor**), **Workload Identity Federation** CI/CD, and multi-region Gemini failover.
- **Security pipeline** — a reusable **4-stage automated scanner** (Gitleaks, Trivy, Semgrep, Checkov + AI review) on Cloud Build, catching leaked secrets, CVEs, and misconfigurations before production — adopted across every repo.
- **Carreros** — a job-search product aggregating **144k+ listings across all 47 Japanese prefectures** into **Azure AI Search** with 25+ filters, served via Azure Functions + React.

**Backend Intern — [smallcase](https://www.smallcase.com/)**, APAC · _Oct 2025 – Feb 2026_

Backend engineer on the loan-against-mutual-funds platform (Go, MongoDB, Redis), shipping security and reliability features across the South Indian Bank integration.

- **Closed an open cost leak** — built a two-stage **Bank Verification API** (Penny Drop + Name Match). Each penny drop is a paid bank call and the flow was previously unbounded; added abuse guards (max 10 attempts, auto-block after 3 failures), encrypted PII, and submission gating — blocking payouts to invalid accounts.
- **Cut DB load** with a Redis caching layer for ~**8k ISINs** of mutual fund data: batch MGET reads, pipelined writes, non-blocking SCAN invalidation, 90-min TTL, non-fatal on cache failure.

**Software Engineering Intern (Full Stack) — [Mobile Premier League (MPL)](https://www.mpl.live/)**, Pune · _Jun 2025 – Aug 2025_

- Designed and shipped full-stack features on a scalable **Data Engineering Platform** (React + Spring Boot, RESTful APIs).
- Integrated **Kafka + Apache Camel** for real-time streaming across microservices; added **gRPC** inter-service communication to reduce latency.

**Software Engineering Intern (C4GT DMP'25) — Argusoft (MedPlat)**, Remote · _May 2025 – Aug 2025_

Open-source contributor on a Digital Public Good — selected **top 100 of 4,200+ applicants**.

- Built **7+ interactive dashboards** in React.js with a reusable component-based architecture (Hooks + Context API).
- Integrated an **AI-powered query system** serving **100+ real-time requests/day**, cutting data reporting time by **40%**.

**Backend & Research Intern — IIITDM Jabalpur** · _Dec 2023 – Nov 2024_

- Owned the **elective allocation algorithm** for the College ERP Portal serving **3,000+ users**; migrated the frontend from Django templates to React.
- Analyzed network logs with **CICFlowMeter** to detect security threats at **97% accuracy**; visualized attacks in Grafana covering **70%+** of known malware methods.

---

### Featured Projects

| Project | Description | Tech |
| --- | --- | --- |
| **[Honyaku](https://honyaku.aktsk.ai)** | Production multi-tenant Slack translation SaaS — Slack OAuth, Stripe billing, per-workspace usage metering, event-driven AI pipeline. | `Next.js` · `Node.js` · `Gemini` · `Stripe` · `Cloud Run` |
| **Red Baron** | AI motorcycle appraisal + flyer platform rendering print-ready **30-vehicle PDF flyers in under a minute**. | `FastAPI` · `Next.js` · `YOLOv8` · `Vertex AI` · `Terraform` |
| **MedPlat AI Dashboard Builder** | Natural-language dashboard builder letting non-technical health teams ship dashboards autonomously. Open source (C4GT'25). | `React` · `NLP` · `DPG` |
| **CyberFortress** | API security & inventory framework wired into CI/CD — flagged **15/16 APIs** secure, **60% OWASP API Top 10** coverage. | `Jenkins` · `Security` · `OWASP` |
| **IoT Anomaly Detection** | ML pipeline detecting network threats at **97% accuracy**, visualized end-to-end. | `CICFlowMeter` · `Prometheus` · `Grafana` |

---

### Achievements

- Helped grow product revenue **28× (¥10M → ¥280M)** in one year at Akatsuki
- **Knight on LeetCode** — rating 2043, top 2.5%, 850+ problems solved
- **Top 100 of 4,200+** applicants — C4GT DMP 2025
- **Flipkart GRiD 6.0 Semifinalist** (Top 22 of 17,000+ teams) · **IIT Bombay TechFest Top 5**
- **AIR-1** — SOF International French Olympiad

---

### Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=go,ts,js,python,java,cpp,react,nextjs,nodejs,express,fastapi,spring,postgres,mongodb,redis,gcp,azure,terraform,docker,kubernetes,kafka,grpc,tailwind,git" />
</p>

---

### GitHub Stats

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ashwinkothavade&theme=tokyonight" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ashwinkothavade&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ashwinkothavade&theme=tokyonight&hide_border=true" />
</p>

---

<p align="center"><i>Open to teams building in AI, cloud, devtools, or infra — full-time or contract.</i></p>

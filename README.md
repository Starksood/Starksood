<div align="center">

# Sanyam Sood
### Backend Systems · Data Engineering · AI-Driven Products

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanyam--sood/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snym.sood@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Starksood)

</div>

---

### 👨‍💻 About Me

Senior at **Wayne State College** pursuing a dual degree: **B.S. Cybersecurity & B.Sc. Computer Science**. Backed by four years of professional analytics work at a national-scale organization, my current focus bridges foundational security principles with advanced computer science R&D. 

While actively engineering research-driven systems—ranging from deterministic AI memory substrates to enterprise-grade data pipelines—I am concurrently advancing my infrastructure and security expertise by working toward my **CompTIA Security+** and **CompTIA Network+** certifications.

---

## 🚀 Featured Engineering

---

### 🌸 Fireweed Fabric — Memory-First AI Architecture
> **In Development (Private Repo)** · [GitHub](https://github.com/Starksood/Fireweed) · `v15-redesign`
📊 Fireweed — Paper Verification Bundle
> **Public Archive** · [GitHub](https://github.com/Starksood/Fireweed_Fabric) Independent verification repository for the paper *"A Model-Independent Memory Substrate: Preserving an Agent's Account of a User Across LLM Swaps, Scales, and Families."*

Research system for **persistent, emotionally-weighted LLM memory** — architecturally distinct from RAG. A per-user **memory graph** accumulates structured claims across sessions; a fine-tuned memory operator proposes graph ops while deterministic Python enforces mutations and domain safety.

**Thesis:** *accumulation* (biological reinforcement) + *synthesis* (INFER/REFLECT) + *inhabitation* (respond from durable knowledge, not chunk lookup).

| Dimension | Details |
|---|---|
| **Memory Fabric** | Stateful node graph — CREATE / REINFORCE / MODIFY / DISPUTE / FREEZE; cosine dedup (≥0.94); WARM→HOT→CORE via strength `r`; idle decay `0.012×turns`; atomic snapshot I/O. |
| **v2.0 Substrate** | Affective valence `[-1,1]` modulates decay; **curiosity drive** surfaces diverse COLD nodes; **dual-process routing** gated on compliance + constitutional events. |
| **v16 Pipeline** | LLM emits normalized claims → **Memory Claim Firewall** → deterministic resolver. Extraction is strictly decoupled from mutation. |
| **Validation** | **320+ pytest** incl. Hypothesis property tests; ingestion trace harnesses. Benchmark against Mem0 + RAG ablation baselines. |
| **Stack** | Python · FastAPI · httpx · LM Studio/Ollama · TRL/PEFT fine-tune pipeline · Docker |

---

### 📈 CIM SEO Automation Platform
> **Enterprise Tooling (Private Repo)** · Analytics Orchestration · AI Intelligence

An enterprise-grade automation platform that orchestrates multiple monitoring and reporting workflows, unifying data from Google Analytics 4, Search Console, and PageSpeed Insights into a centralized, AI-enhanced intelligence pipeline for stakeholder decision-making.

| Dimension | Details |
|---|---|
| **Architecture** | Master orchestrator pattern routing to parallel API-based analytics pipelines and serial crawl-based technical workers. |
| **Data Ingestion** | Automated extraction from GA4 Data API, GSC API (queries, landings, ranking positions), and PageSpeed Insights (Core Web Vitals). |
| **Technical Audits** | Async crawler utilizing Playwright and BeautifulSoup for broken link detection, internal link structure analysis, and orphan page identification. |
| **AI Integration** | Groq (Llama-3.3-70b) integration to evaluate pages for AI-search readiness, hallucination risk, and executive summary generation. |
| **Data I/O & Sync** | Bidirectional syncing with Monday.com via GraphQL, historical persistence in Google Sheets, and automated multi-format output (PDF via WeasyPrint, HTML dashboards, CSV, Markdown). |
| **Stack** | Python 3.8+ · asyncio · Playwright · pandas · Groq SDK · Monday.com API · WeasyPrint |

---

### 🏎️ Redline — Collector Car Market Intelligence Platform
> **Live:** [www.redlineauto.click](https://redlineauto.click) · [API](https://principal-tallou-gavel-3718a78a.koyeb.app) · [Docs](https://principal-tallou-gavel-3718a78a.koyeb.app/docs)

A full-stack market intelligence platform aggregating sold auction data from **14+ sources**, routing it through a multi-factor decision engine to determine real-time vehicle viability and market trends.

| Dimension | Details |
|---|---|
| **Data Ingestion** | 8 concurrent async scrapers (BaT, Mecum, Barrett-Jackson, etc.) orchestrated via `asyncio.Semaphore(5)`. |
| **Decision Engine** | Deal Score (0–100) across 5 weighted factors + Viability Score formula with BUY / WAIT / PASS verdicts. |
| **Data Quality** | Stringent quarantine layer prior to DB upsert rejecting price anomalies, mileage outliers, and non-vehicle listings. |
| **Automation** | 11 scheduled GitHub Actions jobs handling daily scraping, normalization, AI summaries, SEO generation, and social distribution. |
| **Monetization** | Stripe-integrated tiered API (Free → $149/mo Business), Redis sliding-window rate limiting, SHA-256 key auth. |
| **Stack** | FastAPI · PostgreSQL (Neon) · Redis (Upstash) · React 18 / TypeScript · Vercel · Playwright · Groq |

---

## 🔬 Additional Projects

*   **[Alfred & AMMA](https://main.d2odyrogzbyuno.amplifyapp.com)**: AWS $10,000 AI Ideas Competition Semi-Finalist. A dual-agent AI architecture deployed on AWS automating ethical shopping workflows and personalized nutrition mapping.
*   **[Sovereign Administrative Suite](https://sovereign-suite-1kja.vercel.app)**: Full-stack SaaS platform utilizing JavaScript, Vercel, and REST APIs for legal & administrative paperwork automation.
*   **[The Forge](https://github.com/Starksood/the_forge/tree/main)**: Local, offline instruction-tuning dataset generator utilizing Ollama to convert source documents into strict `{system, user, assistant}` triples.
*   **[SHAMAN.OS](https://github.com/Starksood/Shaman.io)**: Voice-to-voice interaction loop with custom fine-tuned local models and live fractal visual generation.

---

## 🛠️ Technical Arsenal

| Category | Technologies |
|---|---|
| **Languages** | Python, JavaScript/TypeScript (ES6+), SQL, HTML5/CSS3 |
| **Backend & Orchestration** | FastAPI, asyncio, SQLAlchemy 2.x, Playwright, pandas |
| **Data & AI** | PostgreSQL, Redis, Groq (Llama-3.3-70b), Ollama, TRL/PEFT, TensorFlow, Scikit-learn |
| **Infrastructure & DevOps** | GitHub Actions (CI/CD), Koyeb, Vercel, AWS, Neon, Upstash, Docker |
| **Frontend** | React 18, Vite, Tailwind CSS, Recharts |
| **Security & Quality** | SHA-256 Auth, HMAC Verification, Rate Limiting, pytest, Hypothesis |

---

## 💼 Professional Experience

**Administrative Assistant** | *Camp Laurel South* (Casco, ME) · Summer 2026
*   Managed daily administrative operations, organizational workflows, and logistical support for a high-volume seasonal program.

**Digital Marketing & Web Optimization Specialist** | *CIM* (4 years)
*   Architected and maintained production analytics systems at a national scale.
*   Developed comprehensive Python/SQL data pipelines, orchestrated A/B testing infrastructure, and built automated executive dashboards.

**Agribusiness Intern** | *FarNorth Fungi* (Anchorage, AK)
*   Deployed a Computer Vision and IoT pipeline to establish real-time environmental monitoring for commercial mushroom cultivation. 
*   Optimized TensorFlow models to operate efficiently under constrained agricultural hardware conditions.

**Food Pantry Coordinator** | *Wayne State College* (2025 – Present)
*   Direct logistics and community operations management, ensuring continuous supply chain flow and equitable distribution.

---

## 🎓 Education & Credentials

**Wayne State College** (Expected 2027)
*   B.S. Cybersecurity
*   B.Sc. Computer Science 

**Professional Certifications**
*   **CompTIA Security+** (In Progress)
*   **CompTIA Network+** (In Progress)
*   **Data Science Professional Certificate** — IBM
*   **Machine Learning with Python** — IBM
*   **Financial Markets (Honors)** — Yale University
*   **Responsive Web Design** — freeCodeCamp

---

<div align="center">
  <sub>Building toward the future of secure, intelligent systems.</sub>
</div>

<div align="center">

# Sanyam Sood
### Backend Systems · Offensive Security · AI-Driven Products

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanyam--sood/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snym.sood@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Starksood)

</div>

---

### 👨‍💻 About Me

Senior at **Wayne State College** — Double Major - B.S. Cybersecurity + B.Sc Computer Science. Four years of professional analytics work at a national-scale organization; now building production systems at the intersection of data pipelines, decision engines, and AI.

I don't do toy projects. Everything I ship has real users, real data, and real infrastructure requirements behind it.

---

## 🚀 Featured Projects

---

### 🏎️ Redline — Collector Car Market Intelligence Platform
> **Live:** [www.redlineauto.click](https://redlineauto.click) · [API](https://principal-tallou-gavel-3718a78a.koyeb.app) · [Docs](https://principal-tallou-gavel-3718a78a.koyeb.app/docs)

A full-stack market intelligence platform that aggregates sold auction data from **14+ sources**, runs it through a multi-factor decision engine, and answers: *is this a good deal, and should I buy now or wait?*

**What makes it production-grade:**

| Dimension | Details |
|---|---|
| **Data ingestion** | 8 concurrent async scrapers (BaT, eBay Motors, Mecum, Barrett-Jackson, Cars & Bids, PCAR Market, Craigslist, AutoTrader) — all orchestrated via `asyncio.Semaphore(5)` |
| **Decision engine** | Deal Score (0–100) across 5 weighted factors + Viability Score formula `VS = 0.40P + 0.25R + 0.20L + 0.15TCO` with BUY / WAIT / PASS verdict |
| **Data quality** | Every record validated through a quarantine layer before DB upsert — rejects bad prices, mileage outliers, non-vehicle listings |
| **Test coverage** | **1,398+ tests** — unit, integration, and Hypothesis property-based tests. SQLite in-memory fixtures, zero external deps required |
| **Automation** | Fully zero-touch: 11 scheduled GitHub Actions jobs, daily scraping → normalization → enrichment → AI summaries → SEO pages → social distribution |
| **AI integration** | Groq (llama-3.3-70b) for natural language search, weekly editorial newsletters, buyer briefs, and content humanization |
| **Monetization** | Stripe-integrated tiered API (Free → $149/mo Business), Redis sliding-window rate limiting, SHA-256 key auth |
| **Stack** | FastAPI · PostgreSQL (Neon) · Redis (Upstash) · React 18 + Vite + TypeScript · Koyeb · Vercel · Playwright |

**Core APIs (all public, no key required):**
- `POST /v1/deal-score` — score any vehicle 0–100 with comparable auction data
- `GET /v1/market/wait-index` — supply/velocity signal for any make/model
- `GET /v1/auctions/search` — natural language auction search via Groq
- `GET /v1/pricing` — P10–P90 historical distribution + quarterly trend

---

### 🥇 Alfred & AMMA | *AWS $10,000 AI Ideas Competition — Semi-Finalist*
**Dual-agent AI system for ethical shopping & personalized nutrition.**
- **Alfred:** Automates values-aligned purchasing decisions across retailer ecosystems.
- **AMMA:** Delivers adaptive, personalized nutrition planning at the individual level.
- **Stack:** AWS multi-agent reasoning pipeline.
- 🔗 [AWS Builder Center](https://builder.aws.com/content/3APDUpWatvHmb5TAtvY6tsbSIi0/aideas-alfred-and-amma-the-dual-agent-ai-automating-ethical-shopping-and-personalized-nutrition) · [Web App](https://main.d2odyrogzbyuno.amplifyapp.com)

---

### ⚗️ The Forge
**Offline instruction-tuning dataset generator.**
- Converts source documents (PDF, DOCX, TXT) into `{system, user, assistant}` triples for LLM fine-tuning.
- Runs entirely via **Ollama** — zero data leaves the machine.
- 🔗 [GitHub](https://github.com/Starksood/the_forge/tree/main)

---

### 🌿 SHAMAN.OS
**Offline macOS guide for psychedelic harm reduction and integration.**
- Voice-to-voice interaction loop with synthesized speech and live fractal visuals.
- Custom fine-tuning pipeline for a specialized Ollama model.
- 🔗 [GitHub](https://github.com/Starksood/Shaman.io)

---

### 🏛️ Sovereign Administrative Suite
**Full-stack SaaS for legal & administrative workflow automation.**
- Built for small businesses and independent operators managing high-volume paperwork.
- **Stack:** JavaScript, Vercel, REST APIs.
- 🔗 [Live Site](https://sovereign-suite-1kja.vercel.app)

---

## 🛠️ Tech Stack

| Category | Tools & Languages |
|---|---|
| **Languages** | Python, JavaScript/TypeScript (ES6+), SQL, R, Java, HTML5/CSS3 |
| **Backend** | FastAPI, asyncio, SQLAlchemy 2.x, Alembic, Playwright, httpx |
| **Data & AI** | PostgreSQL, Redis, Groq (llama-3.3-70b), Ollama, TensorFlow, Scikit-learn |
| **Infrastructure** | GitHub Actions (CI/CD + scheduled pipelines), Koyeb, Vercel, AWS, Neon, Upstash |
| **Frontend** | React 18, Vite, Tailwind CSS, Recharts |
| **Security** | SHA-256 key auth, HMAC webhook verification, rate limiting, network security |
| **Testing** | pytest, Hypothesis (property-based), SQLite in-memory fixtures |

---

## 💼 Professional Experience

**Digital Marketing & Analytics Specialist** | *CIM (Canadian Institute of Mining)* · 4 years
- Production analytics at national scale — Python/SQL pipelines, predictive modeling, A/B testing infrastructure.

**Agribusiness Intern** | *FarNorth Fungi, Anchorage AK*
- Computer Vision + IoT pipeline for real-time mushroom cultivation monitoring. TensorFlow under real agricultural constraints.

---

## 🎓 Education & Certifications

- **B.S. Cybersecurity + B.Sc in Computer Science** | Wayne State College (Expected 2027)
- **IBM Data Science Professional Certificate**
- **Machine Learning with Python** | IBM
- **Financial Markets (with Honors)** | Yale University
- **Responsive Web Design** | freeCodeCamp

---

<div align="center">
  <sub>Building toward the future of secure, intelligent systems.</sub>
</div>

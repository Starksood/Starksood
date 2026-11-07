<div align="center">

# SANYAM SOOD
### `Systems Architecture` · `Applied Cryptography & AI` · `Data Engineering`

*Engineering deterministic AI memory substrates, autonomous market intelligence engines, and enterprise analytics pipelines.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sanyam--sood/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:snym.sood@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Starksood)
[![PyPI](https://img.shields.io/pypi/v/fireweed-mcp?style=for-the-badge&logo=pypi&logoColor=white&label=fireweed-mcp&color=3775A9)](https://pypi.org/project/fireweed-mcp/)
[![Zenodo](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.21278301-024285?style=for-the-badge)](https://doi.org/10.5281/zenodo.21278301)

**[🌸 Fireweed MCP](#-flagship-research--systems)** &nbsp;·&nbsp;
**[🚀 Production Systems](#-production-platforms--enterprise-systems)** &nbsp;·&nbsp;
**[🔬 R&D Labs](#-rd-labs--experiments)** &nbsp;·&nbsp;
**[🛠️ Tech Stack](#-technical-arsenal)** &nbsp;·&nbsp;
**[💼 Experience & Credentials](#-experience--credentials)**

</div>

---

> [!NOTE]
> ### 👨‍💻 Executive Summary & Telemetry
> Senior at **Wayne State College** pursuing a **B.S. in Cybersecurity** (Minor in Computer Science), backed by **4+ years of production data engineering and analytics experience** at a national scale. My work sits at the intersection of **verifiable systems** and **applied AI**: building infrastructure where language models propose, but deterministic code, cryptographic proofs, and strict data schemas govern what hits production.
>
> 🔴 **Shipped Package:** [`pip install fireweed-mcp`](https://pypi.org/project/fireweed-mcp/) *(Zero runtime deps · 1,092 deterministic tests)*
> 🟣 **Published Research:** [aiXiv Preprint](https://aixiv.science/abs/aixiv.260709.000003) · [OpenReview](https://openreview.net/pdf?id=mVgwFd5K0B) · [Zenodo DOI](https://doi.org/10.5281/zenodo.21278301)
> 🟢 **Live Systems:** **10,900+** scraped collector-car comps · **12+** enterprise analytics pipelines
> 🟡 **Security & Honors:** AWS $10k AI Semi-Finalist · Peer Reviewer (AIAgents4Qual) · CompTIA **Security+** & **Network+** *(In Progress)*

---

## 🌸 Flagship Research & Systems

> [!IMPORTANT]
> ### **Fireweed** — Deterministic, Cryptographically Verifiable Memory for AI Agents
> [![PyPI](https://img.shields.io/badge/PyPI-fireweed--mcp-3775A9?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/fireweed-mcp/)
> [![GitHub](https://img.shields.io/badge/GitHub-Starksood%2Ffireweed--mcp-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Starksood/fireweed-mcp)
> [![MCP Registry](https://img.shields.io/badge/MCP-Official_Registry-00A67E?style=flat-square)](https://registry.modelcontextprotocol.io/)
> [![DEV.to](https://img.shields.io/badge/Writeup-DEV.to-0A0A0A?style=flat-square&logo=devdotto&logoColor=white)](https://dev.to/starksood/i-built-an-mcp-memory-server-where-code-not-the-model-decides-what-gets-stored-497j)
> [![aiXiv](https://img.shields.io/badge/aiXiv-260709.000003-B31B1B?style=flat-square)](https://aixiv.science/abs/aixiv.260709.000003)
> [![OpenReview](https://img.shields.io/badge/OpenReview-mVgwFd5K0B-8C1B13?style=flat-square)](https://openreview.net/pdf?id=mVgwFd5K0B)
> [![Verification](https://img.shields.io/badge/Verify-Fireweed__Fabric-2EA44F?style=flat-square&logo=github&logoColor=white)](https://github.com/Starksood/Fireweed_Fabric)
>
> Most agent memory lets a language model decide what gets written down — putting the component that hallucinates in charge of the record. **Fireweed inverts that: the model proposes, deterministic code decides, and nothing ungrounded is committed.** An agent submits a claim *and the verbatim text it is quoting*. Four pure functions decide admission (subject grounding, relation preservation, numeric fidelity, span containment). Nothing in the server calls an LLM.

<table>
<tr>
<td width="50%" valign="top">

#### 🔐 Cryptographic & Systems Guarantees
* **Adjudicated Writes:** Emits typed refusals (`REFUSED (asserts_more_than_evidence)`) stating the claim, evidence, and fix.
* **Verifiable Provenance:** Every admitted fact binds to a byte range in its source. `verify_receipts` re-hashes and re-slices so tampering fails loudly.
* **Redactable Merkle Receipts:** Merkle-tree binding over document parts so erasing one subject leaves *other* parties' proofs intact.
* **Provable Erasure:** Structural closure, AES-256-GCM crypto-shredding under a per-subject key, durable tombstones, and third-party verifiable **Ed25519** certificates.

</td>
<td width="50%" valign="top">

#### 📐 Engineering & Published Research
* **Engine Footprint:** ~10k LOC deterministic engine · **1,092 tests** · append-only hash-chained ledger · **zero runtime dependencies** · stdlib-only open storage reader.
* **Research Paper:** *A Model-Independent Memory Substrate: Preserving an Agent's Account of a User Across LLM Swaps, Scales, and Families* (~0.8 semantic agreement across model families).
* **Stack:** `Python 3.9–3.13` · `stdio JSON-RPC` · `SQLite` · `AES-256-GCM` · `Ed25519` · `GitHub OIDC`

</td>
</tr>
</table>

> [!WARNING]
> **On Measurement & Scientific Integrity ([RETRACTION.md](https://github.com/Starksood/Fireweed_Fabric/blob/main/RETRACTION.md)):**
> One result in that work — a scaled abstention benchmark reporting zero false assertions — turned out to be measuring an empty database (721 of 722 stores held no nodes due to upstream benchmark extraction failure, where answering *"I don't know"* scores 100%). I withdrew that claim publicly with the raw data and a one-line verification command rather than quietly patching it. When I decomposed the corrected recall figure, the admission gate found genuinely stored answers **98.4%** of the time. Later, when a new optimization looked excellent, I built an adversarial corpus capable of *disproving* it, watched it collapse a core property by 60 points, and reverted it.

---

## 🚀 Production Platforms & Enterprise Systems


> [!CAUTION]
> ### 🏎️ SYSTEM 01 // [Redline Auto](https://redlineauto.click) — *Autonomous Collector Car Market Intelligence*
> [![Live Site](https://img.shields.io/badge/LIVE-redlineauto.click-E11D48?style=flat-square&logo=vercel&logoColor=white)](https://redlineauto.click)
> ![Comps](https://img.shields.io/badge/DATASET-10900_Verified_Comps-0F172A?style=flat-square)
> ![Studio](https://img.shields.io/badge/ENGINE-2D_Vector_Build_Studio-B91C1C?style=flat-square)
>
> Autonomous vehicle valuation and digital-twin studio powered by **10,900+ verified auction comps** scraped 24/7 across Bring a Trailer, Cars & Bids, and eBay Motors.

<details open>
<summary><b>⚡ Click to Toggle Redline Architecture & Telemetry</b></summary>

* 🎨 **Interactive 2D Vector Build Studio:** Models period-correct modifications (wheels, suspension, brakes, aero) and calculates real-time hammer-price resale multipliers and exportable Monroney window dossiers.
* 📊 **Algorithmic Valuation Engine:** Computes P10–P90 percentile valuation bands, a *Wait Index* (supply velocity indicator), and an automated pre-purchase deal-scoring engine.
* 🤖 **Autonomous Daily SEO Pipeline:** Analyzes daily auction transactions, generates rich editorial market reports, and injects `Schema.org` (`BlogPosting`, `FAQPage`) structured data for organic search discovery.
* 🛠️ **Stack:** `React 18` · `TypeScript` · `Vite` · `Tailwind CSS` · `Python (FastAPI)` · `PostgreSQL (Neon)` · `Redis` · `Vercel Edge`

</details>

<br/>

> [!IMPORTANT]
> ### 📈 SYSTEM 02 // CIM Enterprise SEO & Content Intelligence Platform
> ![Repo](https://img.shields.io/badge/DEPLOYMENT-Enterprise_Private_Repo-6D28D9?style=flat-square)
> ![Workflows](https://img.shields.io/badge/ORCHESTRATION-12_Automated_Pipelines-0F172A?style=flat-square)
> ![Sources](https://img.shields.io/badge/TELEMETRY-6_Unified_Data_Sources-4F46E5?style=flat-square)
>
> National-scale SEO and content intelligence platform orchestrating weekly and monthly reporting workflows across **Google Analytics 4, Search Console, PageSpeed Insights, Mailchimp, Monday.com, and Google Sheets**.

<details open>
<summary><b>⚡ Click to Toggle CIM Master Orchestrator Architecture</b></summary>

* 🔄 **Ingestion & Async Crawl Workers:** Parallel API extraction (GA4, GSC, PageSpeed, Mailchimp) paired with sequential async crawlers (`Playwright`, `BeautifulSoup`, `aiohttp`) for broken link detection, redirect tracking, internal link equity analysis, and orphan page discovery.
* 🧠 **Cross-Channel Content Intelligence:** Joins search visibility, GA4 engagement, Mailchimp clicks, and content audit signals to identify content champions, refresh candidates, distribution gaps, and engagement decay.
* 🤖 **LLM Executive Synthesis:** Groq/OpenAI-compatible integration for executive summaries, AI-snippet readiness checks, hallucination risk reviews, and prioritized remediation queues.
* 📡 **Automated Delivery & Resilience:** Monday.com GraphQL uploads, Google Sheets historical persistence, self-contained HTML/CSV/Markdown dashboards, and GitHub Actions schedules with automatic source-data fallbacks.
* 🛠️ **Stack:** `Python 3.11` · `asyncio` · `aiohttp` · `Playwright` · `pandas` · `matplotlib` · `GA4 & GSC APIs` · `Monday.com GraphQL` · `Mailchimp API` · `Groq SDK` · `GitHub Actions`

</details>

<br/>

> [!TIP]
> ### 🛠️ SYSTEM 03 // [Bazaar](https://bazaar.me.uk/) — *Edge-Native Neighborhood Repair Platform*
> [![Live Site](https://img.shields.io/badge/LIVE-bazaar.me.uk-059669?style=flat-square&logo=cloudflare&logoColor=white)](https://bazaar.me.uk/)
> ![Hubs](https://img.shields.io/badge/CITIES-NYC_--_Austin_--_SF_--_Chicago-0F172A?style=flat-square)
> ![SEO](https://img.shields.io/badge/GROWTH-Zero_Cost_Daily_AI_SEO-047857?style=flat-square)
>
> Full-stack community platform where people host and join free fix-it gatherings (electronics, bikes, textiles, furniture) across New York, Austin, San Francisco, and Chicago.

<details open>
<summary><b>⚡ Click to Toggle Bazaar Edge & Automation Specs</b></summary>

* 🌐 **Global Edge Execution:** Built on Next.js 16 and React 19 running on **Cloudflare Workers** via the ChatGPT Sites platform, backed by a serverless **D1 (SQLite)** relational database and Drizzle ORM.
* ✍️ **Autonomous Organic Discovery Loop:** GitHub Actions pipeline powered by the Gemini API generates and publishes a new AI-written repair story daily to `bazaar.me.uk/stories` — zero operational cost, zero manual effort.
* 🔐 **Identity & Access:** Frictionless user onboarding with Clerk and Google SSO.
* 🛠️ **Stack:** `Next.js 16` · `React 19` · `Cloudflare Workers` · `D1 (SQLite)` · `Drizzle ORM` · `Clerk (Google SSO)` · `Tailwind 4` · `TypeScript` · `GitHub Actions` · `Gemini API`

</details>

---

## 🔬 R&D Labs & Experiments

> [!WARNING]
> 🏆 **[Alfred & AMMA](https://main.d2odyrogzbyuno.amplifyapp.com) — *AWS $10,000 AI Ideas Competition Semi-Finalist***
> Dual-agent AI architecture deployed on AWS automating ethical shopping workflows and personalized nutrition mapping.

> [!NOTE]
> ⚒️ **[The Forge](https://github.com/Starksood/the_forge/tree/main) — *Local Offline SFT Dataset Generator***
> Privacy-first instruction-tuning pipeline utilizing **Ollama** to convert raw source documents into strict `{system, user, assistant}` triples.

> [!TIP]
> 🏛️ **[Sovereign Administrative Suite](https://sovereign-suite-1kja.vercel.app) — *Legal & Administrative SaaS***
> Full-stack web platform built on JavaScript, Vercel, and REST APIs for legal and administrative paperwork automation.

> [!IMPORTANT]
> 🌀 **[SHAMAN.OS](https://github.com/Starksood/Shaman.io) — *Voice-to-Voice Local AI Loop***
> Low-latency voice interaction loop pairing custom fine-tuned local language models with live fractal visual generation.

---

## 🛠️ Technical Arsenal

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ Backend & Systems
* **Languages:** Python (3.9–3.13), TypeScript/JavaScript (ES6+), SQL, HTML5/CSS3
* **Frameworks:** FastAPI, `asyncio`, SQLAlchemy 2.x, Drizzle ORM, Playwright, `aiohttp`
* **Protocols:** Model Context Protocol (MCP), stdio JSON-RPC, OIDC Trusted Publishing

</td>
<td width="50%" valign="top">

### 🔐 Applied Cryptography & QA
* **Primitives:** AES-256-GCM, Ed25519, HMAC-SHA256
* **Structures:** Redactable Merkle trees, hash-chained append-only ledgers, crypto-shredding
* **Testing:** `pytest`, Hypothesis property tests, adversarial corpora, cross-version gates

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 Data Engineering & AI
* **Datastores:** PostgreSQL (Neon), SQLite (Cloudflare D1), Redis (Upstash)
* **Models & ML:** Groq (Llama-3.3-70b), Ollama, Gemini API, TRL/PEFT, TensorFlow, Scikit-learn, pandas

</td>
<td width="50%" valign="top">

### 🌐 Frontend & Cloud Infra
* **Frontend:** Next.js 16, React 18/19, Tailwind CSS 4, Vite, Recharts
* **Cloud & CI/CD:** Cloudflare Workers, AWS, Vercel Edge, Koyeb, Docker, GitHub Actions

</td>
</tr>
</table>

---

## 💼 Experience & Credentials

<table>
<tr>
<td width="58%" valign="top">

### 🏛️ Professional Experience

**Digital Marketing & Web Optimization Specialist** · *CIM* `(4 Years)`
* Architected and maintained production analytics systems at a national scale.
* Developed comprehensive Python/SQL data pipelines, orchestrated A/B testing infrastructure, and built automated executive dashboards.

**Agribusiness Intern** · *FarNorth Fungi (Anchorage, AK)*
* Deployed a Computer Vision and IoT pipeline for real-time environmental monitoring in commercial mushroom cultivation.
* Optimized TensorFlow models to operate under constrained agricultural hardware conditions.

**Food Pantry Coordinator** · *Wayne State College* `(2025 – Present)`
* Direct logistics and community operations management, ensuring continuous supply chain flow and equitable distribution.

**Administrative Assistant** · *Camp Laurel South (Casco, ME)* `(Summer 2026)`
* Managed daily administrative operations, organizational workflows, and logistical support for a high-volume seasonal program.

</td>
<td width="42%" valign="top">

### 🎓 Education
**Wayne State College** `(Expected 2027)`
* **B.S. in Cybersecurity**
* **Minor in Computer Science**

---

### 🏅 Awards & Recognition
* 🎖️ **Honorary Reviewer** — *AIAgents4Qual Conference (2026)*
* 🏆 **Semi-Finalist** — *AWS $10,000 AI Ideas Competition*

---

### 📜 Certifications
* 🔄 **CompTIA Security+** *(In Progress)*
* 🔄 **CompTIA Network+** *(In Progress)*
* ✅ **Data Science Professional Certificate** — *IBM*
* ✅ **Machine Learning with Python** — *IBM*
* ✅ **Financial Markets (Honors)** — *Yale University*
* ✅ **NSE 1, 2, & 3** — *Fortinet*
* ✅ **Responsive Web Design** — *freeCodeCamp*

</td>
</tr>
</table>

---

<div align="center">

![Open to Roles](https://img.shields.io/badge/STATUS-Open_to_Security_--_Backend_--_AI_Engineering_Roles-2EA44F?style=for-the-badge)

<sub>Building toward the future of secure, intelligent systems · <a href="mailto:snym.sood@gmail.com">snym.sood@gmail.com</a> · <a href="https://www.linkedin.com/in/sanyam--sood/">LinkedIn</a></sub>

</div>

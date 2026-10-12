<!-- ============ HERO ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,50:1D4ED8,100:06B6D4&height=210&section=header&text=Arjun%20R%20K&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%C2%B7%20Data%20%C2%B7%20Backend%20%C2%B7%20GPU%20%26%20HPC%20curious&descSize=18&descAlignY=60" width="100%" alt="Arjun R K banner"/>

<a href="https://github.com/AxArjun">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1200&color=1D4ED8&center=true&vCenter=true&width=700&lines=AI+Intern+%40+Applied+Systems+Research+%26+Technology;Models+%E2%86%92+Pipelines+%E2%86%92+APIs+%E2%86%92+Dashboards;Curious+about+GPU+%26+HPC%3A+making+compute+fast;Open+to+AI+Eng+%7C+Data+Eng+%7C+FDE+%7C+SDE+%C2%B7+Class+of+2027" alt="Typing intro"/>
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-axarjun-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/axarjun/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arjunramprasad.2005@gmail.com)
![Open to work](https://img.shields.io/badge/Open%20to%20Work-2027%20Graduate-22C55E?style=for-the-badge)

</div>

---

## 👋 About

I build systems that take **data in, run heavy computation, and put the result in front of a user**: a model or solver in the middle, a pipeline feeding it, an API and dashboard on top.

Final-year B.Tech IT student at **SRMIST Chennai**, currently an **AI Intern at Applied Systems Research & Technology**, leading a small team of undergrads on an AI infrastructure observability platform. I'm especially drawn to the **GPU / high-performance computing** side: simulation, inference speed, and squeezing more out of hardware.

|  |  |
|---|---|
| 🎓 **Education** | B.Tech Information Technology, SRMIST Chennai (2023–2027) |
| 💼 **Now** | AI Intern, Applied Systems Research & Technology Pvt Ltd |
| 🎯 **Open to** | AI Engineer · Data Engineer · Forward Deployed Engineer · SDE · GPU/HPC-adjacent roles |
| 📍 **Base** | Chennai, India |

---

## 🎯 Where I Fit

| Role | Why | Proof |
|---|---|---|
| **AI Engineer** | Train, serve, and guard models in real systems | YOLOv8 multi-camera pipeline · churn model (ROC-AUC 85.03%) · LLM guardrails in REVORA |
| **Data Engineer** | Ingest, model, and serve data reliably | Relational ETL → MongoDB → star schema · TimescaleDB metrics in AISO |
| **Forward Deployed Engineer** | Take a messy real-world problem to a working deployed solution | Disaster-response platform (SIH 2026) · industrial PPE monitoring · payments recovery app |
| **SDE / Backend** | Clean APIs, auth, queues, containers, CI | FastAPI + Redis + WebSockets + JWT · Docker · GitHub Actions |
| **GPU / HPC** | Simulation and inference are where I want to go deeper | Hydrodynamic + SPH solver pipeline · real-time CV inference · see [Roadmap](#-roadmap) |

---

## 💼 Experience

### AI Intern, Applied Systems Research & Technology Pvt Ltd
**AISO: AI Infrastructure Observability Platform**
- Built on **FastAPI · PostgreSQL · TimescaleDB · Redis**
- Lead a small team of undergraduate contributors on the codebase
- <!-- ADD: one measurable outcome, e.g. metrics/sec ingested or latency of a key query. Verified numbers only. -->

---

## 🚀 Featured Projects

### 🌊 [JalRakshak-HD](https://github.com/AxArjun/JalRakshak---HD): Dam-Break & Disaster-Response Intelligence Platform
> **Smart India Hackathon 2026 · Problem Statement SIH26161 · Team of 6**
> My role: <!-- ADD: your exact contribution, e.g. backend APIs / HADR screening / validation scripts -->

A configuration-driven pipeline from dam geometry to breach hydrograph, **2D flood simulation**, **near-field particle (SPH) simulation**, hazard classification, and humanitarian exposure screening, served through a React GIS dashboard. New dams are onboarded with YAML, not code changes.

| | |
|---|---|
| **2D flood model** | D-Flow FM · 818 km² domain · 30 h simulated · 181 output frames |
| **Near-field model** | DualSPHysics · ~11K particles · first 1.5 km below the breach |
| **Exposure screening** | Population, buildings, roads, bridges, critical facilities, 6 response sectors |
| **Engineering** | FastAPI + React 19 + TypeScript · 57 tests · mass-balance residual 0.0052% |
| **Honesty by design** | Anything not computed is shown as `NOT_RUN`, never filled in |

`FastAPI` `React 19` `TypeScript` `D-Flow FM` `DualSPHysics` `GeoPandas` `Google Earth Engine` `Sentinel-1`
🔭 *Next on its roadmap: on-demand solver runs on an HPC queue and full 3D SPH on GPU.*

---

### 👷 [Worker Safety Detection v2](https://github.com/AxArjun/Worker-safety-detection-System-v2): Real-time PPE Compliance
Multi-camera YOLOv8 pipeline: threaded capture per camera → Redis pub/sub → severity classification → **WebSocket alerts** to a React dashboard, with JWT + OTP auth, snapshots, email alerts, and one-command Docker deployment.

| | |
|---|---|
| **Pipeline** | Per-camera threads · spatial helmet/vest matching per worker · alert cooldown throttling |
| **Stack** | YOLOv8 · OpenCV · FastAPI · Redis · SQLAlchemy · React 19 + TypeScript · Docker |
| **Metrics** | <!-- ADD: mAP / precision / recall on your PPE model + FPS on CPU vs GPU --> |

---

### 📉 [Telco Customer Churn](https://github.com/AxArjun/telco-customer-churn-analysis): Prediction + Executive Dashboard
SQL analytics → EDA → feature engineering → Random Forest → **7-page Power BI dashboard** with a retention what-if simulator, on 7,043 customers.

**ROC-AUC 85.03%** · Accuracy 80.7% · built with a team of 3
`SQL` `Pandas` `Scikit-learn` `Power BI` `DAX`

---

### 🗄️ [Enterprise Data Engineering Pipeline](https://github.com/AxArjun/Enterprise-Data-Engineering-Pipeline): Multi-Database Architecture
A retail scenario across three storage layers: **relational ETL**, **MongoDB** product catalog, and a **star-schema warehouse** (fact + dimension tables) for analytical queries.

| | |
|---|---|
| **Scale** | <!-- ADD: row counts, load time, number of fact/dim tables --> |
| **Stack** | Python · SQL · PostgreSQL · MongoDB |

---

### 🚗 [FuelIQ](https://github.com/AxArjun/FuelIQ): Vehicle Intelligence Platform *(in development)*
Flutter app + FastAPI backend: multi-vehicle garage, fuel-efficiency analytics, service reminders, and **on-device OCR receipt scanning**. Backed by PostgreSQL 16 (partitioned tables, materialized views), Redis, and MinIO, and documented end to end: PRD → architecture → DB design → scale plan.

`Flutter` `FastAPI` `PostgreSQL` `Redis` `MinIO` `Docker` `GitHub Actions`

---

### 🧩 Also Built
- **[REVORA](https://revora-woad-tau.vercel.app)**: AI revenue recovery for failed payments (Razorpay Buildathon 2026). LLM proposes actions; a **deterministic policy gateway** approves them. FastAPI · Next.js · Gemini · live on Vercel/Render
- **AI Contract Analyzer**: multi-agent contract review with LangGraph <!-- ADD repo link -->
- **SentinEdge**: [enterprise fraud risk pipeline](https://github.com/AxArjun/enterprise-fraud-risk-pipeline) with tiered review queues

---

## 🧰 Tech Stack

<div align="center">

| | |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) |
| **AI / ML** | ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![YOLOv8](https://img.shields.io/badge/YOLOv8-111827?style=flat-square&logo=opencv&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-0F172A?style=flat-square) |
| **Data** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=flat-square&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?style=flat-square&logo=timescale&logoColor=black) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) |
| **Scientific / Geo** | ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square) ![Rasterio](https://img.shields.io/badge/Rasterio-2D6A4F?style=flat-square) ![Earth Engine](https://img.shields.io/badge/Earth%20Engine-4285F4?style=flat-square&logo=googleearth&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-D82C20?style=flat-square&logo=redis&logoColor=white) ![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat-square) |
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white) |

</div>

---

## ⚡ GPU & HPC Focus

What pulls me here: the moment a system stops being "does it work?" and becomes "how fast, and on what hardware?"

**Where it already shows up in my work**
- Running **physics solvers** (D-Flow FM, DualSPHysics) as stages of a larger pipeline in JalRakshak-HD
- **Real-time inference** under frame-rate and latency limits in the PPE detection system

**What I'm building toward** → see Roadmap below.

---

## 🗺️ Roadmap

- [ ] GPU vs CPU inference benchmark for the PPE detector (FPS, latency, batch size), then export to ONNX / TensorRT
- [ ] Run the near-field SPH case on GPU and publish timing vs CPU
- [ ] CUDA fundamentals: write and profile a few kernels (reductions, matrix ops)
- [ ] MPI / multi-process basics on a small simulation workload
- [ ] PySpark layer on the data-engineering pipeline
- [ ] Azure deployment + **DP-900**
- [ ] Harden FuelIQ (tests, CI, deployment)

*Checked items get a link to the repo or write-up.*

---

## 📊 GitHub Snapshot

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=AxArjun&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AxArjun&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>

</div>

---

<div align="center">

**Hiring for 2027 graduates in AI, data, backend, or GPU/HPC-adjacent roles? Let's talk.**

[![LinkedIn](https://img.shields.io/badge/Connect%20on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/axarjun/)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:1D4ED8,100:0B1220&height=100&section=footer" width="100%" alt="footer"/>

</div>

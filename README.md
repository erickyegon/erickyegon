# Erick Kiprotich Yegon
### Fabric Analytics Engineer · Data Scientist · Healthcare AI & Analytics · Causal Inference

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/erick-yegon-phd-4116961b4/)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--7055--4848-A6CE39?style=flat&logo=orcid)](https://orcid.org/0000-0002-7055-4848)
[![Portfolio](https://img.shields.io/badge/Portfolio-codebasics.io-FF6B35?style=flat)](https://codebasics.io/portfolio/ErickKiprotich-Yegon)
[![Email](https://img.shields.io/badge/Email-keyegon@gmail.com-D14836?style=flat&logo=gmail)](mailto:keyegon@gmail.com)

📍 Richmond, Kentucky, USA &nbsp;|&nbsp; 🇺🇸 U.S. Permanent Resident — No Sponsorship Required

---

## What I Do

I design and ship **production analytics and data science systems** — Microsoft Fabric lakehouses, ML pipelines, causal inference engines, AI platforms, and real-time analytics infrastructure — applied to healthcare and population health problems at scale.

My background combines **hands-on engineering** with deep **quantitative methodology**: I build the models *and* I understand the math behind them. My systems have run in production against live government health databases, served predictions to frontline health workers in real time, and informed decisions affecting millions of individuals.

**Core areas:**

- 🏗️ **Microsoft Fabric & Power BI** — Lakehouse architecture, Medallion pipelines, semantic models, DAX, KQL, deployment pipelines
- 🤖 **AI / LLM Systems** — RAG pipelines, multi-agent architectures, healthcare Q&A platforms
- 🧠 **Machine Learning & MLOps** — end-to-end pipelines, model calibration, SHAP explainability, drift monitoring, CI/CD
- 📊 **Healthcare Analytics** — risk stratification, population health modeling, clinical decision intelligence
- 🔬 **Causal Inference & RWE** — PSM, DiD, ITS, TMLE, SuperLearner — production-grade, not just academic

> **Philosophy:** Models that don't deploy don't matter. Data science should produce systems, not papers.

---

## Impact at a Glance

| What I Built | Result |
|---|---|
| **Immunization defaulter risk engine** (Kenya MOH eCHIS · live production DB) | ROC-AUC 0.892 · 6,864 patients · 4,672 CHW areas · [live app ↗](https://immunizationengine.streamlit.app/) |
| **Microsoft Fabric Medallion Lakehouse** (YegonFabricLabs) | Bronze → Silver → Gold · Data Factory pipelines · Semantic model · Power BI |
| **CertiAce Retail Analytics** (Fabric portfolio · DP-600) | Full Medallion lakehouse · 555K rows · DAX · KQL · RLS/OLS · deployment pipelines |
| ML predictive models for health outcomes | ~30% improvement in prediction accuracy |
| Automated data pipelines (ClickHouse + Python + dbt) | Reporting latency: 10–14 days → **real-time** |
| Causal inference & RWE studies | 25+ production studies informing program decisions |
| Medicare risk adjustment pipeline (U.S.) | Validated ATT of **−$391/member**, p<0.0001 |
| Healthcare analytics platforms | Scale: **8.5M+ individuals** across multiple health systems |
| Peer-reviewed publications | 30+ articles incl. *The Lancet Global Health* |

---

## Featured Projects

### 🏗️ Microsoft Fabric & Power BI

| Project | Description | Stack |
|---|---|---|
| [**CertiAce Retail Analytics — Fabric Portfolio**](https://github.com/erickyegon/certace-fabric-analytics) | End-to-end Microsoft Fabric project covering all DP-600 domains — Medallion (Bronze/Silver/Gold) architecture over 555K rows, Data Factory pipelines, semantic model with DAX measures, KQL real-time monitoring, RLS/OLS, and deployment pipelines | Microsoft Fabric · OneLake · KQL · DAX · T-SQL · Power BI |
| [**YegonFabricLabs — Medallion Lakehouse**](https://github.com/erickyegon/DP600) | Enterprise Medallion architecture on Microsoft Fabric — Bronze/Silver/Gold Lakehouses, Data Factory pipelines with ForEach/Copy Data activities, Dataflow Gen2, semantic model with DAX measures, RLS, and deployment pipeline (Dev → Test → Prod) | Microsoft Fabric · OneLake · KQL · DAX · T-SQL · Power BI |
| [**E-Commerce Intelligence Platform**](https://github.com/erickyegon/ecommerce-intelligence-platform) | Production-grade lakehouse pipeline — 1.7M rows, 6 relational tables, full Bronze → Silver → Gold Medallion architecture, analytics-ready semantic layer | Databricks · Delta Lake · SQL · Python |
| [**Community Health Intelligence Platform**](https://github.com/erickyegon/community-health-intelligence-platform) | End-to-end community health lakehouse — Medallion pipeline, Unity Catalog RLS, AI/BI Genie, executive dashboard serving 5,000 CHWs across Kenya | Databricks · Unity Catalog · Delta Lake · Python |

---

### 🧠 Machine Learning & MLOps

| Project | Description | Stack |
|---|---|---|
| [**Immunization Defaulter Risk Engine**](https://github.com/erickyegon/immunization-defaulter-risk-engine) [![Live App](https://img.shields.io/badge/Live-App-FF4B4B?style=flat&logo=streamlit)](https://immunizationengine.streamlit.app/) | Production XGBoost pipeline predicting vaccine defaulter risk for 6,864 children across 4,672 CHW areas. Data drawn directly from Kenya Ministry of Health eCHIS. Per-patient SHAP explainability, isotonic calibration (ECE=0.023), PSI drift monitoring, RBAC Streamlit dashboard, FastAPI serving. | Python · XGBoost · SHAP · FastAPI · PostgreSQL · MLflow · Streamlit |
| [Medicare Risk Adjustment Pipeline](https://github.com/erickyegon/medicare-raf-prototypes) | Validated U.S. Medicare RAF pipeline — ATT −$391/member, p<0.0001 | Python · R · SQL · CMS HCC |
| [Insurance Premium Prediction](https://github.com/erickyegon/insurance-premium-prediction-ml) | End-to-end ML pipeline with CI/CD, MLflow tracking and SHAP explainability | Python · XGBoost · MLflow · SHAP |
| [DHS RAG System](https://github.com/erickyegon/dhs-rag-system) | Semantic intelligence system for Demographic & Health Survey datasets | Python · RAG · Vector Search |
| [Multimodal PDF RAG System](https://github.com/erickyegon/multimodal-pdf-rag-system) | Document intelligence platform with OCR, table extraction and semantic search | Python · FastAPI · React |

---

### 🤖 AI & LLM Systems

| Project | Description | Stack |
|---|---|---|
| [AI-Powered Research Assistant](https://github.com/erickyegon/AI-Powered-Research-Assistant-for-Scientific-Papers) | Production RAG platform for scientific paper intelligence with modular LangGraph workflows | Python · LangGraph · LangChain · ChromaDB · FastAPI |
| [Healthcare Q&A RAG Platform](https://github.com/erickyegon/Healthcare-Q-A-Tool) | Enterprise healthcare knowledge retrieval with vector search and RBAC | Python · FastAPI · ChromaDB |
| [Women's Health RAG](https://github.com/erickyegon/womens-health-rag) | Global women's health intelligence assistant using DHS reports from Kenya, Nigeria, Ghana, Ethiopia | Python · LangChain · pgvector · GPT-4o |
| [Clinical Document Intelligence](https://github.com/erickyegon/clinical-doc-intelligence) | AI-powered FDA drug label intelligence — production RAG with 5-stage retrieval, multi-agent orchestration, 54 automated tests | Python · FastAPI · Multi-Agent |

---

### 📊 Healthcare Data Science

| Project | Description | Stack |
|---|---|---|
| [Databricks Medicare Lakehouse](https://github.com/erickyegon/databricks-medicare-lakehouse) | Medicare analytics lakehouse with risk adjustment modeling | Python · Databricks · Delta Lake |
| [Kenya Community Health AI](https://github.com/erickyegon/ushauri-ai-kenya-community-health) | AI analytics platform integrating national digital health systems for 107,000 CHPs | Python · Multi-Agent AI |

---

## Technical Stack

**Microsoft Fabric & BI**
Microsoft Fabric · Power BI · OneLake · Lakehouse · Data Warehouse · Dataflow Gen2 · Data Factory · KQL · DAX · T-SQL · Eventhouse · Deployment Pipelines · Direct Lake · Semantic Models · RLS/OLS

**Languages**
Python · R · SQL · KQL · DAX

**Machine Learning**
scikit-learn · XGBoost · PyTorch · TensorFlow · MLflow · SHAP · Optuna · Survival models

**AI / LLM**
LangChain · LangGraph · RAG · Vector Databases (ChromaDB, Pinecone, pgvector) · Multi-Agent Systems · Prompt Engineering

**Data Infrastructure**
Databricks · Delta Lake · AWS (Redshift · Glue · SageMaker · S3) · ClickHouse · PostgreSQL · dbt · FastAPI · Docker · Streamlit · Airflow

**Visualization & BI**
Power BI · Tableau · Plotly · ggplot2

**Causal & Statistical Methods**
PSM · Difference-in-Differences · Interrupted Time Series · TMLE · SuperLearner · Bayesian modeling · Mixed-effects models · Pharmacoepidemiology

---

## Education

**PhD — Epidemiology** *(Quantitative Methods, Causal Inference & Health Data Science)*
Advanced training in study design, statistical theory, and evidence generation — applied directly to ML model validation, experiment design, and real-world evidence production.

**MSc — Health Systems Management**
**BSc — Statistics**

---

## Certifications

| Certification | Issuer | Status |
|---|---|---|
| **Microsoft Certified: Fabric Analytics Engineer Associate (DP-600)** | Microsoft | ✅ 2026 |
| **Microsoft Certified: Power BI Data Analyst Associate (PL-300)** | Microsoft | ✅ 2024 |
| Machine Learning in Medicine | Stanford University | ✅ |
| AWS Certified Data Science & Analytics | Amazon Web Services | ✅ |
| Google Data Analytics Professional Certificate | Google | ✅ |
| DataCamp Machine Learning Scientist Track | DataCamp | ✅ |
| LLMOps (186+ hrs, 6 production projects) | Multiple platforms | ✅ |

---

## Why PhD + Data Science + Fabric?

A common assumption: *PhD = academic researcher = not hands-on.*

That's not my profile.

My PhD is in **quantitative epidemiology** — which means advanced statistics, causal modeling, experimental design, and evidence validation. These are the same foundations that make a data scientist rigorous: knowing *why* a model works, not just *that* it works.

What makes my profile unusual: I combine **enterprise analytics engineering** (Fabric, Power BI, Medallion architecture) with **deep ML/AI capability** (RAG, causal inference, production MLOps) and **domain expertise** (17+ years in global health, 30+ peer-reviewed publications including The Lancet).

Most Fabric engineers don't have PhD-level statistical depth.
Most data scientists can't build enterprise semantic models and deployment pipelines.
I do both.

---

## Open To

**Hands-on and leadership roles** across analytics engineering, data science, and healthcare AI:

- **Analytics Engineer / Senior Analytics Engineer**
- **Microsoft Fabric Engineer / Architect**
- **Power BI Developer / Architect**
- **Senior / Principal / Lead Data Scientist**
- **Healthcare Data Scientist / Clinical Data Scientist**
- **Population Health Analytics Lead**
- **Director / VP, Data & Analytics**
- **Real-World Evidence Scientist**

**Target sectors:**
Health Systems · Payers & Insurers · Pharma · Biotech · CRO · Health Tech · Global Health · Federal Contractors · Microsoft Partners

---

<div align="center">

**Microsoft Fabric · Power BI · Healthcare Analytics · AI Systems · Causal Inference · Real-World Evidence**

📩 **keyegon@gmail.com** &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/erick-yegon-phd-4116961b4/) &nbsp;|&nbsp; 🌐 [Portfolio](https://codebasics.io/portfolio/ErickKiprotich-Yegon)

</div>

# Erick Kiprotich Yegon
### Epidemiologist & Data Scientist · Real-World Evidence · Causal Inference · Healthcare AI & Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/erickyegon)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--7055--4848-A6CE39?style=flat&logo=orcid)](https://orcid.org/0000-0002-7055-4848)
[![Portfolio](https://img.shields.io/badge/Portfolio-Project%20sites-FF6B35?style=flat)](https://erickyegon.github.io/incretin-access-value/)
[![Email](https://img.shields.io/badge/Email-keyegon@gmail.com-D14836?style=flat&logo=gmail)](mailto:keyegon@gmail.com)

📍 Richmond, Kentucky, USA &nbsp;|&nbsp; 🇺🇸 U.S. Permanent Resident — No Sponsorship Required

---

## What I Do

I have spent 17+ years in epidemiology, global health analytics, data science and agentic AI, underpinned by doctoral training in epidemiology. I build the analysis and the system around it: cohort and survival studies on real-world data, causal designs for policy questions, and the pipelines, models and apps that put results in front of decision makers.

**Core areas** (each links to a repo that shows it):

- 🔬 **Real-world evidence & causal inference:** [oncology cohort and survival analysis](https://github.com/erickyegon/oncology-rwe-nsclc), [IPTW and immortal-time-bias methods](https://github.com/erickyegon/nsclc-rwd-truth-recovery), [difference-in-differences and event-study designs](https://github.com/erickyegon/incretin-access-value)
- 📊 **Health economics:** [Medicaid coverage and budget impact](https://github.com/erickyegon/incretin-access-value)
- 🧠 **Machine learning for health:** [risk stratification with SHAP and calibration](https://github.com/erickyegon/immunization-defaulter-risk-engine)
- 🤖 **AI / LLM systems:** [production RAG](https://github.com/erickyegon/clinical-doc-intelligence), [multi-agent orchestration](https://github.com/erickyegon/AgentCare)
- 🏗️ **Data platforms:** [Microsoft Fabric](https://github.com/erickyegon/certace-fabric-analytics), [Databricks lakehouse](https://github.com/erickyegon/community-health-intelligence-platform)

---

## Real-World Evidence & Oncology

| Project | What it shows | Stack |
|---|---|---|
| [**oncology-rwe-nsclc**](https://github.com/erickyegon/oncology-rwe-nsclc) · [report](https://erickyegon.github.io/oncology-rwe-nsclc/report.html) | NSCLC survival pipeline on synthetic EHR data (Synthea → OMOP CDM → dbt → R), benchmarked against 172,582 U.S. patients from SEER. Documents a case where the synthetic data failed validation: unmodified Synthea staged every lung cancer as stage I. | R · OMOP CDM · dbt · PostgreSQL |
| [**nsclc-rwd-truth-recovery**](https://github.com/erickyegon/nsclc-rwd-truth-recovery) | Companion project: a custom generator with a known truth, rule-based line-of-therapy derivation (98.1% whole-sequence exact match against truth), IPTW, an immortal-time-bias demonstration, and a 10-seed Monte-Carlo bias and coverage study. | Python · lifelines · scikit-learn |
| [**incretin-access-value**](https://github.com/erickyegon/incretin-access-value) · [site](https://erickyegon.github.io/incretin-access-value/) | Public-data study of Medicaid coverage of Wegovy and Zepbound: 12.2 additional prescriptions per 1,000 enrollees per quarter (95% CI 8.4 to 16.0) and a net budget impact of about $161.3 million over five years for a 1-million-enrollee program. Tested warehouse, Quarto report, interactive budget model. | PostgreSQL · dbt · R · Quarto · Shiny |

---

## Healthcare Data Science & ML

| Project | Description | Stack |
|---|---|---|
| [**Immunization Defaulter Risk Engine**](https://github.com/erickyegon/immunization-defaulter-risk-engine) [![Live App](https://img.shields.io/badge/Live-App-FF4B4B?style=flat&logo=streamlit)](https://immunizationengine.streamlit.app/) | XGBoost pipeline predicting vaccine defaulter risk for 6,864 children across 4,672 CHW areas in Kenya. Per-patient SHAP explainability, isotonic calibration (ECE 0.023), PSI drift monitoring, FastAPI serving, Streamlit dashboard. | Python · XGBoost · SHAP · FastAPI · PostgreSQL · MLflow · Optuna |
| [Databricks Medicare Lakehouse](https://github.com/erickyegon/databricks-medicare-lakehouse) | Medicare Advantage lakehouse: medallion ETL, CMS HCC v28 risk adjustment, XGBoost + SHAP, Unity Catalog governance. | Databricks · Delta Lake · Python |
| [Community Health Intelligence Platform](https://github.com/erickyegon/community-health-intelligence-platform) | Community health lakehouse for Kenya's CHW program: medallion pipeline, Unity Catalog row-level security, AI/BI Genie, dashboard. | Databricks · Delta Lake · dbt · Airflow |
| [Insurance Premium Prediction](https://github.com/erickyegon/insurance-premium-prediction-ml) | End-to-end ML pipeline with CI/CD, MLflow tracking and SHAP explainability. | Python · XGBoost · MLflow · SageMaker |
| [Within Reach](https://github.com/erickyegon/within-reach) | #TidyTuesday analysis of hospital access across 11,422 U.S. cities, with a live Shiny app. | R · Shiny |

---

## AI & LLM Systems

| Project | Description | Stack |
|---|---|---|
| [Clinical Document Intelligence](https://github.com/erickyegon/clinical-doc-intelligence) | FDA drug-label RAG with 5-stage retrieval, multi-agent orchestration, clinical guardrails and 54 automated tests. | Python · FastAPI · ChromaDB |
| [AgentCare](https://github.com/erickyegon/AgentCare) | Six-agent LangGraph orchestration for patient administration and care coordination. | Python · LangGraph · FastAPI · Next.js |
| [Women's Health RAG](https://github.com/erickyegon/womens-health-rag) | RAG over Demographic and Health Survey reports. | Python · LangChain · LangGraph · pgvector |
| [AI-Powered Research Assistant](https://github.com/erickyegon/AI-Powered-Research-Assistant-for-Scientific-Papers) | RAG platform for scientific papers with modular LangGraph workflows. | Python · LangGraph · Pinecone |
| [Healthcare Q&A RAG Platform](https://github.com/erickyegon/Healthcare-Q-A-Tool) | Healthcare knowledge retrieval with vector search and role-based access. | Python · FastAPI · ChromaDB |
| [Multimodal PDF RAG System](https://github.com/erickyegon/multimodal-pdf-rag-system) | Document intelligence with OCR, table extraction and semantic search. | Python · FastAPI · React |

---

## Microsoft Fabric & Power BI

| Project | Description | Stack |
|---|---|---|
| [**CertiAce Retail Analytics**](https://github.com/erickyegon/certace-fabric-analytics) | Fabric portfolio project covering the DP-600 domains: medallion (Bronze/Silver/Gold) architecture over 555K rows, semantic model with DAX measures, KQL real-time monitoring, RLS/OLS and deployment pipelines. | Microsoft Fabric · OneLake · KQL · DAX · Power BI |
| [E-Commerce Intelligence Platform](https://github.com/erickyegon/ecommerce-intelligence-platform) | Lakehouse pipeline: 1.7M rows, 6 relational tables, medallion architecture, conversion and segmentation models tracked in MLflow. | Databricks · Delta Lake · MLflow |

---

## Impact at a Glance

<!-- VERIFY: rows 5-8 and the publications row come from the previous profile README and are not stated in any repo. Confirm against resume before publishing, or delete. ORCID lists 1 work (a Lancet item); the previous text said "30+ articles incl. The Lancet Global Health". -->
| What I built | Result |
|---|---|
| **Immunization defaulter risk engine** (Kenya MOH eCHIS) | ROC-AUC 0.892 · 6,864 children · 4,672 CHW areas · [live app](https://immunizationengine.streamlit.app/) |
| **Medicaid obesity-drug coverage study** | +12.2 prescriptions per 1,000 enrollees per quarter (95% CI 8.4 to 16.0); about $161.3M net over five years per 1M enrollees · [incretin-access-value](https://github.com/erickyegon/incretin-access-value) |
| **Oncology RWD pipeline validated against a known truth** | 98.1% line-of-therapy exact match; 10-seed Monte-Carlo bias and coverage · [nsclc-rwd-truth-recovery](https://github.com/erickyegon/nsclc-rwd-truth-recovery) |
| **CertiAce Retail Analytics** (Fabric portfolio) | Medallion lakehouse · 555K rows · DAX · KQL · RLS/OLS · deployment pipelines |
| ML predictive models for health outcomes | ~30% improvement in prediction accuracy |
| Automated data pipelines (ClickHouse + Python + dbt) | Reporting latency: 10–14 days → **real-time** |
| Causal inference and RWE studies | 25+ production studies informing program decisions |
| Healthcare analytics platforms | Scale: **8.5M+ individuals** across multiple health systems |
| Peer-reviewed publications | Including *The Lancet* · [ORCID](https://orcid.org/0000-0002-7055-4848) |

---

## Skills and where to see them

| Skill | Evidence |
|---|---|
| Survival analysis (Kaplan–Meier, Cox, time-varying exposure) | [oncology-rwe-nsclc](https://github.com/erickyegon/oncology-rwe-nsclc) · [nsclc-rwd-truth-recovery](https://github.com/erickyegon/nsclc-rwd-truth-recovery) |
| Pharmacoepidemiology methods (IPTW, immortal-time bias, E-value) | [nsclc-rwd-truth-recovery](https://github.com/erickyegon/nsclc-rwd-truth-recovery) |
| Causal inference (difference-in-differences, event study) | [incretin-access-value](https://github.com/erickyegon/incretin-access-value) |
| OMOP CDM, dbt, PostgreSQL | [oncology-rwe-nsclc](https://github.com/erickyegon/oncology-rwe-nsclc) · [incretin-access-value](https://github.com/erickyegon/incretin-access-value) |
| Budget impact / health economics | [incretin-access-value](https://github.com/erickyegon/incretin-access-value) |
| R, Quarto, Shiny | [incretin-access-value](https://github.com/erickyegon/incretin-access-value) · [within-reach](https://github.com/erickyegon/within-reach) |
| Python, scikit-learn, lifelines | [nsclc-rwd-truth-recovery](https://github.com/erickyegon/nsclc-rwd-truth-recovery) |
| XGBoost, SHAP, calibration, drift monitoring | [immunization-defaulter-risk-engine](https://github.com/erickyegon/immunization-defaulter-risk-engine) |
| MLflow, Optuna | [immunization-defaulter-risk-engine](https://github.com/erickyegon/immunization-defaulter-risk-engine) · [insurance-premium-prediction-ml](https://github.com/erickyegon/insurance-premium-prediction-ml) |
| FastAPI, Docker, Streamlit | [immunization-defaulter-risk-engine](https://github.com/erickyegon/immunization-defaulter-risk-engine) |
| AWS SageMaker | [insurance-premium-prediction-ml](https://github.com/erickyegon/insurance-premium-prediction-ml) |
| PyTorch (CNN) | [FreshHarvest](https://github.com/erickyegon/FreshHarvest) |
| RAG, vector search (ChromaDB, pgvector, Pinecone) | [clinical-doc-intelligence](https://github.com/erickyegon/clinical-doc-intelligence) · [womens-health-rag](https://github.com/erickyegon/womens-health-rag) · [AI-Powered-Research-Assistant](https://github.com/erickyegon/AI-Powered-Research-Assistant-for-Scientific-Papers) |
| LangChain, LangGraph, multi-agent systems | [AgentCare](https://github.com/erickyegon/AgentCare) · [clinical-doc-intelligence](https://github.com/erickyegon/clinical-doc-intelligence) |
| Microsoft Fabric, OneLake, KQL, deployment pipelines | [certace-fabric-analytics](https://github.com/erickyegon/certace-fabric-analytics) |
| Power BI, DAX, RLS/OLS | [certace-fabric-analytics](https://github.com/erickyegon/certace-fabric-analytics) |
| Databricks, Delta Lake, Unity Catalog | [community-health-intelligence-platform](https://github.com/erickyegon/community-health-intelligence-platform) · [databricks-medicare-lakehouse](https://github.com/erickyegon/databricks-medicare-lakehouse) |
| Airflow | [community-health-intelligence-platform](https://github.com/erickyegon/community-health-intelligence-platform) |

---

## Education

| Degree | Institution |
|---|---|
| **PhD, Epidemiology** | Jomo Kenyatta University of Agriculture and Technology (JKUAT) |
| **MSc, Health Systems Management** | Kenya Methodist University |
| **BSc, Statistics** | University of Nairobi |

---

## Certifications

<!-- VERIFY: confirm exact credential names and status for each row, in particular the AWS and Stanford entries. -->
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

## How I Work

I pair statistical rigor with working software. I check my methods against a known answer where I can, document where a data source fails validation, and ship analyses as reproducible pipelines. The [NSCLC truth-recovery study](https://github.com/erickyegon/nsclc-rwd-truth-recovery) and the [Synthea-versus-SEER benchmark](https://github.com/erickyegon/oncology-rwe-nsclc) are examples.

---

## Open To

**Hands-on and leadership roles** across real-world evidence, epidemiology, health data science and applied AI:

- **Real-World Evidence Scientist / Epidemiologist**
- **Senior / Principal / Lead Data Scientist** (healthcare and clinical)
- **Population Health Analytics Lead**
- **Analytics Engineer / Microsoft Fabric Engineer**
- **Director / VP, Data & Analytics**

**Target sectors:** Pharma · Biotech · CRO · Health Systems · Payers & Insurers · Health Tech · Global Health · Federal Contractors

---

<div align="center">

📩 **keyegon@gmail.com** &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/erickyegon) &nbsp;|&nbsp; 🆔 [ORCID](https://orcid.org/0000-0002-7055-4848)

</div>

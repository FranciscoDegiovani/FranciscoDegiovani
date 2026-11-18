### Hi, I'm Francisco

Data scientist with an MBA in AI & Big Data (USP) and an M.Sc. in Bioinformatics in its final stage (USP), bridging molecular biology, statistics, machine learning and generative AI. I build reproducible data pipelines, apply ML to complex, high-dimensional datasets (currently multi-omics cancer data from TCGA) and build LLM agents grounded in real data, with their accuracy measured through automated evaluation. I also have hands-on experience in structural bioinformatics, connecting genomic sequence to protein structure and function.

Interested in: Data Science, Generative AI & LLM Agents, Bioinformatics, Machine Learning, Data Engineering
Currently deepening: LLM agents and RAG, LLM evaluation, cloud data architecture, predictive modeling
Based in Brazil, open to remote roles

--- 

### Tech Stack

**Languages & Data**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Machine Learning & AI**
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)

**Generative AI**
![LLM Agents](https://img.shields.io/badge/-LLM%20Agents-5A4FCF?style=flat)
![RAG](https://img.shields.io/badge/-RAG-0F766E?style=flat)
![Sentence Transformers](https://img.shields.io/badge/-Sentence%20Transformers-FFD21E?style=flat&logo=huggingface&logoColor=black)
![Gemini API](https://img.shields.io/badge/-Gemini%20API-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
- Tool calling · Retrieval-augmented generation · LLM evaluation · Guardrails · Model fallback

**Structural Bioinformatics**
![AutoDock Vina](https://img.shields.io/badge/-AutoDock%20Vina-3C6E71?style=flat)
![GROMACS](https://img.shields.io/badge/-GROMACS-3E7C17?style=flat)
![MODELLER](https://img.shields.io/badge/-MODELLER-555555?style=flat)
- Molecular docking · Sequence alignment · Virtual screening · Molecular dynamics simulations

**Data Engineering & Big Data**
![Snakemake](https://img.shields.io/badge/-Snakemake-039475?style=flat)
![Nextflow](https://img.shields.io/badge/-Nextflow-0DC09D?style=flat&logo=nextflow&logoColor=white)
![Spark](https://img.shields.io/badge/-Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)

**Tools & Infra**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat&logo=linux&logoColor=black)

---

### Featured Projects

**[E-commerce AI Assistant: LLM Agent with SQL Tools and RAG](https://github.com/FranciscoDegiovani/ecommerce-ai-assistant)** · [Live demo](https://technova-assistant.streamlit.app)
Customer-service chatbot where an LLM agent decides which tool to call: SQL queries over 5,000 real e-commerce orders (Olist), RAG over store policies with multilingual embeddings, and aggregation of real customer reviews. Evaluated with 30 automated test cases, including prompt injection and personal-data requests: 100% tool-routing accuracy. The evaluation caught a retrieval failure (95% factual accuracy); after diagnosing and fixing it, factual accuracy reached 100%. Includes retry with backoff, automatic fallback across models, input validation, and a Streamlit chat deployed online.

**[Five-Year Mortality Prediction in Endometrial Cancer — TCGA-UCEC (MBA Capstone)](https://github.com/FranciscoDegiovani/tcc-mba-endometrio-ml-usp)**
ML pipeline predicting 5-year mortality from tumor transcriptomes (10,164 genes), with explicit censoring correction (522 → 183 patients) and leakage control (SMOTE inside CV, single master split). Compares LASSO, Random Forest, XGBoost and SVM with McNemar tests and bootstrap CIs — LASSO reached AUC 0.69 with a 43-gene signature — plus a controlled AWST vs log2(TPM+1) normalization analysis.

**[Multi-Omics Survival Analysis — TCGA-BRCA (MOFA2)](https://github.com/FranciscoDegiovani/tcga-brca-multiomics-survival)**
Integration of RNA-seq and DNA methylation data (866 matched patients) using MOFA2 to identify latent factors, followed by Cox regression and Kaplan-Meier analysis — two factors significantly associated with survival (p < 0.005), cross-platform pipeline (R + Python).

**[Structural Bioinformatics — FOXJ1 Forkhead Domain](https://github.com/FranciscoDegiovani/foxj1-forkhead-structural-screening)**
AlphaFold structural modeling, pocket detection, and virtual screening pipeline for a transcription factor target — molecular docking (AutoDock Vina) against a curated library of approved drugs, with visual pose validation.

**[RNA-seq Differential Expression Analysis — DESeq2](https://github.com/FranciscoDegiovani/rnaseq-deseq2-airway)**
Genomics/transcriptomics analysis identifying differentially expressed genes (DESeq2, R/Bioconductor), orchestrated as a Snakemake pipeline for full reproducibility — statistical modeling, MA-plot, volcano plot, PCA, and heatmap visualization.

**[Breast Cancer Classification — Logistic Regression vs. Random Forest](https://github.com/FranciscoDegiovani/ml-classification-breast-cancer)**
Clinical data classification (malignant/benign) with model comparison, cross-validation, and ROC/AUC evaluation — 98.2% accuracy with feature importance validated against biological expectations.

**[Exploratory Data Analysis — Online Retail](https://github.com/FranciscoDegiovani/python-eda-retail)**
End-to-end EDA on real UK e-commerce transaction data (541K+ records) — revenue analysis, seasonality, outlier investigation, and data storytelling with Python and Pandas.

**[SQL Practice — Chinook Database](https://github.com/FranciscoDegiovani/sql-chinook-analysis)**
6 business-style SQL queries (joins, window functions, CTEs, subqueries) on a relational database, with tested and documented results.

---

### Background

- **M.Sc. in Bioinformatics** — University of São Paulo (FMRP-USP), 2025–2026
- **MBA in Artificial Intelligence & Big Data** — University of São Paulo (ICMC-USP), 2025–2026 (completed)
  - Coursework: Data Science & Machine Learning · Large-scale Parallel Data Processing · Statistics with R · Neural Networks & Deep Learning · Data Governance · Cloud Infrastructure & Security · Data Visualization · [Capstone: 5-year mortality prediction in endometrial cancer](https://github.com/FranciscoDegiovani/tcc-mba-endometrio-ml-usp)
- **B.Sc. in Biotechnology** — Federal University of Alfenas (UNIFAL), 2020–2025

---

### Connect

[LinkedIn](https://www.linkedin.com/in/francisco-martins-degiovani-165671313/) · francisco.degiovani@outlook.com

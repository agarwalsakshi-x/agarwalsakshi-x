# Hi, I'm Sakshi 👋

**MSBA @ UMass Amherst (GPA 3.9) · Ex-Accenture · Graduated May 2026**

Before grad school, I spent three years at **Accenture** working on enterprise data quality and compliance for life-science platforms (Takeda Pharmaceuticals), and that's where I learned that the hardest part of analytics isn't the model — it's asking the right question.

I work across the full stack: SQL for operational analysis, Python for modeling, Power BI and Tableau for communicating results to people who don't live in spreadsheets. My projects span healthcare claims analytics, supply chain risk, credit risk, churn, and location optimization, but the through-line is always the same: find what the data is actually saying and make it useful to someone. I also leverage AI tools to accelerate workflows — from faster data exploration to cleaner documentation — so I can spend more time on the analysis that actually matters.

Looking for **Data Analyst or Business Analyst** roles in healthcare analytics, payer-side organizations, or anywhere technical depth and business judgment both matter.

## 🔍 What I Work On

My projects focus on **end-to-end analytics workflows**, including:

- Data cleaning, exploratory analysis, and feature engineering
- Machine learning for prediction and decision support
- SQL-based business analytics and KPI development
- Dashboarding and visualization for stakeholder communication
- Translating analytical results into **actionable business recommendations**

## 📂 Featured Projects

### CMS Medicare Claims Analytics Dashboard (Python, Power BI)
Before a single chart was built, data validation revealed that 64% of raw inpatient claims were duplicates — $6.1M in potentially double-counted Medicare payments that would have corrupted every downstream metric if left uncorrected. After cleaning 633K+ records across 3 CMS files, the analysis surfaced 3 high-impact findings: (1) a 104-day hospital stay miscoded as a routine DRG was reimbursed at only $28K — a significant revenue loss for the provider; (2) COPD with major complications (DRG 190) drives both the longest average stay (13.4 days) and the second-highest cost ($117K) — a clear target for utilization management intervention; (3) a single CKD Stage 4 patient generated 783 outpatient visits in 8 years, confirming that chronic disease concentration — not procedure volume — is the primary driver of Medicare outpatient spend. Built a 5-page Power BI dashboard translating these findings into actionable insights for payer-side analytics and care management teams.

**Repo:** https://github.com/agarwalsakshi-x/CMS-Medicare-Analysis

### Loan Approval Prediction (Python, Machine Learning)
Identified that optimizing for accuracy alone would miss 40% of high-risk applicants — shifted to recall-focused evaluation using decile analysis to surface the top risk drivers that lenders actually care about. The result: a model that supports smarter credit decisioning by flagging the applicants most likely to default, not just the ones easiest to classify.

**Repo:** https://github.com/agarwalsakshi-x/Predicting-Loan-Approval

### Customer Churn Prediction & Retention Strategy (Python, Machine Learning)
Found that 26% of telecom customers were at high churn risk — concentrated in month-to-month contracts and fiber optic users with no bundled services. Built a churn model (AUC 0.85) and translated the output into a tiered retention strategy: targeted discounts for high-risk segments, bundle upsells for mid-risk, and loyalty rewards for low-risk — linking model predictions directly to revenue protection.

**Repo:** https://github.com/agarwalsakshi-x/IBM-Telco-Customer-Churn

### U.S. State Relocation Decision Dashboard (Excel, Power Query, XLOOKUP)
Turned a fragmented decision — where should I live? — into a structured, data-driven framework. Integrated cost of living, crime, weather, and housing data across all 50 states into a single interactive Excel dashboard, enabling users to rank and filter states by what matters most to them. The insight: the "best" state shifts dramatically depending on whether you weight affordability vs. safety vs. climate.

**Repo:** https://github.com/agarwalsakshi-x/US_Relocation_Excel_dashboard

### Supply Chain Performance & Risk Analytics (SQL, Tableau)
Processed 100K+ supplier records and found that 15% of suppliers accounted for 60% of delivery delays — a classic concentration problem that most supply chain reports miss by averaging across all vendors. Built SQL-based KPIs and a Tableau dashboard that let operations teams drill into specific supplier risk factors and take targeted corrective action instead of applying blanket fixes.

**Repo:** https://github.com/agarwalsakshi-x/supplychain-performance-sql

### Amazon Prime Air Drone Hub Optimization (Supply Chain Analytics, Location Modeling)
Determined that a single centralized hub would leave 34% of Massachusetts residents outside viable delivery range — and that a three-hub configuration using Center of Gravity and Huff demand modeling could achieve near-complete statewide coverage with lower operational cost than a four-hub alternative. Recommended a phased deployment strategy that balances coverage expansion against capital investment.

**Repo:** https://github.com/agarwalsakshi-x/Amazon-Prime-Air-Drone-Hub-Analysis

## 🛠 Skills & Technologies

**Databases & Data Querying**
- SQL (Joins, Aggregations, CTEs, Window Functions)
- Relational databases, data warehousing concepts, Snowflake

**Data Analysis & Machine Learning**
- Python (Pandas, NumPy, Scikit-learn)
- EDA, data cleaning, feature engineering
- Logistic Regression, Decision Trees, Random Forest, Neural Networks
- Model evaluation: AUC, Precision-Recall, Cross-Validation

**Healthcare Analytics**
- CMS Medicare claims data (Inpatient, Outpatient, Beneficiary)
- DRG codes, ICD-10, CPT/HCPCS coding systems
- Revenue cycle concepts: AR days, denial management, payer analysis
- HIPAA awareness

**Business & Product Analytics**
- KPI design, cohort & retention analysis, churn modeling
- Forecasting, segmentation, decision support, A/B testing concepts

**Visualization & Reporting**
- Tableau, Power BI (DAX, Power Query), Excel dashboards
- Data storytelling for non-technical stakeholders

**Cloud & Data Engineering (Foundational)**
- AWS & Azure fundamentals, cloud storage & compute
- ETL/ELT basics, structured vs. streaming data

**Tools & Collaboration**
- GitHub, Jupyter Notebook, Google Colab
- Agile fundamentals, requirements gathering, stakeholder communication
- AI-Augmented Analytics — Claude, ChatGPT for accelerating EDA, code generation, documentation, and translating business questions into analytical frameworks

## 🌐 Let's Connect

- LinkedIn: https://linkedin.com/in/sakshiagarwal19
- Email: 8sakshi.agarwal@gmail.com

Thanks for visiting — feel free to explore the repositories or reach out!

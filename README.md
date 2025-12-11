# Hi there 👋

I’ve always been drawn to understanding how people use products — what works, what doesn’t, and why.  
After 15+ years in product management, I wanted to go deeper and learn how the analytical pipelines, models, and dashboards behind better decisions are built.

Today I focus on building clean, thoughtful analytics that bridge product understanding and modern data engineering.

---

## 🧩 How I work with the modern data stack

Over the last year, I recreated real-world workflows across the full analytics lifecycle —  
from ingesting raw data to modeling it into meaningful structures and visualizing the story behind it.  
Here’s what that journey looks like:

---

### 📥 1) Data Loading & Integration (EL)

This is where raw operational data turns into structured, analysis-ready datasets.  
Using **Fivetran**, I built automated ingestion pipelines that feed directly into cloud warehouses.

**Example:**  
[Ecom - Cohort Retention](https://github.com/t-jor/cohort-retention-analytics) – ingestion of transactional e-commerce data for retention modeling.

---

### **🏛️ 2) Data Warehousing & Storage**

I worked with multiple warehouse setups — **Snowflake**, **BigQuery**, and **Databricks** — to explore how different environments shape data workflows.  
Each project taught me something different about performance, scaling, and design decisions.

**Examples:**

- [PowerFlow - Marketing ROI](https://github.com/t-jor/marketing-roi-analytics) – Snowflake warehouse for marketing & behavioral data  
- [Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) – Snowflake warehouse for theater-level revenue & cost data  
- [HealthTail - Medication Audit](https://github.com/t-jor/diagnosis-medication-audit) – stand-alone BigQuery warehouse for diagnosis & medication trend modeling
- [Ecom - Cohort Retention](https://github.com/t-jor/cohort-retention-analytics) – hybrid BigQuery + Delta Lake setup (raw data in BigQuery, refined Delta tables in Databricks)

---

### **🧱 3) Data Modeling & Transformation**

This is where everything comes together.  
I used **dbt Cloud**, **SQL**, and **Jinja** to turn raw datasets into clean, testable, analytics-ready models — often following a medallion-style architecture.

**Examples:**  
[PowerFlow - Marketing ROI](https://github.com/t-jor/marketing-roi-analytics) ·  
[Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) ·  
[MarketFlash - Campaign Database](https://github.com/t-jor/campaign-database-design) ·  
[TravelTide - Customer Loyalty](https://github.com/t-jor/customer-loyalty-segmentation)

---

### **📊 4) BI & Dashboarding**

I enjoy the storytelling side of analytics — turning models into intuitive dashboards that highlight what really matters.  
I’ve worked with **Tableau** and **Looker Studio** to build clean, decision-oriented visualizations.

**Examples:**  
[Spotify - Streaming KPIs](https://github.com/t-jor/music-streaming-kpi-analytics) ·  
[Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) ·  
[MarketFlash - Campaign Database](https://github.com/t-jor/campaign-database-design) ·  
[HealthTail - Medication Audit](https://github.com/t-jor/diagnosis-medication-audit)

---

## 🧰 Core Tech Stack

**Warehousing:** Snowflake · BigQuery · Databricks  
**Modeling:** dbt Cloud · SQL · Jinja · Medallion Architecture  
**ELT:** Fivetran · Delta Lake  
**Analytics:** Tableau · Looker Studio  
**Programming:** Python (basics · pandas)
**Other:** Git · GitHub · Relational modeling · Databricks Notebooks (SQL + light PySpark)

---

## 📬 More

You can find [My Dashboards and Visualizations](https://public.tableau.com/app/profile/thomas.jortzig/vizzes) on Tableau Public

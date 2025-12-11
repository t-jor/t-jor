# Hi there 👋

I’ve always been drawn to understanding how people use products — what works, what doesn’t, and why.  
After 15+ years in product management, I wanted to go deeper and learn how to build the analytical pipelines, models, and dashboards behind better decisions.

Over the past year, as part of my professional transition and hands-on analytics training, I built several end-to-end projects that mirror real modern data-stack workflows.

Today I focus on building clean, thoughtful analytics that connect product understanding and modern data engineering.

---

## 🧩 How I work with the modern data stack

Throughout this journey, I recreated real-world workflows across the full analytics lifecycle —  
from ingesting raw data to modeling it into meaningful structures and visualizing the story behind it.  
Here’s how the different layers fit together:

---

### 📥 1) Data Loading & Integration (EL)

This is where raw operational data becomes structured and ready for analysis.  
Using **Fivetran**, I built automated ingestion pipelines that feed directly into cloud warehouses.

**Example:**  
[Ecom - Cohort Retention](https://github.com/t-jor/cohort-retention-analytics) – ingestion of transactional e-commerce data for retention modeling

---

### **🏛️ 2) Data Warehousing & Storage**

I worked with multiple warehouse setups — **Snowflake**, **BigQuery**, and **Databricks** — to explore how different environments shape data workflows.

**Examples:**

- [PowerFlow - Marketing ROI](https://github.com/t-jor/marketing-roi-analytics) – Snowflake warehouse for marketing & behavioral data  
- [Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) – Snowflake warehouse for theater-level revenue & cost data  
- [HealthTail - Medication Audit](https://github.com/t-jor/diagnosis-medication-audit) – stand-alone BigQuery warehouse for diagnosis & medication trend modeling
- [Ecom - Cohort Retention](https://github.com/t-jor/cohort-retention-analytics) – hybrid BigQuery + Delta Lake setup (raw data in BigQuery, refined Delta tables in Databricks)

---

### **🧱 3) Data Modeling & Transformation**

This is where everything comes together. I used **dbt Cloud**, **SQL**, and **Jinja** to turn raw datasets into clean, testable, analytics models — often following a medallion-style approach to separate staging, transformation logic, and analytics outputs.

**Examples:**

- [PowerFlow - Marketing ROI](https://github.com/t-jor/marketing-roi-analytics) — modeling attribution, spend, and conversion metrics
- [Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) — building modular revenue/cost models in dbt  
- [MarketFlash - Campaign Database](https://github.com/t-jor/campaign-database-design) — deriving KPIs from a relational schema using SQL
- [TravelTide - Customer Loyalty](https://github.com/t-jor/customer-loyalty-segmentation) — engineering segmentation features and perk logic

---

### **📊 4) BI & Dashboarding**

I enjoy the storytelling side of analytics — turning models into intuitive dashboards that highlight what matters most.  
I used **Tableau** and **Looker Studio** to design clean, decision-focused data stories.

**Examples:**

- [Spotify - Streaming KPIs](https://github.com/t-jor/music-streaming-kpi-analytics) — engagement, churn drivers, monetization metrics
- [Silverscreen - Cinema Profitability](https://github.com/t-jor/cinema-profitability-analytics) — theater-level insights for revenue, occupancy, cost
- [MarketFlash - Campaign Database](https://github.com/t-jor/campaign-database-design) — campaign performance & regional breakdowns
- [HealthTail - Medication Audit](https://github.com/t-jor/diagnosis-medication-audit) — diagnosis & medication trends (Looker Studio)

---

## 🧰 Core Tech Stack

**Warehousing:** Snowflake · BigQuery · Databricks  
**Modeling:** dbt Cloud · SQL · Jinja · Medallion Architecture  
**ELT:** Fivetran · Delta Lake  
**Analytics:** Tableau · Looker Studio  
**Programming:** Python (basics, pandas)  
**Other:** Git · GitHub · Relational modeling · Databricks Notebooks (SQL + light PySpark)

---

## 📬 More

You can find [my dashboards and visualizations](https://public.tableau.com/app/profile/thomas.jortzig/vizzes) on Tableau Public.

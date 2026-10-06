<div align="center">
    <img src="https://github.com/AtilaKzlts/ELT-Pipeline/blob/main/assets/Atilla-Portf.png" alt="Header Image" width="100%">
    <br><br>
    <div class="skills-list">
        <a href="https://github.com/AtilaKzlts/SaaS/blob/main/assets/Atilla_Kiziltas_Data_Analytics_Hybrid_CV.pdf" target="_blank">
            <img src="https://img.shields.io/badge/RESUME-Click%20To%20View-blue?style=for-the-badge&logo=googledocs&logoColor=white" alt="Resume">
        </a>
        <br><br>
        <h4>Tools & Technologies 🛠</h4>
        <table>
            <tr>
                <td><b>▪ Python, R</b></td>
                <td><b>▪ Apache Spark, Apache Kafka </b></td>
            </tr>
            <tr>
                <td><b>▪ Tableau, Looker, QuickSight</b></td>
                <td><b>▪ GA4, GTM, Google Ads</b></td>
            </tr>
            <tr>
                <td><b>▪ SQL (PostgreSQL), BigQuery</b></td>
                <td><b>▪ dbt </b></td>
            </tr>
            <tr>
                <td><b>▪ Apache Airflow, n8n (workflow orchestration)</b></td>
                <td><b>▪ Amplitude, Mixpanel (product analytics)</b></td>
            </tr>
            <tr>
                <td><b>▪ AWS (Glue, Athena, S3, CloudWatch), Snowflake, Databricks</b></td>
                <td><b>▪ Git, Docker, Linux, NLP </b></td>
            </tr>
        </table>
    </div>
</div>

---

*Click title to see implementation details, code & documentation*

| 🔗 Project Link| Core Technologies | Business Problem Solved | Impact & Key Metrics |
|---|---|---|---|
| [End-to-End Data Analytics for SaaS  ](https://github.com/AtilaKzlts/SaaS/tree/main) | AWS Glue (PySpark ETL), Athena, S3 Data Lake, Airbyte, QuickSight, CloudWatch | Platform-specific performance bottlenecks driving 48% user drop-off post-signup—unable to isolate root cause from raw event logs | **$42K+ revenue recovery identified**. Processed 30K+ daily behavioral events via Glue pipelines. Built dimension tables + funnel analysis in Athena. Diagnosed platform logic bug causing drop-off. Delivered actionable product roadmap to engineering team. |
| [Customer Feedback Analysis on New Product Launch  ](https://github.com/AtilaKzlts/Youtube-Sentiment-Topic) | BERT sentiment classification, BERTopic topic modeling, NLP | Post-launch market reaction unclear—product/marketing teams blind to customer pain points and feature requests buried in 10.000+ social comments | **92% sentiment classification accuracy**. Extracted 8 major customer concern topics (UX friction, pricing, integration requests). Automated daily report fed directly to Product & Marketing. Shaped roadmap priorities, preventing churn risk and optimizing marketing messaging. |
| [Price Elasticity & Inventory Optimization  ](https://github.com/AtilaKzlts/Inventory-Price-Elasticity-Analysis/tree/main) | Consumer behavior modeling, statistical analysis, price optimization, marketing strategy | Dynamic pricing decisions made on gut feel, losing margin to underpriced items and volume to overpriced ones | Elasticity analysis revealed **3 SKU price points with 15-25% margin improvement potential**. Competitor pricing + promotional impact modeling enabled data-driven pricing strategy. Reduced pricing cycle from monthly guesswork to data-informed decisions. |
| [AI Analytics Copilot](https://github.com/AtilaKzlts/analytics-copilot) | LangChain, dbt orchestration, Groq API (open-source LLM inference), Z-score anomaly detection | Non-technical teams (Sales, Marketing) blocked by SQL bottleneck—3-4 hour wait for simple ad-hoc queries. Analyst bandwidth saturated. | Plain-English query interface → SQL translation → anomaly detection + LLM business insights. **Pilot phase:** 8 users, ~12 queries/day, **85% first-attempt accuracy**. **~3 hours/day analyst time freed**—reallocated to strategic work. Cost: Groq vs OpenAI saved **70% inference spend**. Deployed as internal tool. |
| [Admin Dashboard](https://public.tableau.com/app/profile/atilla.kiziltas/viz/AdminDashboard_17615866862640/Summary) | Tableau, real-time metrics, business intelligence | Daily e-commerce operations lack centralized KPI visibility—executives piecing together data from 4+ systems | **Real-time daily metrics dashboard** (revenue, orders, AOV, GMV, user acquisition trends). Auto-refreshed hourly. Single source of truth for exec standups. Reduced reporting time by 2 hours/day. Used by 6-person leadership team. |
| [ELT Pipeline for E-commerce Analytics   ](https://github.com/AtilaKzlts/ELT-Pipeline) | Apache Airflow (DAG orchestration), Snowflake, AWS S3 data lake, dbt (45+ transformation models), Tableau, email alerting | Manual daily reporting taking 4+ hours. Data freshness lagging 12-24 hours. No failure notifications = data outages undiscovered. | **Fully automated S3 → Snowflake → dbt → Tableau pipeline**. Reduced reporting from 4 hours/day to 15 min refresh cycle. **Data freshness improved from 24h → 2h**. Added dbt tests (row counts, null checks, referential integrity) catching 95% of upstream data issues before dashboards update. Slack alerting on Airflow failures. Designed for small e-commerce company; scales to 500M+ rows annually. |
| [Web Development Insights Dashboard](https://github.com/AtilaKzlts/Device-and-Browser-Performance-Analysis) | GA4 API, BigQuery SQL, Looker visualization, cross-device analytics | Web dev team flying blind on browser/device performance issues—bounce rates and session quality varying wildly by device, root cause unknown | **Cross-device performance segmentation** (iOS Chrome vs Android Firefox vs desktop Safari). Identified **3 device/browser combos with 35% higher bounce rate**. Prioritized fixes (mobile form validation, responsive design gaps). Bounce rate reduced **8% in 3 months** post-optimization. |
| [Marketing Performance Dashboard](https://public.tableau.com/app/profile/atilla.kiziltas/viz/MarketingPerformance_17615868598940/Dashboard2) | Tableau, marketing KPIs, campaign analytics, ROI tracking | Marketing campaigns lack unified ROI visibility—channel performance and CAC scattered across 5 systems | **Centralized marketing dashboard** tracking customer acquisition cost (CAC), conversion rate, LTV, channel-level ROI. Updated daily from ad platforms (Google Ads, Meta, etc.). **Revealed underperforming channel** (organic search) and top performer (LinkedIn). Reallocated budget, **improved overall ROAS by 23%**. |

---


##  **What I Bring**

- **End-to-end analytics ownership**—data pipeline → transformation → visualization → business decision  
- **Bridge between data & business**—translate messy requirements into actionable insights  
- **Production mindset**—monitoring, alerting, documentation, test coverage  
- **Tool agnostic**—pick the right tool for the job (cloud: AWS/Snowflake/Databricks, tools: dbt/Airflow/Spark, BI: Tableau/Looker)  


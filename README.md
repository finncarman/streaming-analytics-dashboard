# Streaming Subscription Analytics Dashboard

An end-to-end data analytics project exploring retention, churn, revenue growth, and lifetime value across customer cohorts for a subscription-based streaming platform.

---

## Project Overview
This project combines **SQL** data preparation and **Tableau** visualisation to uncover trends in customer behaviour, helping understand what drives retention and long-term growth.

The dataset simulates real-world subscription activity, including join dates, cancellation data, and payment details. It was cleaned, transformed, and visualised to deliver actionable insights.

---

## Objectives
- Identify customer churn and retention trends over time.  
- Analyse cohort-based revenue and lifetime value growth.  
- Evaluate customer tenure and average engagement period.  
- Build a professional analytics dashboard to visualise KPIs and trends clearly.

---

## Repository Structure
    streaming-analytics-dashboard/
    ├── data/
    │   ├── Subscription Cohort Analysis Data.csv
    │   └── Subscription Cohort Analysis Data Dictionary.csv
    │
    ├── sql/
    │   └── streaming_data_cleaning_queries.sql
    │
    ├── tableau/
    │   └── dashboard_screenshot.png
    │
    └── README.md

---

## Tools Used
- **SQL (MySQL Workbench)** – Data cleaning, transformation & cohort preparation.  
- **Tableau Public** – Dashboard design & visualisation.  
- **Excel** – Exploratory review and data validation.

---

## SQL Workflow Summary
1. Imported the raw CSV and formatted `created_date` and `canceled_date` columns.  
2. Calculated active users per month, churned users, and retention by cohort.  
3. Derived key KPIs:
   - Churn Rate %
   - Retention Rate %
   - Average Tenure (Months)
   - Total & Cumulative Revenue
   - Estimated Customer Lifetime Value (LTV)
4. Exported cleaned and aggregated tables for Tableau.

---

## Tableau Dashboard

**[View the Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/finn.carman/viz/StreamingDataAnalysis_17633808570700/StreamingAnalyticsDashboard)**

<img width="1598" height="1278" alt="Streaming Analytics Dashboard" src="https://github.com/user-attachments/assets/d51da8a9-9e9d-4981-9680-31312f689c99" />

---

## Key Insights
- Retention improved mid-year before tapering off in later cohorts.  
- Revenue grew steadily, surpassing **£120K cumulative** by the end of the observed period.  
- Average customer tenure stabilised around **12 months**.  
- Later cohorts showed higher **LTV**, indicating stronger engagement and user value.

---

## Learnings & Takeaways
- Reinforced experience in SQL cleaning, joining, and aggregating time-based datasets.  
- Enhanced Tableau design skills, focusing on layout, KPI hierarchy, and interactive storytelling.  
- Strengthened understanding of subscription analytics — churn, retention, and LTV modelling.

---

## License
This project is open-source and available under the [MIT License](LICENSE).

---

© 2025 Finn Carman – Data Analytics Portfolio Project


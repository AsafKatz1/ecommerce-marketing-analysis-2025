
# Marketing and Customer Analysis Project

This project analyzes marketing spend, revenue, and customer retention using the [Marketing Insights for E-Commerce Company](https://www.kaggle.com/datasets/rishikumarrajvansh/marketing-insights-for-e-commerce-company) dataset (12-month period).

---

## Project Overview
The goal is to evaluate the relationship between marketing activities and business performance, and to understand customer behavior across locations.

**Part I – Marketing Spend Analysis**  
- Examines the effect of total, online, and offline marketing spend on weekly revenue and customer acquisition.  
- Controls for seasonality and lagged effects to isolate marketing impact.

**Part II – Cohort and Segmentation Analysis**  
- Analyzes customer retention patterns and revenue by location.  
- Includes cohort matrices, retention curves, and top-revenue products per region.

---

## Tools 
- Python (pandas, numpy, statsmodels-formula, matplotlib, seaborn)
---

## Key Findings
- Marketing spend (current and lagged) shows no significant effect on revenue once seasonality is considered.  
- Retention rates are similar across most regions; Washington DC has fewer customers and slightly higher retention.  
- The *Nest Learning Thermostat 3rd Gen – USA (Stainless Steel)* is the top-revenue product in 4 of 5 locations.  
- A mid-year retention boost (~6 months) may indicate seasonality or campaign timing.

---

## Repository Contents
- `Marketing_Customers_Project_AsafKatz.ipynb` – Full analysis notebook  
- `README.md` – Project description  
- *(No raw data included; dataset link above.)*

---

## How to View
Open the notebook directly on GitHub or through [nbviewer](https://nbviewer.org/github/AsafKatz1/ecommerce-marketing-analysis-2025/blob/main/Marketing_Customers_Project_AsafKatz.ipynb?flush=1
) for a cleaner display.

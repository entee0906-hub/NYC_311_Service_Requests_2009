# NYC 311 Service Requests — 2009

**Data analysis & dashboard** of NYC 311 service requests in 2009.  
Cleaned with Python (Pandas), exploratory analysis in a Kaggle notebook, and interactive visualization built in Tableau Public. This repo contains the analysis notebook, dashboard screenshots, and instructions to reproduce the work.

---



## Project Summary

- **Objective:** Explore NYC 311 complaints from 2009 to identify top complaint types, borough-level patterns, seasonal trends, and service response-time differences.  
- **Dataset size used during analysis:** ~1.78M rows (full dataset used during analysis, not included here).  
- **This repo contains:** a reproducible Kaggle notebook (cleaning & EDA), and portfolio-ready Tableau screenshots for sharing.

---

## Key Insights (high level)

- **Top complaint types:** HEATING, Street Light Condition, General Construction, Plumbing.  
- **Borough volumes:** Queens and Brooklyn produced the highest complaint volumes in 2009.  
- **Seasonality:** Heating complaints spike in winter months.  
- **Response times:** Noticeable differences in average closure times between boroughs.

---
## Interactive Dashboard

Click the image to view the interactive dashboard on Tableau Public:

[![NYC 311 Dashboard](Tableau/Screenshots/Dashboard_Full.png)](https://public.tableau.com/authoring/NYC311ServiceRequestsDashboard2009/NYC311ServiceRequests2009#1)

**Live dashboard:** https://public.tableau.com/views/YOUR_WORKBOOK_NAME/YOUR_VIEW_NAME



---

## Notebook — What’s inside

Open `Notebooks/NYC_311_EDA.ipynb` (or view a copy on Kaggle) to see:

1. Data ingestion and inspection  
2. Date parsing & validation (Created Date, Closed Date)  
3. `Response Time (Days)` calculation and filtering invalid values  
4. Aggregations: complaints by borough, top complaint types, monthly trends  
5. Visualizations (Matplotlib/Seaborn) used for quick EDA and annotation  
6. CSV export used as input for Tableau

**Kaggle notebook :** '(https://www.kaggle.com/code/jamesmcentee/sql-python-tableau/edit)`

---

## How to run the notebook locally (recommended)

1. Clone the repo:

```bash
git clone https://github.com/<your-username>/NYC_311_Service_Requests_2009.git
cd NYC_311_Service_Requests_2009/Notebooks



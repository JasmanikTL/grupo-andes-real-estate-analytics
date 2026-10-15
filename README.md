# Grupo Andes Inmobiliario | Real Estate Business Analytics

**Power BI · DAX · Data Modeling · Commercial KPIs · Cohort Analysis**

## Overview
Business analytics case study of real-estate sales in **2023–2024**. The project focuses on understanding revenue, transaction volume, commissions, property types, customer segments, sales channels, and repeat purchasing patterns.

## Business questions
- Which property types, cities, and channels contribute the most revenue?
- How do revenue and sales change over time?
- How does performance differ across customer segments?
- Do customers make subsequent purchases after their first transaction?

## Data and modeling
The original project uses three tables: `hecho_ventas_propiedades` (sales fact table), `dim_propiedades` (property dimension), and `dim_clientes` (customer dimension). A date dimension (`dim_fecha`) is part of the documented Power BI workflow.

The supplied CSV files contain **8,500 sales**, **8,000 property records**, and **3,500 customer records**. The CSV files and `.pbix` are **not included in this public repository** pending confirmation of redistribution permissions.

## Analysis and dashboard
The Power BI report was structured around executive performance, commercial breakdowns, and customer cohorts. The project report discusses revenue, average sale value, commissions, year-over-year growth, and segment comparisons.

## Reported findings
The original executive summary reports:

- **$6.01 billion** in revenue from **8,500 sales** during 2023–2024.
- **$200.63 million** in total commissions.
- **11.14%** revenue growth in 2024 compared with 2023.
- Houses as the leading property type by total revenue; apartments as the leading type by transaction count.
- Evidence of repeat purchases in the cohort analysis.

*These figures are reproduced from the author's original executive summary. The notebook is a narrative report, not an executable calculation pipeline; Power BI measure definitions have not been independently verified here. Currency is shown as in the source report; the underlying currency denomination was not specified.*

## Files
- `grupo_andes_case_study.ipynb` — cleaned, readable case-study report, without reviewer feedback or course submission instructions.
- `README.md` — project summary and publication notes.
- `.gitignore` — excludes local datasets, Power BI files, and temporary files.

## Dashboard
[Power BI project link (Google Drive)](https://drive.google.com/file/d/116tdeDGXjhnpKQfRZzWMMcqN7gZgnfXo/view?usp=sharing) — availability and sharing permissions should be verified by the repository owner before promoting this link.

## Reproducibility and limitations
This repository documents a **Power BI-centered** analysis, rather than a Python implementation. The original notebook did not include executable data processing code. To reproduce the dashboard, an authorized copy of the data and Power BI project would be needed. No invented DAX formulas or notebook calculations are supplied.

## Tools
Power BI, DAX, data modeling, business intelligence, cohort analysis.

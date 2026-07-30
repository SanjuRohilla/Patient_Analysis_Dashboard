# 🏥 Patient Analysis Dashboard | Power BI

An end-to-end healthcare analytics dashboard built in Power BI to analyze patient admissions, demographics, and hospital revenue trends. Designed to help hospital administrators make data-driven decisions around resource allocation, department staffing, and patient care planning.

![Dashboard Preview](Screenshot%202026-07-31%20014634.png)

### 🎥 Live Demo

![Dashboard Demo](patientDashboardemo.gif)

## 📌 Overview

This project covers the complete BI workflow — from raw data import and cleaning to a fully interactive, business-ready dashboard. Data was cleaned and transformed using Power Query, relationships were modeled across multiple tables, and key metrics were calculated using DAX measures. The final report includes dynamic slicers for Department, City, and Month, allowing users to drill down into specific segments in real time.

## 📊 Key Metrics

| Metric | Value |
|---|---|
| Total Patients | 1,000 |
| Average Stay Duration | 8.30 Days |
| Average Bill | ₹75.24K |
| Total Revenue | ₹75.24M |

## 🔍 Dashboard Features

- **KPI Cards** — Total Patients, Average Stay Duration, Average Bill, Total Revenue
- **Monthly Patient Trends** — Line chart tracking admissions across the year
- **Department-Wise Patient Analysis** — Bar chart comparing patient load across 8 departments
- **Gender Distribution** — Donut chart (Male 51.4% / Female 48.6%)
- **Insurance Status** — Donut chart tracking insured vs. uninsured patients
- **Admission Type Analysis** — Emergency vs. Referral vs. Elective breakdown
- **Age Group Distribution** — Bar chart segmented across 5 age bands
- **City-Wise Patient Analysis** — Interactive map visual across patient locations
- **Top Disease Analysis** — Ranked bar chart of most frequently diagnosed conditions
- **Cross-Filtering Slicers** — Department, City, and Month filters applied across all visuals

## 🛠️ Tools & Techniques

`Power BI` · `Power Query` · `DAX` · `Data Modeling` · `Data Cleaning & Transformation` · `Interactive Slicers & Cross-Filtering` · `Map Visualization` · `Dashboard Design`

## 💡 Business Insights

- **Pulmonology (226) and General Medicine (204) patients together account for ~43% of total patient volume** — signals where staffing and bed capacity should be prioritized.
- **Patient admissions dropped sharply after June** (from ~120/month in H1 to a steady ~54/month in H2), suggesting a strong seasonal pattern worth investigating for resource planning.
- **65+ age group is the largest patient segment (277 patients)**, followed by 0–18 (208) — indicating the hospital serves a dual population of elderly and pediatric care, which may need different care protocols.
- **Nearly half of patients (48.9%) are uninsured**, highlighting a significant revenue risk area and a potential target for insurance outreach programs.
- **Migraine, Asthma, and Pneumonia are the top 3 diagnosed conditions**, useful for preventive care and medicine stock planning.

## 📂 Project Files

- `Patient_Analysis_Dashboard.pbix` — Full Power BI report file
- `Screenshot 2026-07-31 014634.png` — Dashboard preview
- `patientDashboardemo.gif` — Interactive demo walkthrough

## ▶️ How to View

1. Download `Patient_Analysis_Dashboard.pbix`
2. Open in [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads) (free)
3. Use the Department, City, and Month slicers to explore the data interactively

---

⭐ If you found this project useful, feel free to star the repo!

## 📌 Business Overview
This project analyzes Netflix’s global library of over 8,000 titles to identify content acquisition trends and regional distribution gaps.  

It aims to provide stakeholders with actionable insights into catalog diversity, content strategy, and audience reach across regions.

---

## 🚀 Key Features & UX

This dashboard is designed with an **interactive, app-like experience** for seamless exploration:

- **Executive KPIs:**  
  Real-time tracking of Total Titles, Directors, and Content Ratings.

- **Advanced Navigation:**  
  Integrated button-based navigation for smooth movement between report pages.

- **Deep-Dive Analytics:**  
  Drill-through pages and report tooltips enable granular exploration without cluttering the main dashboard.

---

## 🛠️ Technical Stack & Architecture

### 1. Data Modeling (Snowflake/Star Schema)
Developed a **Snowflake Schema** to efficiently manage complex relationships between:
- Content titles
- Genres
- Creators (directors/actors)
- Regional metadata

This ensures scalability and optimized query performance.

---

### 2. DAX Implementation

- **Time Intelligence:**  
  Built YoY growth metrics and rolling averages for trend analysis.

- **Dynamic Logic:**  
  Used `SWITCH(TRUE())` for classification models like BCG Matrix and content segmentation.

- **What-If Parameters:**  
  Enabled dynamic scenario simulation for business forecasting.

---

## 🧪 Data Pipeline

- **SQL:**  
  Used for data extraction, cleaning, and CTE-based transformations.

- **Power Query (M Language):**  
  Applied for data shaping, normalization, and preprocessing before modeling.

---

## 📊 Dashboard Preview

| Page                 |          Primary Insight                  |
|----------------------|-----------------------------------------|
| **Main Dashboard** | Global KPI overview and content trends |
| **Geographic Analysis** | Country-wise content distribution |
| **Catalog Diversity** | Genre and rating breakdown |

## 🎓 Credentials & Inspiration
This project is inspired by best practices from:

- Microsoft **PL-300: Power BI Data Analyst Certification**
- University of Washington **Data Analytics & Visualization Principles**

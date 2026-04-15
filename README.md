# Sales Performance Dashboard - Power BI

> An end-to-end Power BI project analyzing gross profit performance across countries, product types, and time periods (2023–2025), with dynamic visuals, DAX measures, and professional formatting.

---
## 📂 Project File: [Sales Performance Report](https://github.com/Shihab412/Sales_Performance_Dashboard-Power_BI/tree/main/Project%20File)

---
## 📊 Dashboard Preview

<img width="994" height="557" alt="Performance Dashboard" src="https://github.com/user-attachments/assets/ba5df413-9c99-4674-afe7-35e538b339cb" />


---

## 🗂️ Project Overview

This project builds a fully interactive Power BI report for a fictional plant company ("Plant Co."), tracking gross profit KPIs across multiple dimensions. The focus is on deriving actionable insight from year-over-year comparisons — identifying underperforming countries, monitoring monthly trends, and segmenting accounts by profitability.

| Property | Details |
|---|---|
| **Tool** | Power BI Desktop |
| **Data Period** | 2023, 2024, 2025 |
| **Primary Metric** | Gross Profit (YTD vs PYTD) |
| **Secondary Metrics** | Quantity, Sales, GP% |
| **Visualization Types** | Treemap, Waterfall, Combo Chart, Scatter Chart |

---

## 🛠️ Technical Skills Demonstrated

### Data Preparation
- **Power Query** — data cleaning, transformation, and shaping before model load
- **Virtual Tables** — used within DAX to create in-memory calculation tables without persisting to the model

### Data Modeling & DAX
- Designed a clean star schema model
- Built reusable **core measures**: YTD, PYTD, YTD vs PYTD, GP%
- Used `CALCULATE`, `SAMEPERIODLASTYEAR`, `SWITCH`, `SELECTEDVALUE` and other DAX functions
- Dynamic metric switching via a disconnected slicer (Gross Profit / Quantity / Sales)

### Visualizations
| Visual | Purpose |
|---|---|
| **Treemap** | Bottom 10 countries by YTD vs PYTD |
| **Waterfall Chart** | Monthly gross profit change breakdown |
| **Combo Chart** | YTD & PYTD monthly comparison with product type stacking |
| **Scatter Chart + Zoom Slider** | Account profitability segmentation by GP% and Value YTD |

### Formatting & UX
- **Conditional formatting** on KPI cards (red highlight for negative YTD vs PYTD)
- **Dynamic chart titles** that update based on slicer selection
- **Dynamic report title** reflecting the selected year
- Consistent color theme and axis label cleanup throughout

---

## Author

**Sahadat Ullah Mollah**  
Data Analytics Portfolio Project  
[LinkedIn](www.linkedin.com/in/sahadat-ullah)

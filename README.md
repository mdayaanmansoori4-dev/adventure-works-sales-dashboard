# 📊 Adventure Works Sales Analysis Dashboard (Excel)

An interactive Excel dashboard analyzing sales, profitability, and transaction trends for **Adventure Works**, built using PivotTables, slicers, and dynamic formulas to surface time-based, geographic, and seasonal drivers of revenue and profit — all without leaving Excel.

![Dashboard Preview](<img width="1361" height="768" alt="Dashboard_Preview" src="https://github.com/user-attachments/assets/54446b91-566d-4a76-a642-7e6ecf00ae71" />
)

---

## 🎯 Overview

This dashboard turns raw Adventure Works sales data into a single, interactive Excel workbook — combining KPI tracking, time-series trends, and weekday/quarterly breakdowns so stakeholders can quickly see **what's driving revenue and where margin is being made or lost**, using nothing but native Excel tools.

**Key metrics at a glance:**

| Metric | Value |
|---|---|
| Total Revenue | $307.09 M |
| Total Profit | $126.29 M |
| Total COGS | $180.80 M |
| Profit Margin | 41.1% |
| Total Quantity Sold | 631.92 K |
| Total Transactions | 60.40 K |

---

## ✨ Features

- **KPI Summary Cards** — Revenue, profit, COGS, margin, quantity, and transaction volume, built from PivotTable/formula-driven cells styled as custom cards (not default Excel chart elements).
- **Dynamic Measure Switcher** — Option buttons (Revenue / Profit / Transaction) linked to a cell that drives a single chart via `CHOOSE`/`SWITCH` formulas, so one visual can display three different metrics.
- **Slicers & Timelines** — Interactive slicers for year, month, weekday, and quarter, connected across multiple PivotTables/PivotCharts for synchronized filtering.
- **Dynamic Callout Text** — Formula-driven summary text (e.g., *"Collectively accounted for 31.9%"*) that updates automatically based on slicer selection.
- **Weekday vs. Weekend Split** — Donut chart showing weekdays account for 72% of total profit.
- **Quarterly Profit Breakdown** — Color-coded KPI cards with percentage-of-total contribution per quarter.
- **Geographic Filter** — Country-level slicer (Australia, Canada, France, Germany, UK, US).
- **Custom Visual Design** — Cohesive black/cyan/grey theme built with formatted cells, shapes, and icons in place of default Excel chart styling, for a Power BI–style look inside Excel.

---

## 🔍 Key Insights

- Weekdays (Mon–Fri) drive **72%** of total profit, with **Wednesday–Friday** the strongest days ($18M+ each).
- **Q2** is the strongest quarter (31% of profit / $39.02M), while **Q3** dips to 19% ($24.19M).
- In 2005, **May, June, and December** together accounted for **31.9%** of that year's revenue.
- Highlighted weekdays alone contributed **43.8%** of total profit within the weekly view.

---

## 🛠️ Tech Stack

- **Microsoft Excel** — dashboard layout, formatting, and design
- **PivotTables & PivotCharts** — underlying data aggregation and charting
- **Power Query** — data import, cleaning, and transformation
- **Slicers & Timelines** — cross-filtering interactivity
- **Excel Formulas** — `SWITCH`/`CHOOSE`, `SUMIFS`, `GETPIVOTDATA`, dynamic text concatenation for callouts
- **Form Controls** — option buttons/checkboxes for the measure switcher
- *(If used)* **VBA Macros** — for additional interactivity or refresh automation

> Update the stack list above to match exactly what you used (e.g., remove VBA if you didn't use macros).

---

## 📂 Repository Contents

```
├── AdventureWorks_SalesAnalysis.xlsx   
├── dashboard-preview.png              
├── data/                               
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `AdventureWorks_SalesAnalysis.xlsx` in **Microsoft Excel** (2016 or later recommended for full slicer/PivotChart support).
3. If prompted, enable content/macros and refresh the data connection (Data → Refresh All) to load the source data.
4. Use the slicers, timeline, and option buttons to interactively explore revenue, profit, and transactions by year, quarter, month, weekday, and country.

---

## 📬 Contact

If you have questions or feedback about this project, feel free to reach out via [LinkedIn](www.linkedin.com/in/aayan-mansoori-a47a03362) or open an issue in this repository.

---

*Built with Microsoft Excel • Adventure Works dataset*

**Md Aayan**

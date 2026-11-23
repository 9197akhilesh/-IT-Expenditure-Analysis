# -IT-Expenditure-Analysis
Developed an interactive Power BI dashboard to analyze IT expenditure across business units, regions, and cost categories. Compared actual, forecast, and planned spending to identify budget variances, overspending, and cost-saving opportunities, enabling data-driven financial decisions.
from pathlib import Path

readme = """# 💻 IT Expenditure Analysis | Power BI

> **Turning IT spending data into clearer financial decisions.**

An interactive Power BI report designed to explore IT expenditure across business areas, regions, IT areas, and cost elements. It brings together budget performance, variance analysis, cost drivers, and spending trends to help stakeholders understand where IT budgets are being used and where closer attention may be needed.

## 🎯 Project Objectives

- Review IT expenditure across business units, regions, and cost categories.
- Compare actual, forecast, and planned spend.
- Identify budget variances and areas that may require investigation.
- Explore key cost drivers, including labor and other IT expenditure areas.
- Support more informed budgeting, cost monitoring, and resource-allocation decisions.

## 📊 Report Pages

The PBIX report includes 12 pages, each offering a different view of IT expenditure:

| Page | What it explores |
|---|---|
| **Summary** | High-level KPIs and an overview of IT spending distribution and trends. |
| **Variance** | Budget variance analysis using comparison visuals, including a waterfall chart. |
| **Drivers** | Cost drivers and their movement across the selected reporting context. |
| **Outlook** | Forward-looking expenditure view and supporting breakdowns. |
| **YTD** | Year-to-date performance, KPIs, and trend comparisons. |
| **Regions** | Regional expenditure patterns and comparisons. |
| **Labor** | Labor-related cost composition and trends. |
| **IT Areas** | Spend distribution and comparison across IT areas. |
| **Trends** | Time-based expenditure patterns and changes. |
| **Elements** | Cost-element breakdowns and comparisons. |
| **Business** | Business-area expenditure composition and analysis. |
| **Insights** | A dedicated page for presenting key observations. |

## ✨ Dashboard Features

- Interactive slicers for filtering report views.
- KPI cards for quick performance checks.
- Actual, forecast, and plan comparisons.
- Trend, variance, and category-level visual analysis.
- Drill-down style exploration across regions, business areas, IT areas, labor, and cost elements.
- Multiple visual types, including bar and column charts, line charts, combo charts, treemaps, donut charts, waterfall charts, tables, and scatter charts.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — report development and visualization.
- **Power Query** — data loading and transformation within Power BI.
- **DAX** — measures and analytical calculations, where implemented in the report.

## 🔍 Business Value

The report is intended to make IT expenditure easier to monitor and explain. By bringing multiple views of spend into one interactive report, stakeholders can investigate budget differences, understand cost concentration, compare performance across organizational areas, and identify topics for financial review.

## ▶️ How to View

1. Download the `.pbix` project file from this repository.
2. Open it using **Microsoft Power BI Desktop**.
3. Use the slicers and page navigation to explore the report.
4. Select relevant regions, business areas, or reporting periods to focus the analysis.

## 📌 Notes

This repository contains the Power BI report file. The exact source-system details, refresh configuration, and business definitions should be confirmed from the underlying dataset and report model before operational use. Interpret variances in the context of the organization's approved budget definitions and reporting calendar.

---

### 👤 Author

**Akhilesh Mishra**


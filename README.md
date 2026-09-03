# Super Store Sales Dashboard — Power BI Capstone

An interactive, two-page Power BI dashboard analyzing ~5,900 Super Store retail
transactions across regions, customer segments, categories, and shipping modes.

## Overview

- **Page 1 — Sales Overview:** KPI cards (Sales, Quantity, Profit), segment &
  payment-mode donut charts, monthly sales/profit trend lines (2019 vs 2020
  year-over-year), geographic sales map (Bing Maps), and category/sub-category/
  ship-mode bar charts.
- **Page 2 — Regional & Profitability Analysis:** Region slicer, Region × Category
  sales matrix, monthly profit variance waterfall, sales-vs-profit scatter plot by
  sub-category, and a conditionally formatted detailed transaction table (loss-making
  rows highlighted in red).

Covers all 10 core Power BI visual types: KPI cards, line, bar, donut, table, matrix,
scatter, map, waterfall, and slicer.

## Key Insights

- Total sales of **$1.57M** across **22K units**, yielding **$175.26K** profit.
- **Office Supplies** is the top revenue category ($0.64M), ahead of Technology
  ($0.47M) and Furniture ($0.45M).
- **Consumer** segment drives 48% of total sales — the primary target group.
- **West region** leads all regions at **$5.22M** in total sales (Region × Category matrix).
- Profit grew consistently through 2020 vs. 2019, peaking in Q4 (Oct–Dec).
- **Furniture** shows recurring losses in the monthly profit-variance waterfall.

## Tech Stack

| Technology | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation, data modeling, all visualizations |
| Power Query (M) | Data transformation and type-fixing inside Power BI |
| DAX | KPI measures, calculated fields, aggregations |
| Python (pandas) | Data cleaning and preprocessing before import |
| Bing Maps (integrated) | Geographic visualization of global sales distribution |

## Files

- `SuperStore_Sales_Dashboard.pbix` — the Power BI Desktop file (open in Power BI Desktop to explore interactively)
- `data/SuperStore_Sales_Dataset.csv` — source dataset (~5,900 transaction rows)
- `report/SuperStoreSales_Report.pdf` — full capstone write-up: problem statement,
  objectives, solution walkthrough, dashboard screenshots, and key findings

## Data Source

Super Store Sales dataset (Kaggle).

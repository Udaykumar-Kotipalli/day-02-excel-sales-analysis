# Day 02 — Excel Sales Analysis Dashboard

## Goal
Clean a fictional retail sales dataset, calculate performance KPIs, and build a formula-driven Excel dashboard.

## Files
- `day-02-excel-sales-analysis.xlsx` — workbook with Dashboard, Raw Data, Cleaned Data, Summary, and Analysis sheets.
- `data/sales_raw.csv` — 500-row raw dataset export.

## Workbook guide
1. **Raw Data:** original data with intentionally introduced quality issues.
2. **Cleaned Data:** standardized text, duplicate IDs and non-positive quantities removed, missing price filled from product reference, and sales recalculated.
3. **Summary:** KPI formulas for orders, units, gross sales, discounts, net sales, and average order value.
4. **Analysis:** summaries by category, region, and month.
5. **Dashboard:** KPI cards and charts.

## Your task
- Identify the top category and region.
- Find the strongest and weakest months.
- Compare gross sales, discounts, and net sales.
- Write three recommendations supported by the workbook.
- Explain the cleaning decisions and their limitations.

## Data-quality decisions
Duplicate order IDs and non-positive quantities are removed. Text fields are standardized. The missing unit price is filled using the product reference price. Sales values are recalculated. Missing region is labeled `Unknown`.

**Important:** This is synthetic practice data, not real company data. Some formulas and charts recalculate when opened in Excel or LibreOffice.

## GitHub repo name
`day-02-excel-sales-analysis`

## Skills
Excel data cleaning, formulas, COUNTIF/SUMIF/SUMIFS, KPI reporting, charting, dashboard design, business interpretation.

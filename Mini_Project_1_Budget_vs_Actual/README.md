# Mini Project 1 &mdash; Budget vs Actual Tracker (Excel)

## Overview
This mini project demonstrates **core data analysis skills in Excel**, including structured data modeling, aggregation with PivotTables, KPI calculation, and variance analysis. The workbook is designed to support **monitoring performance against a reference baseline** and identifying areas that warrant further investigation.

All data is simulated.

While the example uses a financial context, the analytical patterns are applicable to any domain involving **planned vs observed outcomes** (e.g., operations, program evaluation, usage metrics).

---

## Analytical Question
How does observed performance compare to an expected baseline across categories and time, and where do meaningful deviations occur?

---

## What This Project Demonstrates
- Structuring raw data into analysis-ready tables
- Aggregating metrics using PivotTables
- Calculating and interpreting variances
- Designing summary views for rapid insight
- Separating inputs, data, and reporting layers

---

## Workbook Structure
- **Inputs**: Centralized reporting controls (e.g., last closed month) used to standardize analysis views across summaries and PivotTables. *No forecasting logic is applied.*
- **Fact_Finance_Long**: Clean, long-format fact table containing simulated baseline and observed values, structured for aggregation and BI-style analysis.
- **Ref_Department**: Categorical dimension used for grouping and roll-ups (included for data-model realism).
- **Ref_GLAccount**: Category mapping supporting grouped variance analysis.
- **Ref_Date**: Calendar dimension supporting time-based aggregation and filtering.
- **Dashboard_Summaries**: High-level KPI view with calculated variances and conditional formatting to highlight outliers.
- **Pivot_Instructions**: Documentation explaining how summary views are derived from the fact table.
- **Pivots**: PivotTables summarizing baseline vs observed performance across dimensions.

---

## Key Excel Skills Used
- PivotTables and aggregations
- KPI and variance calculation
- Data modeling concepts (fact + dimensions)
- Conditional formatting for insight discovery
- Clear documentation of analytical steps
- Excel lookup logic (`INDEX` / `MATCH`)

---

## Notes
- All data is simulated
- The focus is on **analysis and interpretation**, not automation
- The workbook prioritizes clarity and explainability
- Category attributes are joined to the fact table using Excel lookup logic (`INDEX` / `MATCH`) to demonstrate relational data preparation.

---

## How This Would Be Used
This pattern supports recurring reporting, performance monitoring, and exploratory analysis in data analyst roles where structured summaries are needed to guide decision-making.
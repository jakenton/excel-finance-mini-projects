# Mini Project 2 &mdash; Rolling Forecast Logic (Excel)

## Overview
This mini project demonstrates **conditional logic and time-aware analysis** in Excel. The workbook uses IF-based logic to dynamically switch between observed data for completed periods and estimaged values for future periods.

The emphasis is on **correct analytical behavior over time**, not predictive modeling.

All data is simulated.

---

## Analytical Question
How can time-based metrics update dynamically as new data becomes available, while preserving historical values?

---

## What This Project Demonstrates
- Conditional logic driven by time context
- Separation of observed vs estimated data
- Input-driven recalculation of metrics
- Clear presentation of evolving metrics

---

## Workbook Structure
- **Inputs**: User-controlled parameters including the last completed period and a simple growth assumption.
- **Forecast_Table**: Core calculation table using IF logic to
    - Lock observed values for completed periods
    - Apply assumptions only to future periods
- **KPI_Summary**: High-level rollups summarizing cumulative observed values and projected totals.

---

## Key Data Analyst Skills Used
- IF-based conditional logic
- Time-aware metric calculation
- Controlled used of assumptions
- Clear visualization of trends over time

---

## Visualization Notes
Observed and estimated values intentionally overlap for completed periods. This reflects correct time-aware logic and is visually differentiated rather than separated into distinct calculations.

---

## Notes
- This is a logic-focused example, not a forecasting system
- Assumptions are intentionally simple to emphasize reasoning
- All data is simulated

---

## How This Would Be Used
This approach mirrors how analysts maintain rolling metrics, cumulative KPIs, or projections that update as new data is ingested.
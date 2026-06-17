Greenhouse Production Performance Analysis

End-to-end production analytics project covering data cleaning, trend analysis, labour scenario planning, and dashboard design, built entirely in Excel and Power Query.

Business Context

A flower-growing operation manages multiple varieties across several greenhouse locations, each running a 15-week production cycle. Leadership needed a clearer picture of how actual production was tracking against forecasts, whether current staffing plans were realistic, and what KPIs should be monitored going forward.

What I Did

1. Data Cleaning & Preparation Cleaned a 2,100+ row weekly production dataset, standardising inconsistent variety and location naming, investigating and documenting missing values, and uncovering a significant data integrity issue where daily production records and weekly totals failed to reconcile for over 99% of rows. Rather than silently fixing this, I flagged it, investigated the root cause, and made a documented decision on which figure to treat as authoritative going forward.
2. Trend Analysis Compared actual vs. estimated production coefficients across 16 varieties and found an overall estimation accuracy rate of just 60% ,meaning actual yield consistently fell well short of forecasts. Mapped how performance changes across the 15-week production cycle, identifying a consistent early dip and a long decline in later weeks.
3. Scenario-Based Labour Planning Modelled 2026 harvester requirements under two scenarios; production hitting forecast vs. production following the historical 60% accuracy pattern while incorporating a 6% sick factor. Found the business would need roughly 64% more harvesters than planned if historical performance patterns continue, with Week 50 as peak demand.
4. Interactive Performance Dashboard Built a single-page Excel dashboard with KPI summary cards, top/bottom 10 variety performance, coefficient performance by location, harvester speed & quality trends, and absenteeism tracking.

   
Key Insight

The most valuable finding wasn't a chart — it was a data quality issue. Investigating why two production figures didn't match revealed they came from entirely separate, unreconciled recording systems, a finding with real operational implications that a purely mechanical "clean and move on" approach would have missed entirely.

Tools Used

Excel · Power Query · PivotTables & PivotCharts · Data Cleaning · Business Context Framing


The underlying dataset was adapted from a structured take-home exercise; all analysis, data quality investigation, and dashboard design represent my own independent work.


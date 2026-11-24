# VoltRelay — Battery-Swapping Network Analytics

## Project Overview

A data analytics project completed as part of the **Gradient Learnings Data Analytics Hackathon (November 2026)**.

The project analyzes approximately **3.87 million battery-swapping events** across six Indian cities to investigate network performance, identify operational bottlenecks, understand failure patterns, and develop data-driven business recommendations.

## Business Problem

VoltRelay operates a battery-swapping network. Operational failures, battery availability issues, long waiting times, and underperforming charging stations can affect customer experience and network reliability.

The objective was to identify where and why operational problems occur and recommend improvements.

## Dataset

The dataset contains approximately 3.87 million swap events from January 2024 to June 2025 across:

- Bengaluru
- Delhi NCR
- Hyderabad
- Pune
- Mumbai
- Jaipur

Additional datasets covered stations, batteries, riders, support tickets, fleet partners, station-hourly status, and city-level daily context.

## Tools & Technologies

- Python — data processing and analysis
- SQL — querying and analytical investigation
- DuckDB — large-scale data analysis
- Google Colab — notebook development
- Power BI — data visualization and reporting

## Key Findings

1. **Network reliability:** Overall non-completion rate was approximately 5.96%, representing 231,204 unsuccessful or abandoned events.
2. **City-level performance:** Delhi NCR recorded a 7.35% non-completion rate, while Jaipur had the highest failure rate among the six cities.
3. **Charger generation:** Gen1 chargers showed a higher non-completion rate (approximately 7.23%) compared with Gen2 and Gen3 (approximately 4.84% each).
4. **Charging performance:** Gen1 chargers had longer average charging times and higher battery-failure rates than newer generations.
5. **Station-level investigation:** Several underperforming stations contributed disproportionately to unsuccessful swaps.
6. **Monthly patterns:** Failure rates increased during certain periods, with May 2025 recording a 9.91% non-completion rate.

## Business Recommendations

- Prioritize maintenance and performance audits at stations with high failure volumes and rates.
- Investigate and upgrade underperforming Gen1 charging infrastructure.
- Improve battery availability and charging operations.
- Monitor waiting times and investigate stations with elevated abandonment.
- Introduce city-wise and station-wise performance monitoring dashboards.
- Track monthly operational KPIs to identify deterioration early.

## Project Files

- `notebook/` — Google Colab analysis notebook
- `report/` — Final analytical report
- `presentation/` — Hackathon presentation
- `data/` — Dataset documentation and access information
- `certificate/` — Participation certificate

## Methodology

The analysis involved data inspection, cleaning, exploratory data analysis, SQL-based aggregation, city and station comparisons, charger-generation analysis, trend investigation, and business recommendation development.

## Hackathon

**Event:** Gradient Learnings Data Analytics Hackathon  
**Project:** VoltRelay Battery-Swapping Network Analytics  
**Participation:** Certificate of Participation  
**Date:** November 2026

## Disclaimer

This project was completed for an educational hackathon using the provided dataset. Findings describe observed associations and patterns and should not automatically be interpreted as proof of causation.

# Strategic Plan Performance Tracker

An interactive dashboard for following up a strategic plan: KPI scorecard, initiative progress, risk register and year-end scenarios. It is built for a sample cultural authority.

**All figures are illustrative sample data for a fictional organisation.** They are not real figures from any government entity.

## What it shows
- 12 KPIs across 4 strategic pillars, each with a baseline, a target, a peer benchmark and a traffic-light status
- Year-end projections under pessimistic, base and optimistic scenarios
- Corrective actions generated for every KPI projected off track and every initiative more than 15 points behind plan
- Progress of 10 strategic initiatives against plan, with owners and budgets
- A likelihood × impact risk heatmap, with fallback plans linked to each initiative

## Method
- **Achievement** = projected Q4 ÷ target, or target ÷ projected Q4 when lower is better, capped at 120%.
- **Projection** = Q3 value + the average quarterly change from Q1 to Q3, scaled by scenario (× 0.4, × 1.0, × 1.5).
- **Status**: on track ≥ 98%, at risk 90–98%, off track < 90%.

## Run it
Open `index.html` in any browser. It needs no install or server, and runs on plain HTML, CSS and JavaScript.

Author: Mohammad Sharvan Kamil Karaya

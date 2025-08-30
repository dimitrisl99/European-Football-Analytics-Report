# European Football Analytics — A Power BI Report

![alt text](<League Overview VOL 1 .png>)

## Introduction

This project explores **European football** using the European Soccer Database (Kaggle, SQLite) to build a business-ready analytics report in Power BI. The aim is to turn raw match records into clear insights that **answer practical questions** for analysts, coaches, and scouts: *What does each league look like? How is a team really performing? How do leagues compare? What can we expect against a specific opponent?*

## Skills Showcased 

- **🛠️ Data Transformation (ETL) with Power Query:** Cleaned and shaped raw data, handled blanks/types, merged sources, and created derived fields.
- **🧩 Data Modeling:** Designed star-schema models, defined relationships/cardinalities, used role-playing dimensions, and set “Sort by” keys.
- **🧮 DAX & Analytical Measures:** Built business KPIs, applied filter context with CALCULATE, created safe ratios with DIVIDE, and standardized number/percent formats.
- **📊 Core Charts:** Used column/bar, line/area, 100% stacked, scatter, and small multiples to compare entities and trends over time.
- **🏷️ KPI Cards & Tables:** Surfaced key indicators with Cards and delivered sortable detail via Tables with conditional formatting.
- **🗺️ Geospatial Analysis:** Leveraged map visual to show geographic distribution and intensity.
- **🎨 Dashboard Design:** Crafted clear layouts, consistent theming/typography, accessible color choices, and readable labels.
- **🎛️ Interactive Reporting:** Implemented slicers, edit interactions, synchronised filters across pages, and added reset/UX controls.
- **✅ Quality & Validation:** Profiled datasets, ran sanity checks (totals vs percentages), and ensured cross-visual consistency.
- **📝 Documentation & Storytelling:** Wrote problem statements, page rationales, and executive summaries; exported clean artifacts (PDF/screens).

### Page 1 : League Overview 

![alt text](<League Overview VOL 1 .png>)

This is your mission control for any league. **Slicers** (Country/League/Season) drive four core **KPIs** (Matches, Avg Goals/Match, Home & Away Win %) plus a season-by-season scoring **trend** and a ranked team **table** (PPG, Win %, GD). Use it to understand a league’s style and competitiveness in seconds.

### Page 2 : Team Performance 

![alt text](<Team Performance VOL 1 .png>)

A focused deep-dive for a single team. **Headline KPIs** (PPG, Win %, GF/GA/GD) sit alongside a Home vs Away comparison, a seasonal **trend line**, and a clean match list (date, opponent, score, outcome, points). Ideal for diagnosing form and strengths/weaknesses.

### Page 3A : League Comparison - Overview 

![alt text](<League Comparison VOL 1 .png>)

Benchmark leagues across countries. See the **W/D/L outcome mix (100% stacked)**, a ranking of Avg Goals per Match, a **scatter** of Scoring vs Home Advantage (bubble size = matches), and a country map. Great for spotting high-scoring leagues and where home edge is strongest.

### Page 3B : League Comparison - Trends 

![alt text](<League Comparison VOL 2.png>)

Small-multiples **lines** show how leagues evolve by season (uniform axes, average line per panel). Quickly see stability vs change in scoring (or win rate) across time and compare patterns side-by-side.

### Page 4 : Head-to-Head 

![alt text](<Head To HeaD.png>)

One team vs one opponent, all in one place. KPIs (PPG, Win %, GF/GA/GD, Matches), a Home vs Away H2H **chart**, a **result-mix bar** (Win/Draw/Loss %), and a **match table** provide the full context for preparation and realistic expectations.

### Conclusion 

This project turns the European Soccer Database into a clear, business-ready analytics report in Power BI. By shaping a single long fact table and a compact star schema, we produced consistent KPIs and reusable measures that power four focused pages—league overview, team performance, cross-league comparison, and head-to-head analysis.
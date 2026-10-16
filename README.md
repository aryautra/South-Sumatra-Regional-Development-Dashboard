<!-- Repo settings
About: Interactive dashboard of poverty, jobs, HDI, inequality and GRDP across South Sumatra's 17 regencies and cities (2015-2025), built from BPS data.
Topics: data-visualization, dashboard, economics, regional-development, indonesia, bps, data-analysis, javascript, html, svg
Tip: rename SouthSumatra_Dashboard.html to index.html and enable GitHub Pages to get a live demo link.
-->

# South Sumatra Economic Dashboard

Interactive regional monitoring of **17 regencies and cities** in South Sumatra, **2015-2025**, using official BPS statistics.

**Live demo:** `https://aryautra.github.io/South-Sumatra-Regional-Development-Dashboard/`

## What it does
- **Region vs region:** compare any two areas, with the province as a reference line.
- **Zoom and highlight:** choose a year range (animated zoom) and mark a year to read exact values on the chart.
- **Area report card:** rank among 17 areas, change since 2015, above or below the province.
- **Auto key findings:** plain-language findings that update with the indicator and year.
- **Summary cards** for the province or any single area, plus a ranking chart of all 17 areas.

## Why it is useful
- Turns scattered BPS tables into one view a planner or analyst can read in minutes.
- Fully traceable: every indicator records its BPS source table and release.
- Transparent method: province GRDP is computed as the sum of the 17 areas, and unusual values are flagged for checking.
- One self-contained HTML file: no install, no dependencies, works offline, adapts to light and dark mode.

## Key findings
- Poverty fell from 14.25% to 10.15% (2015-2025), and it fell in all 17 areas.
- Output is concentrated: Palembang produces 31% of provincial GRDP and the top three areas 62% (2025).
- Unemployment is highest in cities: Palembang 6.81% vs 3.69% for the province.
- Output rank is not human-development rank: Muara Enim and Musi Banyuasin rank 2nd and 3rd in GRDP but 7th and 10th in HDI.
- Relationships (correlation across 17 areas and 11 years): HDI and poverty move in opposite directions (r = -0.43) and GRDP rises with HDI (r = +0.37). Growth, unemployment and Gini show no clear link with poverty, and HDI rises with unemployment (r = +0.47), the opposite of simple theory. Correlation is not causation.

## Presentation
`SouthSumatra_Dashboard_Deck.pptx` summarizes the dashboard, the problems it reveals and the relationships between indicators.

## Data
Poverty rate and number of poor people, open unemployment rate (TPT), Human Development Index (IPM), Gini ratio, GRDP at current prices, and per-capita GRDP growth (constant 2010 prices, area level only). Source: BPS Provinsi Sumatera Selatan. Verify figures against BPS before reusing them.

## Run it
Open index.html in any browser. To update the data, replace the embedded `DATA` object in the file.

## Skills demonstrated
Data collection and cleaning, regional development analysis, interactive dashboard design, AI-assisted building with human verification.

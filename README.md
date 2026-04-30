# 🔭 TALENTscope

**Vertex Talent Intelligence Platform** — an interactive labor market dashboard covering US & Canada.

Built with D3.js, Chart.js, and real market data from Draup (June 2022 refresh), paired with internal hiring metrics.

## Features

- **Market Map** — interactive North America heat map with city-level talent bubbles, colored by any metric
- **Market Details** — compensation bands, talent pool seniority breakdown, and market health indicators
- **Internal Metrics** — time-to-fill stage funnel, applicant volume, and 1-year retention rates
- **Location Comparison** — side-by-side comparison of all markets for any selected role and metric

## Usage

Open `index.html` in any modern browser. All data is embedded — no server required.

## Data

- Market data: Draup US & Canada refresh, June 2022
- Internal metrics: synthetic data seeded from realistic hiring benchmarks by job family and market

## Tech Stack

- [D3.js](https://d3js.org/) v7 — map rendering
- [Chart.js](https://www.chartjs.org/) v4 — charts
- [TopoJSON](https://github.com/topojson/topojson) — geography
- [Cabin](https://fonts.google.com/specimen/Cabin) — Vertex brand typeface

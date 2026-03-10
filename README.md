# NYC 311 Service Requests Dashboard

Interactive dashboard visualizing NYC 311 service request data, built with **ArcGIS Maps SDK for JavaScript**, **Calcite Design System**, and **Chart.js**.

**[View Live Demo](https://garridolecca.github.io/nyc-311-dashboard/)**

![Dashboard Preview](https://img.shields.io/badge/status-live-brightgreen)

## Features

- **Interactive Map** — 2,500 color-coded data points across all 5 NYC boroughs on a dark basemap
- **Complaint Type Filters** — Toggle categories (Noise, Heat/Hot Water, Street, Water, Blocked Driveway, Illegal Parking)
- **Time Range Selector** — Filter by 7 days, 30 days, 90 days, 1 year, or all data
- **Borough Breakdown** — Ranked list with proportional bars
- **Charts** — Top complaint types (horizontal bar), requests over time (area), status breakdown (doughnut), hourly pattern (bar)
- **Summary Stats** — Total requests, open/closed counts, average resolution time, top complaint type
- **Popups** — Click any point for complaint details (type, borough, status, date, ZIP)

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Map | ArcGIS Maps SDK for JavaScript 4.31 |
| UI | Calcite Design System |
| Charts | Chart.js 4.x |
| Data | 2,500 synthetic records with realistic NYC distributions |

## Getting Started

No build step or API key required. Open `index.html` in a browser or visit the [live demo](https://garridolecca.github.io/nyc-311-dashboard/).

## License

MIT

# Earthquake Impact Dashboard (Indonesia, 2000–2024)

An interactive **Tableau** dashboard and data story about earthquakes in Indonesia and their human and infrastructure impact. It uses historical disaster data from **DIBI** (Data Informasi Bencana Indonesia, Indonesia's national disaster database). Data Visualization course group project.

## What the dashboard shows

The workbook contains a story (`Story 1`) built from nine worksheets:

| Worksheet | Purpose |
|---|---|
| **KPI** | Headline totals: deaths, displaced people, total damage |
| **Number of Earthquake** | Count of recorded earthquake events |
| **Map** | Total damage by province, filterable by year |
| **Total Death** | Fatalities |
| **Total Damage** | Total damaged buildings |
| **Damage Grade** | Damage by severity: heavy, moderate, light |
| **Facility** | Damaged education, worship and public facilities |
| **Top 5** | The five provinces with the highest total damage |
| **Forecast** | Forecast of total damage by year and province |

The dataset has about 790 earthquake records with casualties (dead, missing, injured, displaced), damage grades and damaged facilities per regency/city. A year highlight parameter (`Highlight_Year`) lets the viewer focus on a single year across views.

## Files

```
earthquake-impact-dashboard.twbx   # packaged workbook (includes the DIBI data extract)
```

## How to open

1. Install [Tableau Desktop](https://www.tableau.com/products/desktop) or the free [Tableau Public](https://public.tableau.com/app/discover) desktop app.
2. Open `earthquake-impact-dashboard.twbx`. The data is packaged inside the file, so no extra setup is needed.

## Skills demonstrated

Data storytelling · KPI design · geographic mapping · time-series forecasting in Tableau · dashboard interactivity (parameters, highlights)

## Tech stack

Tableau · Excel

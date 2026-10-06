# SEAT 2.0 visual direction: Signal & Accountability

A second, independent visual direction for the SEAT front-end. It uses a compact workspace navigation, dashboard cards, trend and status charts, institution progress bars, and a citizen experience dashboard with location, indicator, time-of-day and channel visualisations.

## Run

Open `index.html` in a current browser. No package installation or build step is required. To serve locally, run `python3 -m http.server 8000` in this folder and open `http://localhost:8000`.

## Main interactions

- Switch between the overview, Reform Tracker and Citizen Experience dashboards using the side navigation.
- Use overview and tracker KPI cards to pre-filter recommendation statuses.
- Search recommendations, filter by institution or status, and open a recommendation evidence detail panel.
- Change the trend chart time range and inspect chart points.
- Switch the citizen dashboard map between citizen-only and combined citizen/observer marks.
- Change the time chart between report volume and experience index.
- Select map marks to inspect illustrative report counts by state.
- Use the mobile navigation and responsive dashboard layouts.

## Demo data

All recommendation statuses, counts, indicator values, location marks, dates and trend values are illustrative. This prototype has no connection to live Situation Room or SEAT data and stores no citizen submissions. Google Fonts load when network access is available; local sans-serif fonts provide the fallback.

## Project files

- `index.html`: application structure
- `styles.css`: visual system, charts, dashboard layouts and responsive rules
- `app.js`: demo records, dashboard rendering and interactions

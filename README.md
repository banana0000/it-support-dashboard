# IT Support Dashboard

Interactive IT support ticket dashboard built with [Plotly.js](https://plotly.com/javascript/). The data (11,923 tickets, 2024) is embedded in the HTML, so no backend is needed.

- `index.html`: full interactive dashboard (Overview, Locations, Workload pages, filters)
- `static.html`: small static version with the main charts and tables

**Live:** https://it-support-dashboard2.onrender.com/

## Contents

- KPIs: total tickets, high priority share, average tickets per day, average resolution time (days)
- Tickets by queue, priority and type
- Tickets and resolution time by month
- Country table and queue summary

## Run locally

Open `index.html` (or `static.html`) in a browser (Plotly.js is loaded from the `cdn.plot.ly` CDN, so an internet connection is needed).

## Deploy

Hosted as a static site on Render. `render.yaml` holds the blueprint; the publish directory is the repo root (`./`).

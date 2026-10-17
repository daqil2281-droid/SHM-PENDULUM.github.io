# gLab Physics — Pendulum Lab v2.0

A polished Progressive Web App for a pendulum practical.

## Features
- T = t_average / 20
- T² vs l graph and linear regression
- gradient, intercept, R² and g = 4π²/gradient
- Excel (.xlsx/.xls) and CSV import
- CSV and JSON export
- local auto-save
- dark mode
- sample data
- print / Save as PDF
- installable PWA
- service-worker caching for repeat/offline use after first successful load

## Publish
Upload the contents of this folder to a GitHub repository and enable GitHub Pages from the `main` branch and repository root.

## Important
Chart.js and SheetJS are fetched from jsDelivr and cached by the service worker. The first visit needs internet access; after the libraries have been cached, the app can continue to work offline in supported browsers.

# Team 6 — Updated EV Charging Dashboard

This is a static GitHub Pages dashboard based on the updated 1,000-site, 22-column synthetic dataset.

## Publish
1. Open the GitHub repository that currently hosts your dashboard.
2. Upload/replace `index.html` and `data.csv` in the publishing folder (usually repository root). Keep the names exactly as shown.
3. Commit the changes. In **Settings → Pages**, ensure deployment is set to the branch and folder containing `index.html`.
4. Refresh the existing GitHub Pages link after deployment. If you see old data, hard-refresh the browser.

## Local preview
Run `python3 -m http.server 8000` in this folder and visit http://localhost:8000.

Uses Chart.js and Papa Parse from CDNs. No npm or backend required. Actual sessions are only computed for existing sites with recorded values. Filtering updates all KPIs and charts.

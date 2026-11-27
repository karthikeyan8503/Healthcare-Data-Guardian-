# HealthGuard

Multi-disease healthcare data quality and risk screening, running fully in the browser. No backend, no build step.

**Decision support only.** HealthGuard checks data quality and gives rule-based risk indicators. It does not diagnose. Always confirm with a doctor.

## Features
- Data: upload or paste a CSV, or load a synthetic sample (Heart disease, Diabetes, Dengue, Viral fever, Mixed)
- Quality scan: weighted quality score, disease readiness, attribute coverage, findings, and a safe cleaner that never imputes values
- Risk prediction: transparent rule-based scores per disease with the values that drove them
- Report: plain-text report and findings CSV

## Run locally
- Easiest: open `index.html` in a browser.
- VS Code: install the **Live Server** extension, right-click `index.html`, then **Open with Live Server**.
- Or from a terminal in this folder: `python -m http.server 8000` and open http://localhost:8000

## Files
- `index.html` page structure
- `style.css` styling and light/dark themes
- `app.js` disease profiles, quality engine, cleaner, risk rules and pages

Google Fonts load from the internet; without it the app falls back to system fonts.

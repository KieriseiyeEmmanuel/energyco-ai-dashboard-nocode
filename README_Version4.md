# EnergyCo Executive AI Dashboard (No-Code, Appsmith)

## Overview

A ready-to-deploy, no-code dashboard for Chevron, Total, NNPC, and Dangote Refinery. Features AI-powered insights, predictive analytics, anomaly detection, interactive charts, sustainability metrics, and company branding. Built for Appsmith, easily adaptable to Retool or Bubble.

---

## Features

- **Company Selector**: Chevron, Total, NNPC, Dangote logos.
- **KPI Cards**: Oil production, Gas output, Refinery utilization, OPEX, CAPEX, Net profit margin, Market share.
- **AI Assistant Panel**: Natural language Q&A, predictive analytics, auto-summaries, anomaly detection.
- **Visualizations**: Interactive charts, maps, drill-downs.
- **Sustainability Metrics**: CO₂ emissions, renewable share, ESG scores.
- **Modern Design**: Dark mode, glassmorphism, animated transitions, clean typography.
- **Authentication**: Admin, Manager, Analyst roles via plugin.

---

## Quick Start

1. **Import the App Template**
   - Go to your [Appsmith](https://appsmith.com/) instance.
   - Click **Import Application**.
   - Select `appsmith_app_import.json` from this repo.

2. **Upload Data**
   - Use the built-in CSV/XLSX upload or connect Google Sheets/database.
   - Try the included `sample_dataset.csv` for demo.

3. **Configure Auth**
   - Enable no-code auth plugin in Appsmith.
   - Assign users to Admin, Manager, Analyst roles.

4. **AI Assistant Setup**
   - Connect your OpenAI or similar API key in the AI Assistant panel widget.

5. **Branding**
   - Logos are in `assets/` — update if needed.

6. **Deploy**
   - Click **Deploy** in Appsmith to launch your dashboard.
   - Share the link with your team!

---

## Files

- `appsmith_app_import.json`: Importable app config for Appsmith.
- `dashboard_template.json`: Dashboard template structure.
- `sample_dataset.csv`: Demo dataset for upload/testing.
- `assets/`: Company logos.
- `README.md`: Deployment guide (this file).

---

## Customization & Adaptation

- **Retool/Bubble**: Use the included dataset and dashboard template as a reference for widgets/settings.
- **Supabase Studio**: Connect database, use CSV for initial import, then recreate dashboards using included template.

---

## Support

Questions? [Appsmith Docs](https://docs.appsmith.com/) or contact your platform admin.
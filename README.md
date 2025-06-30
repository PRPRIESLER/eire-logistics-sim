# Ireland Logistics Simulation & Optimization Engine 🚚🇮🇪

**A full-scale logistics command center for simulating, analyzing, and optimizing delivery networks across Irish cities.**

This project generates 50,000+ simulated delivery trips across Ireland using OpenStreetMap and CSO geographic data, routed through a local OSRM instance. It’s designed to replicate realistic delivery logistics for food or e-commerce, with plans for anomaly detection, traffic impact analysis, and optimization using Google OR-Tools.

---

## Features (Phase 1 – In Progress)

- ✅ Delivery trip generation using weighted urban populations
- ✅ Real geospatial delivery points within Irish urban polygons (CSO data)
- ✅ Route distances and durations using OSRM
- 🔄 Data export for analysis and modeling

---

## 💡 Coming Soon

- Route anomaly detection (outliers in time/distance)
- Peak hour demand modeling
- Delivery optimization using Google OR-Tools
- Power BI dashboards / Jupyter reports

---

## Data Sources

- **OpenStreetMap** (`.osm.pbf` file)
- **CSO Urban & Small Area Boundaries** (GeoJSON from [CSO.ie](https://www.cso.ie/))

---

## Tech Stack

`Python` · `GeoPandas` · `pandas` · `OSRM` · `Power BI` · `Google OR-Tools` · `SQL` _(planned)_

---

## 📁 Project Structure

eire-logistics-sim/
├── data/ # CSO GeoJSONs, delivery point data (locally stored)

│ ├── smart_delivery_points.csv

│ └── \*.geojson (ignored in Git)

├── notebooks/ # Jupyter Notebooks for EDA, simulation, routing

│ └── urbanAreas.ipynb

├── .gitignore

├── README.md

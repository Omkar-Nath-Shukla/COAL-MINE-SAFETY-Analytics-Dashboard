# COAL-MINE-SAFETY-Analytics-Dashboard

Indian Coal mine accident analysis and interactive dashboard (1997–2022). This repository contains the data, notebooks, and exported visual assets used to build the analytics dashboard shown in the screenshots below.

**Key contents**
- `Final Dshboard/Core_Project.ipynb`: Jupyter notebook used to prepare the dashboard and visualizations.
- `Final files/`: cleaned and derived CSV files used by the dashboard (pre-processed inputs).
- Top-level CSVs: several source CSVs (e.g. `table1_accident_casualty_trend_1997_2022.csv`) containing raw DGMS SANKET data.

Overview
--------
This project analyses Indian coal mine accidents using Python (Pandas) and visualizes results in a dashboard (Power BI / notebook-based visual exports). The dashboard highlights national safety trends, cause & enforcement analysis, company benchmarking (CIL subsidiaries vs non-CIL), and an executive summary.

How to use
----------
1. Open the notebook at `Final Dshboard/Core_Project.ipynb` to explore the data processing and visualization code.
2. The notebook reads CSVs from `Final files/` and the repo root. Run cells to reproduce charts (ensure required Python packages are installed).
3. If you want the README screenshots to render locally, place the dashboard images in the `assets/screenshots/` folder with the filenames listed below.

Screenshots
-----------
The repository README references four dashboard screenshots exported from the final dashboard. Add the provided images (from the attachments) into `assets/screenshots/` using these filenames:

- `assets/screenshots/overview.png` — COAL MINE SAFETY OVERVIEW (1997–2022)
- `assets/screenshots/safety_enforcement.png` — SAFETY RISK & ENFORCEMENT ANALYSIS
- `assets/screenshots/company_benchmark.png` — COMPANY BENCHMARK ANALYSIS (CIL Subsidiaries)
- `assets/screenshots/executive_summary.png` — EXECUTIVE SUMMARY slide

After placing images in the folder the markdown below will display them. If you prefer different filenames, update the paths accordingly.

Executive Summary
-----------------
![Executive Summary](assets/screenshots/executive_summary.png)

Company Benchmark
-----------------
![Company Benchmark](assets/screenshots/company_benchmark.png)

Safety Risk & Enforcement
-------------------------
![Safety & Enforcement](assets/screenshots/safety_enforcement.png)

Overview Dashboard
------------------
![Overview](assets/screenshots/overview.png)

Quick analysis summary
----------------------
- Total accidents, fatalities, and serious-injury trends are pre-computed in the notebook and available under `Final files/`.
- Key findings (as shown in the dashboard): fatalities reduced substantially over the study period; underground mines contributed a large share of fatalities; transportation and roof falls are important causes; CIL subsidiaries and non-CIL companies differ in harm profiles.

Reproducing the environment
---------------------------
This repo does not currently include a pinned environment file. For a minimal Python environment to run the notebook, install the usual data stack:

```
pip install pandas matplotlib seaborn jupyterlab
```

Notes
-----
- If you want, I can add the `assets/screenshots/` folder and commit the images into the repo — please confirm and upload the four PNG files (or grant access to them). Alternatively, I can update the notebook to embed images encoded as base64 if you prefer.
- The notebook includes the complete data processing pipeline; use it to regenerate any chart variants.

License / Attribution
---------------------
Data source: DGMS SANKET (publicly available accident statistics). Analysis and dashboard prepared using Python and Power BI.


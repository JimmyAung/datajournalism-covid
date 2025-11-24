# COVID-19 Data Journalism Project (2020–2024)

## Overview

A comprehensive data journalism project analyzing global COVID-19 trends from 2020 to 2024. This project combines rigorous data analysis with interactive Tableau visualizations to explore pandemic patterns, regional disparities, policy responses, and vaccination impact.

**Key Focus Areas:**
- Per-million metrics for standardized cross-country comparison
- Temporal patterns and pandemic waves across four years
- Regional disparities in cases, deaths, and testing
- Policy stringency and government response effectiveness
- Vaccination rollout and impact analysis

## TL;DR

📊 Interactive Tableau dashboards exploring global COVID-19 data (2020–2024)  
📈 Analysis of cases, deaths, testing, vaccinations, and policy responses  
🗺️ Regional comparisons using per-million standardized metrics  
📄 Comprehensive written report with key findings  
🔍 Data sources: Our World in Data (OWID), Johns Hopkins University (JHU), Oxford COVID-19 Government Response Tracker

## Screenshots

*Hero visualizations showcasing key insights from the analysis:*

![Global COVID-19 Trends](images/global-trends.png)
*Figure 1: Global COVID-19 case and death trends over time*

![Regional Comparison](images/regional-comparison.png)
*Figure 2: Per-million case rates across major regions*

![Vaccination Impact](images/vaccination-impact.png)
*Figure 3: Vaccination rollout and correlation with case reduction*

![Policy Stringency](images/policy-stringency.png)
*Figure 4: Government response stringency and COVID-19 outcomes*

## Repository Structure

```
datajournalism-covid/
├── tableau/              # Tableau workbooks (.twbx files)
│   ├── covid-dashboard-main.twbx
│   ├── regional-analysis.twbx
│   └── vaccination-tracker.twbx
├── reports/              # Analysis reports and findings
│   ├── covid-analysis-report.pdf
│   └── methodology-notes.pdf
├── images/               # Hero charts and key visualizations
│   ├── global-trends.png
│   ├── regional-comparison.png
│   ├── vaccination-impact.png
│   └── policy-stringency.png
├── LICENSE               # MIT License
└── README.md             # This file
```

**Note:** Raw data files are not included in this repository due to size constraints (approx. 50-100 MB for complete datasets in CSV/JSON format). See the Data Sources section below for information on obtaining the source data.

## Data Sources

This project utilizes publicly available COVID-19 datasets from reputable sources:

- **Our World in Data (OWID)** – Primary source for global COVID-19 statistics
  - Comprehensive country-level data on cases, deaths, testing, and vaccinations
  - Standardized per-million population metrics
  - Updated regularly with quality controls
  - Source: https://ourworldindata.org/coronavirus

- **Johns Hopkins University (JHU) CSSE** – Cross-validation and supplementary data
  - Daily case and death counts by country and region
  - Time series data from January 2020 onwards
  - Source: https://github.com/CSSEGISandData/COVID-19

- **Oxford COVID-19 Government Response Tracker** – Policy stringency data
  - Government response stringency indices
  - Policy intervention tracking across countries
  - Lockdown measures, travel restrictions, and economic support
  - Source: https://www.bsg.ox.ac.uk/research/covid-19-government-response-tracker

**Data Coverage:** January 2020 – December 2024

**Note:** Due to repository size constraints, raw datasets are not shipped with this project. To reproduce the analysis:
1. Download datasets from the sources above
2. Follow data preparation steps documented in `reports/methodology-notes.pdf`
3. Open Tableau workbooks and reconnect to your local data files

## How to View the Analysis

### Viewing Tableau Dashboards

1. **Download Tableau Reader** (free):
   - Visit: https://www.tableau.com/products/reader
   - Install Tableau Reader for your operating system

2. **Download the Tableau Workbooks (.twbx)**:
   - Navigate to the `tableau/` directory in this repository
   - Download the `.twbx` files you want to explore:
     - `covid-dashboard-main.twbx` – Main dashboard with global overview
     - `regional-analysis.twbx` – Regional breakdowns and comparisons
     - `vaccination-tracker.twbx` – Vaccination rollout analysis

3. **Open in Tableau Reader**:
   - Double-click the downloaded `.twbx` file, or
   - Open Tableau Reader and select File → Open → Choose the `.twbx` file

4. **Interact with the dashboards**:
   - Use filters to explore specific countries, regions, or time periods
   - Hover over data points for detailed information
   - Click on visualizations to drill down into the data

### Reading the Report

- Download `reports/covid-analysis-report.pdf` for a comprehensive written analysis
- See `reports/methodology-notes.pdf` for detailed methodology and data processing steps

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

**Copyright (c) 2025 Myo Myint Aung Jimmy**

You are free to:
- Use the visualizations and analysis for personal or commercial projects
- Modify and build upon this work
- Share and distribute the dashboards

**Attribution appreciated but not required.**

---

*For questions or collaboration opportunities, please open an issue or reach out via GitHub.*

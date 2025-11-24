
# COVID-19: Where Was It Worst? — A Data Journalism Project

![Overview](images/hero2.png)

Short, visual story on how COVID-19 evolved globally (**2020–2024**): temporal patterns, regional disparities, the role of vaccination, and policy stringency. Built with **Tableau (TWBX)** using **OWID** data.

## TL;DR
- **Deaths peaked in 2021**, cases peaked in **2022 (Omicron)**; severity fell as vaccination & treatments improved.  
- **South America & parts of Europe** had the highest deaths per-million; **Oceania** saw lower outcomes under stricter border controls.  
- **Higher vaccination** ↔ **lower death-to-case ratios**.  
- **Policy stringency** shows a complex, time-dependent relationship with outcomes (association, not causation).

## Repository Structure
images/ -> README hero/screenshot(s)
reports/ -> Slide deck (PDF)
tableau/ -> Packaged workbook (.twbx)
LICENSE -> MIT
README.md -> this file


## Data Source
**Our World in Data (OWID) COVID-19 dataset**  
- GitHub: `owid/covid-19-data`  
- Metrics used: new/total **cases & deaths per million** (7-day smoothed), **hospital/ICU admissions**, **vaccination coverage**, **Oxford stringency index**.  
- Time window: **Jan 2020 – Dec 2024**.

## How to View the Dashboard
1) Download the TWBX from `tableau/`.  
2) Open with **Tableau Desktop** or **Tableau Public (Desktop)**.  
3) Use the filters to explore **Global Trends**, **Regional Comparisons**, **Temporal Patterns**, and **Policy Impact**.

## Methods (Brief)
- Per-million rates for cross-country comparability.  
- 7-day smoothing to reduce reporting noise.  
- Focus countries for examples: **Peru, Bulgaria, Brazil, Hungary, UK, USA, India, Singapore, North Macedonia**.

## Notes & Limits
- Data quality differs by country and period (testing/reporting changes).  
- Stringency is **associative**, not causal; high levels often coincide with worsening outbreaks.  
- 2023–2024: many regions reduced testing; interpret late-period declines with caution.

## License
This project is released under the **MIT License** (see `LICENSE`).

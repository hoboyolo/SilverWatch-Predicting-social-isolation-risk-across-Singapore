# 🛡️ SilverWatch: AI-Powered Eldercare Isolation & Risk Dashboard

**SilverWatch** is an open-data analytics and geospatial dashboard developed for **Track A1** of the Databricks & Open Data Hackathon. It identifies, prioritizes, and maps social isolation risk among seniors across Singapore's planning areas to optimize Active Ageing Centre (AAC) resource deployment and volunteer outreach.

---

## 🚀 Project Overview

Social isolation among older adults is a growing urban challenge. SilverWatch addresses this by combining Singapore Census demographic data and eldercare infrastructure indicators into a unified pipeline that features:
1. **Composite Isolation & Aging Risk Index:** A transparent scoring model balancing absolute elderly population volume with aging density proportions.
2. **Geospatial Risk Heatmap:** An interactive map visualizing high-risk planning areas across Singapore.
3. **Prioritized Outreach Top 10 List:** Actionable rankings to direct social workers and volunteer coordinators where help is needed most.
4. **Interactive Dashboard:** A local prototype combining data tables, charts, and spatial visualisations.


---

## 📁 Repository Structure

```text
├── ResidentPopulationbyPlanningAreaSubzoneofResidenceAgeGroupandSexCensusofPopulation2020.csv # Census demographic data
├── SeniorActivityCentresAndActiveAgeingCentresAnnual.csv                                    # Eldercare facility data
├── silverwatch_pipeline.py                                                                # Master data processing and visualization script
├── app.py                                                                                 # Interactive Streamlit dashboard UI
├── silverwatch_top10_risk.png                                                             # Generated poster-grade chart
└── silverwatch_heatmap.html                                                               # Generated interactive geospatial map

# 🌐 ENSO Analytics: Monitoring Climate Anomalies, Economic Losses & Food Security


An end-to-end climate intelligence and business analytics dashboard evaluating Equatorial Pacific Sea Surface Temperatures (SST), El Niño & La Niña cycles, global agricultural yields, and socio-economic vulnerabilities. This framework bridges spatial climate data and policy analytics to empower data-driven climate resilience and disaster risk reduction.

---

## 📸 Executive Summary & Dashboard Previews

### 1. ENSO Analytics Conceptual Overview
![ENSO Overview](Screenshot%202026-09-15%20174147.png)

> **Visual Synthesis:** A dual-hemispheric visualization illustrating the atmospheric divide between El Niño and La Niña. The left hemisphere depicts extreme solar radiation, thermal land degradation, severe drought conditions, and agricultural moisture stress. The right hemisphere captures intense convective cloud formation, localized precipitation, atmospheric storm generation, and inundated rice paddies.

---

### 2. La Niña Global Impact & Disaster Analytics (2020–2023)
![La Niña Impact](Screenshot%202026-09-15%20174505.png)

> **Visual Synthesis:** A high-contrast dark-mode diagnostic interface tracking global cold-phase anomalies. Features key metric indicators (**Current ONI: -1.1 °C**, **Total Damage: $535B**, **448 Events**), a multi-categorical disaster donut breakdown (41.73% Hydrological, 27.51% Meteorological), annual population impact bar charts, top economic loss rankings (led by the US at $0.44B), and a global geospatial disaster severity heat map.

* **Multi-Year Anomalies:** Analyzes atmospheric feedback loops and oceanic cooling patterns across the central and eastern tropical Pacific down to a peak anomaly of **-2.4 °C**.
* **Compound Disasters:** Tracks **448 total La Niña events** with an average duration of 11 months, detailing compound impacts across hydrological (270 events) and meteorological (178 events) vectors.
* **Vulnerability & Losses:** Quantifies total economic damage (**$535 Billion**) and maps annual population displacement peaking across the 2020–2023 timeline.

---

### 3. El Niño & Climate Disaster Analytics
![El Niño Analytics](Screenshot%202026-09-15%20174539.png)

> **Visual Synthesis:** A thermal-themed dashboard tracking Pacific warm-phase anomalies. Showcases core KPI blocks (**Highest ONI Value: 2.30**, **530 Total Natural Events**, **14 Drought Events**), disaster sub-type bar charts (272 Hydrological, 178 Meteorological), a historical ONI trend curve peaking in 2015, an annual fatality tracking line chart (peaking at 38M), and a regional population impact choropleth map.

* **Thermal Spike Tracking:** Monitors extreme oceanic thermal spikes reaching an ONI peak of **2.30**, capturing 6 extreme heat events and 14 major global drought occurrences.
* **Hazard Identification:** Categorizes 530 natural events (82% of total disaster volume) with granular sub-type tracking across hydrological, meteorological, and climatological hazards.
* **Human Impact:** Evaluates public health vulnerabilities, thermal stress metrics, and socio-economic displacement factors during peak warming events, showing sustained high-risk thresholds between 33M and 38M individuals annually from 2020 to 2023.

---

### 4. Global Agricultural & Food Security Analytics
![Global Agricultural Analytics](Screenshot%202026-09-15%20174644.png)

> **Visual Synthesis:** An agricultural intelligence platform featuring top-level production metrics (**12.45B Total Production**, **5.32B Harvested Area**, **$278.6B Economic Loss**, **235.7M People Affected**). Displays crop pricing breakdowns (led by Thai Rice 5% and Soybeans), historical commodity trend lines, disaster event distribution by type, multi-year crop production yield comparisons, and country-level filtering controls.

* **Supply Chain Intelligence:** Evaluates crop output across **5.32 Billion hectares** of harvested area, monitoring core staple yields including Thai 5% Rice ($247K aggregate price index), Soybeans ($234K), and HRW Wheat ($132K).
* **Commodity Dynamics:** Correlates **$278.6 Billion in economic losses** directly with international food price fluctuations (tracking an ONI Food Price Index baseline of 129.40) and historical price peaks between 2020 and 2023.
* **Humanitarian Analytics:** Connects climate hazard severity with local food security indices to support targeted disaster response and supply chain resilience across major producing countries (Argentina, Australia, Brazil, India).

---

## 💡 Key Insights & Findings

* **Triple-Dip La Niña Impact:** The continuous cold phase from 2020 to 2023 generated **$535 Billion** in cumulative damages, with hydrological events representing **41.73%** of all recorded disaster subgroups.
* **Thermal Sensitivity & Human Exposure:** El Niño warm-phase peaks (ONI **2.30**) directly correspond with sharp escalations in affected populations, maintaining over **30 Million** impacted individuals annually during active windows.
* **Agricultural Yield Risk:** Compound ENSO anomalies resulted in **$278.6 Billion** in agricultural losses across **5.32 Billion** harvested hectares, driving sharp volatility in staple grain commodity price indices.

---

## 🛠️ Tech Stack & Implementation Details

* **Business Intelligence:** Microsoft Power BI / Tableau
* **ETL & Transformation:** Power Query, Python (Pandas, NumPy)
* **Data Sources:** NOAA (SST & ONI Index), NASA SEDAC (Population), FAO (Agricultural Data), World Bank
* **Data Modeling:** Advanced DAX metrics for rolling thermal anomalies, variance metrics, ranking, and predictive yield loss indices

---

## 📄 License & Citation

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

### Citation
If you use this project, analytical framework, or dataset integrations in your research or applications, please cite it as:

```bibtex
@misc{ENSOAnalytics2026,
  author = {SAI-798},
  title = {ENSO Analytics: Monitoring Climate Anomalies, Economic Losses, and Population Vulnerability},
  year = {2026},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{[https://github.com/SAI-798/ENSO-Analytics](https://github.com/SAI-798/ENSO-Analytics)}}
}

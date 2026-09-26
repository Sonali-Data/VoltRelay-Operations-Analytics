# ⚡ VoltRelay Energy: Operational & Strategic Fleet Diagnostics

An end-to-end operational diagnostic and strategic decision model analyzing *3.8M+ battery swap records* across 6 EV fleet hubs (Jan 2024 – Jun 2025).


## 📌 Executive Summary
Between Jan 2024 and Jun 2025, VoltRelay scaled monthly swap volume from ~100k to 320k+. However, rapid top-line growth masked critical operational bottlenecks:
- Service failure rates surged above *6.5%* during peak demand hours.
- Station throughput bottlenecks emerged due to hardware degradation.
- Supplier warranty recourse was severely underutilized.

This project sanitizes 3.8M raw operational transactions, identifies systemic failure modes, and proposes a data-backed CAPEX/OPEX reallocation strategy.


## 🛠️ Data Engineering & Quality Traps Resolved
Handled *5 critical real-world data anomalies* before modeling:
1. *Timezone Offset Inconsistencies:* Aligned UTC and IST swap timestamps to correct peak-hour load calculations.
2. *Ghost / Test Stations:* Isolated non-operational sandbox stations skewing failure KPIs.
3. *Duplicate Retry Storms:* De-duplicated multi-tap user retry attempts within tight time windows.
4. *Sensor Calibration Drift:* Corrected voltage and temperature telemetry anomalies.
5. *Contract Unit Economics:* Normalized tiered revenue per swap against customer segment discounts.


## 📊 Key Findings & Strategic Recommendations
- *Asset Retrofit over Geographic Expansion:* Diverted 40% of planned new station CAPEX into retrofitting failing chargers in high-density corridors.
- *Supplier Warranty Recovery:* Identified battery pack degradation clusters, unlocking warranty claims from Tier-1 cell manufacturers.
- *Dynamic Queue Management:* Introduced predictive station allocation during 4:00 PM – 8:00 PM peak rush.


## 🔗 Project Deliverables & Links
- *Interactive Colab Notebook:* [Google Colab Link](https://colab.research.google.com/drive/165vS7lu-805KgiuA0EeIEMvPU6szyT47?usp=sharing)
- *Demo Video Presentation (2:47 min):* [Watch Video](https://drive.google.com/file/d/1fqPhNhTH4UhcFudiAKFCPBNsh7gKalS/view?usp=sharing)
- *LinkedIn Case Study:* [View Post](https://www.linkedin.com/feed/update/urn:li:activity:7509468977673277440/)
-

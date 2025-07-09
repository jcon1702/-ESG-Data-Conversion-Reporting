# ESG Data Conversion & Reporting

An end‑to‑end Excel/Google Sheets solution to convert hardcopy ESG records into actionable dashboards and reports.

---

## 📘 Background

TotalEnergies Vietnam has recently completed a major ESG data collection campaign—from recycled oil reports to solar plant performance—most of which still exists in hardcopy or mixed formats. To support weekly reporting and strategic decision‑making, we need to:

* Digitize all historical ESG records

* Clean & normalize mixed‐format data (dates, units, missing values)

* Visualize key KPIs in interactive dashboards

* Generate concise reports for PMs and the Board

This mock project demonstrates a repeatable workflow to transform raw OCR‑style input into polished deliverables.

---

## 🎯 Objective

1. Convert scanned & inconsistent ESG records into a standardized Excel table

2. Clean and impute missing/erroneous values for energy consumption, CO₂ emissions, and waste generated

3. Aggregate metrics by day and by week using PivotTables

4. Visualize trends with charts and slicers on a Dashboard sheet

5. Summarize key insights and recommendations in a PowerPoint report

---

## 🗂️ Dataset

* Raw\_OCR (sheet): 20 raw records with mixed date formats and units

* Cleaned (sheet): Standardized table (Date,Energy\_kWh,CO2\_tons,Waste\_kg)

* Dashboard (sheet): Interactive charts & slicers

---

## 🛠 Methodology

1. Data Cleaning

2. Aggregation

3. Dashboard Building

4. Insights & Analysis

---

## 📊 Results & Visuals

Week with Largest WoW (Week over Week) Change: Week 23

Week with Largest Quantity in Total: Week 24

### Energy Consumed:

* Total Energy Consumed: 37400

* Average Weekly Energy: 9350 kWh

* Peak Energy Consumed: 14700 kWh (Week 24)

* Peak WoW Rate: +78.26% (Week 24)

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdtlIo7fC1JZ1V68o5ZecrPaVFdzeTDhVnx_OKb0SAa-sjtpv62VK1YBPGVocNw036h0A3AGWG8OAAsEa3cJMzZDs6gh2SE391g0mxr_EJo47zHZ3wJE1UH5SEiGUnobbUgKlIs?key=SJAGy97b_YGOHcprE-fWMA)

### CO2 Emission

* Total CO2 Emission: 18.65 tons

* Average Weekly CO2: 4,6625 tons

* Peak CO2 Emission: 7,35 (Week 24)

* Peak WoW Rate: +78.02% (Week 23)

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe4O76Sok23xM25m0lBBv_CKEZxXnLfGhli5w3J9TFpkSVELFk_7pLhjiY0NI68gYz7xMnF2tUfchqMLAuuJ3quuC-Pnf2YNnjtsTd0rBd4TqZTDNIztn-ujooVKzfGc9lkzVG9hQ?key=SJAGy97b_YGOHcprE-fWMA)

### Waste Generated

* Total Waste Generated: 3760 kg

* Average Weekly Waste: 940 kg

* Peak Waste Generated: 1470 kg (Week 24)

* Peak WoW Rate: +78.72% (Week 23)

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdzaZ05plDczJ9jOGIU5Rtxcuask8qku0Oh0qPSFcDf0TYsyc1otpnvAZyEhlzMRp8njafFzGvtDhEPoUZoRCbIe1kjWF2SiWPddDtP23EGYGMUmUAnFU_wGFV5uq1jCUs8qoX_wA?key=SJAGy97b_YGOHcprE-fWMA)

---

## ✅ Conclusions & Next Steps

* Success: Achieved full digitization and reliable dashboards in under one week

* Insight: Energy spikes on maintenance days; CO₂ correlates strongly with energy usage

* Recommendations:
  
  * Automate OCR workflow (e.g. Power Automate)

  * Extend to Power BI for real‑time monitoring

  * Integrate with corporate ESG portal for quarterly reporting

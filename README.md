Don't be surprise by the commit history! This repo is basically from DS-DA-Dibimbing, moved here to make it more elegant.

---

# Global Integrated Circuit (IC) Trade — Data Analysis (2020–2024)

**Power BI + EDA** project analyzing worldwide Integrated Circuits (IC) exports: trends, top markets, value-per-kg, and exporter/importer composition. Built for fast, decision-ready insights and storytelling.

> ICs are a strategic commodity underpinning AI, 5G, IoT, autos, and more. This repo packages the data prep, analysis notes, and a Power BI dashboard for exploration.&#x20;

---

## 📌 (Findings)

* **2022** recorded the **highest total export value** (\~USD **2.15T**), about **+43.5% vs 2024** (lowest).&#x20;
* **Global participation widened post-COVID**: not only values increased, but the number of **importers and exporters** rose, signaling broader supply-chain engagement.&#x20;
* **>50% of countries act as importers** while a minority are exporters → **concentrated supply**.&#x20;
* **Value per kg** highlights **high-value hubs** (e.g., Hong Kong SAR, Singapore, Japan) vs **mass movers** exporting large volumes at lower \$/kg (e.g., Russia, Belarus).&#x20;

---

## 🗂 Data

* **Source:** UN Comtrade (IC/semiconductor exports).
* **Coverage:** Year, country, net weight, quantity, export value. Data was cleaned, transformed, and visualized for EDA.&#x20;
* **Key metric:** **Export value per net weight** (USD/kg) to surface “high-value, low-mass” IC flows.&#x20;

---

## 📊 Dashboard (Power BI)

Open `pbix/IC_Trade_Analysis.pbix` in **Power BI Desktop** to interact with:

* **Trends (2020–2024)** for total export value (T USD).&#x20;
* **Country drill-downs:** total quantity, net weight, and **avg export value per net weight** (USD/kg).&#x20;
* **Importer vs exporter composition** by year.&#x20;

**Notes**

* 2022 peak and the relative drop to 2024 are annotated in the dashboard.&#x20;
* Use filters to compare **high-value hubs** vs **high-volume movers**.&#x20;

---

## 🔎 Method (EDA)

1. **Data Cleaning** — type casting, outlier checks, missing handling (e.g., quantity gaps in some countries/years).&#x20;
2. **Transformations** — aggregate by year & country; compute **value per net weight**; create importer/exporter counts.&#x20;
3. **Visualization** — trend lines, bar charts, and distribution comparisons in Power BI.&#x20;

---

## 💡 Insights (Selected)

* **Post-COVID surge**: Export values rose sharply, peaking in **2022**, before stabilizing from **2023** onward.&#x20;
* **Participation up**: Importer/exporter counts increased with the recovery; the exporter share remains **<50%**, indicating supply concentration.&#x20;
* **Value vs volume**:

  * **High \$/kg hubs** include Hong Kong SAR, Singapore, Japan—reflecting re-export roles, advanced assembly/testing, or specialized chips.&#x20;
  * **High-volume movers** (e.g., Russia, Belarus) show large quantities but **lower \$/kg** due to commodity-grade logic/MCUs.&#x20;

---

## 📌 Business Implications

* **Scale where it matters**: Focus on **high-value IC segments** (AI, automotive, medical devices) rather than pure tonnage.&#x20;
* **Fortify logistics hubs**: Countries acting as re-export or testing/assembly hubs can optimize **ports & regional partnerships** to reduce friction.&#x20;
* **Data transparency**: Improve export **quantity reporting** to sharpen policy and trade strategy.&#x20;

---

## 🙌 Credits

* Data: **UN Comtrade**
* Analysis & dashboard: **Rizky Febri Ibra Habibie**
* Contact: [rizkyfebriibrahabibie@gmail.com](mailto:rizkyfebriibrahabibie@gmail.com) | LinkedIn: /in/rizkyfebriibrahabibie/

---

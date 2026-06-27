# 🚗 EV Market Analysis Dashboard

## 📊 Project Overview

This project analyzes global electric vehicle (EV) market trends, focusing on adoption rates, pricing, efficiency, and charging infrastructure. The goal is to identify regions where EV demand is growing faster than infrastructure, highlighting potential bottlenecks.

---

## 🛠️ Tech Stack

* **Python (pandas, Jupyter Notebook)** – Data cleaning & feature engineering
* **MySQL** – Data storage and transformation using SQL views
* **Power BI** – Interactive dashboard and data visualization

---

## 🔄 Data Pipeline

1. **Data Cleaning & Feature Engineering (Python)**

   * Created new metrics:

     * Demand Pressure (sales vs charging stations)
     * Charging efficiency (range per hour)
     * Battery efficiency (km per kWh)
     * Price-to-performance ratios

2. **SQL Data Modeling (MySQL)**

   * Built views to aggregate and structure data:

     * `top_country_sales`
     * `demand_pressure_view`
     * `brand_efficiency`
     * `charging_speed_view`
     * `price_vs_adoption`

3. **Visualization (Power BI)**

   * Connected Power BI directly to MySQL
   * Created dashboards with:

     * KPIs (Total Sales, Adoption Rate, Demand Pressure)
     * Bar charts (country sales, infrastructure pressure)
     * Scatter plot (price vs adoption)

---

## 📈 Key Insights

* Countries like **Japan and Germany** show high demand pressure, indicating infrastructure may not be scaling with EV adoption
* EV adoption is influenced by both **price and infrastructure availability**
* Certain brands demonstrate higher energy efficiency, impacting long-term consumer value
* Countries reflected a high percentile adoption rate, indicating a high comfort level with adopting new automotives 
---

## 📷 Dashboard Preview

<img width="1286" height="730" alt="image" src="https://github.com/user-attachments/assets/eb7c5c65-a156-4c1e-8b9d-de4321e28f61" />

---

## 🚀 Future Improvements

* Add time-series analysis for adoption trends
* Incorporate real-world charging network data
* Deploy dashboard to Power BI Service for sharing

---

## 💡 Key Takeaway

This project demonstrates a full data analytics workflow — from data cleaning and SQL modeling to interactive dashboarding — mirroring real-world data analyst responsibilities.

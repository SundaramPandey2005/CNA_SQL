# 📦 Solving Inventory Inefficiencies Using SQL

An end-to-end SQL-based analytics solution designed to optimize inventory management, reduce stockouts, and minimize overstock risks for retail chains and warehouses. This project leverages historical sales data, demand trends, and external factors like seasonality and weather to generate actionable insights for supply chain decision-making.

---

## 🎯 Project Objective

This project aims to empower inventory-intensive businesses by enabling them to:

- 🏪 Track stock levels in real-time across multiple stores and warehouses.
- 🔄 Forecast product demand and predict reorder timelines.
- 🚩 Detect stockouts and overstock situations dynamically.
- 🏷️ Categorize products by sales velocity for smarter inventory segmentation (e.g., ABC analysis).
- 📊 Compare and benchmark inventory health across different store locations.
- 🔍 Align forecasted demand with actual sales to improve planning accuracy.

---

## 🗺️ Database Schema

The analysis is powered by a structured relational database with the following key tables:

| Table              | Description                                          |
|--------------------|------------------------------------------------------|
| **stores**         | Maps store IDs to corresponding inventory and products. |
| **inventory**      | Tracks stock levels, units sold, and daily demand data.  |
| **external_factor**| Links store and product to seasonal and weather patterns. |
| **seasonality**    | Contains season data (e.g., winter, summer, etc.).       |
| **weather**        | Describes weather conditions relevant to sales trends.   |
| **category**       | Contains product category metadata (e.g., perishable, non-perishable). |

---

## 🛠️ Features & Functionalities

- 📊 **Dynamic KPI Dashboards:** Generate dashboards for stock turnover, sell-through rate, and days of inventory remaining.
- 🚚 **Demand Forecasting:** Predict when stock will run out based on historical sales and external influences.
- 🚩 **Stockout & Overstock Alerts:** Real-time SQL queries flag SKUs that are at risk.
- 🏷️ **ABC Classification:** Segment inventory based on velocity to prioritize focus.
- 🏪 **Multi-Location Analysis:** Compare inventory efficiency across 7+ warehouses or stores.
- ⚙️ **Automated Reporting:** SQL queries structure reports for supply chain managers.

---

## 🔧 Tools & Tech Stack

- **SQL (MySQL/PostgreSQL)** — For querying, analysis, and dashboard creation.
- **Excel / Google Sheets / PowerBI (Optional)** — For visualization if extended.
- **GitHub** — For version control and collaboration.

---

## 📈 Key Results (Hypothetical / Projected)

- ✅ Reduced stockouts by **27%**.
- ✅ Minimized overstock days by **32%**.
- ✅ Improved inventory decision-making speed by **40%** through automated SQL dashboards.

---

## 🚀 How to Run

1. Clone this repository.
2. Import the SQL schema into your MySQL/PostgreSQL instance.
3. Load sample data (`/data/` folder if provided).
4. Run SQL queries in the `/queries/` folder:
   - `stock_summary.sql` — Current stock health
   - `demand_forecast.sql` — Demand prediction
   - `stockout_alerts.sql` — Detect low inventory
   - `abc_analysis.sql` — Product classification
5. (Optional) Connect to BI tools for visualization.

---

## 💡 Future Enhancements

- Integrate with real-time APIs for live stock updates.
- Deploy interactive dashboards using Streamlit or PowerBI.
- Incorporate ML-based demand forecasting models.

---

## 🤝 Acknowledgements

- Consulting & Analytics Club — IIT Guwahati  
- Mentors and peers who guided the development  
- Open-source SQL resources and datasets for reference  

---



---


---


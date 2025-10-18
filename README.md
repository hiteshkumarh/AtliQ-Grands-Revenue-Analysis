# 🏨 AtliQ Grands - Revenue Analysis and Business Intelligence Dashboard

## 📘 Executive Summary

AtliQ Grands, a leading hotel chain in India, was experiencing a decline in market share and revenue performance due to increased competition and a lack of data-driven decision-making.

This Business Intelligence project was initiated to **identify revenue leakages**, **optimize occupancy**, and **enable strategic planning** through a comprehensive **Power BI dashboard**.
The goal is to track revenue sources and other critical performance indicators across all properties.

---

## 🎯 Business Objective

The primary objective of this project was to implement a **data intelligence solution** to provide actionable insights into AtliQ Grands' business operations.

### Specific Goals

* Identify key factors influencing revenue performance.
* Develop a KPI dashboard to track revenue sources and other KPIs across various dimensions.
* Empower the management team to make strategic, data-informed business decisions.
* Increase overall revenue and market share through enhanced performance tracking.

---

## 🧰 Technology Stack

* **Microsoft Power BI** – Data visualization and reporting
* **Power Query** – Data cleaning and transformation
* **Power Pivot** – Data modeling and DAX measure creation

---

## ⚙️ Solution Approach

The project involved **collecting**, **cleaning**, and **modeling** data to create an interactive Power BI dashboard for tracking key business metrics.

### 🧩 Data Model

Five tables were used:

* 3 Dimension Tables → `dim_date`, `dim_hotels`, `dim_rooms`
* 2 Fact Tables → `fact_bookings`, `fact_aggregated_bookings`

Relationships were created in Power Pivot to build a robust data model for analysis.

![Data Modeling](https://github.com/hiteshkumarh/AtliQ-Grands-Revenue-Analysis/blob/main/Screenshot%20data%20modeling.png)

---

### 📊 Key Performance Indicators (KPIs)

DAX measures created for analysis:

| KPI                           | Description                                        |
| ----------------------------- | -------------------------------------------------- |
| **Revenue**                   | Total revenue realized from bookings               |
| **Total Bookings**            | Count of all booking IDs                           |
| **Average Rating**            | Average customer rating                            |
| **Total Capacity**            | Total room capacity from all properties            |
| **Total Successful Bookings** | Number of successful (checked-out) bookings        |
| **Occupancy Rate**            | (Total successful bookings / Total capacity) × 100 |
| **Cancellation Rate**         | (Total cancelled bookings / Total bookings) × 100  |
| **Average Stay Duration**     | Average number of nights per booking               |

---

## 📈 Revenue Analysis Dashboard

The final Power BI dashboard provides both **high-level and granular insights**, with interactive filters for **Month-Year**, **City**, **Booking Platform**, and **Booking Status**.

![Revenue Dashboard](https://github.com/hiteshkumarh/AtliQ-Grands-Revenue-Analysis/blob/main/Screenshot%20\(55\).png)

---

## 💡 Business Insights & Outcomes

Key findings from the analysis:

* **Regional Performance:** Mumbai generates the highest revenue, while Delhi generates the least — suggesting a need for focused marketing in Delhi.
* **Occupancy Trends:** Higher occupancy during weekends can be leveraged for promotional campaigns.
* **Booking Status:** 75% of all bookings generate revenue (70% checked out, 5% no-shows). Cancellation reasons should be analyzed further.
* **Delhi Anomaly:** Despite the highest occupancy (>60%), Delhi hotels have the lowest revenue — indicating a possible pricing or product issue.
* **Customer Metrics:** Average customer rating: 3.4–3.8; Average stay: 2.4 days. These can be compared with industry benchmarks.

---

## 🚀 Business Impact

The implementation of the dashboard enabled the Revenue Management team to make timely, **data-driven decisions**.

* Revenue and market share improved by **20% within one month**.
* Management gained a **holistic view of hotel performance**, enabling faster response to trends.
* Fostered a **data-driven culture**, supporting long-term business growth.

---

## 📂 Project File Structure

```
📁 AtliQ-Grands-Revenue-Analysis/
│
├── 📊 dashboard & PPT/          # Final Power BI dashboard (.pbix) and presentation (.pptx)
├── 📈 input files/              # Raw CSV data used for analysis
└── 📄 Revenue Analysis report.pdf  # Detailed project report (objective to impact)
```

---

## 🙌 Acknowledgment

This project demonstrates how **data-driven decision-making** and **Power BI analytics** can transform business performance in the **hospitality industry**.

---

## 👨‍💻 Author

**Hithesh Kumar**
📍 *Domain:* Hospitality Analytics | Power BI | Data Visualization
📅 *Project Year:* 2025



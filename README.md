# SkyRoutes Airline Performance Analysis

## Project Overview

This project analyzes airline route performance using **SQL and Power BI**.
The objective is to identify profitable routes, analyze seat occupancy, track monthly trends, and provide business insights to improve operational efficiency.

---

## Tools & Technologies

* MySQL (Data Analysis)
* Power BI (Dashboard & Visualization)
* Excel/CSV (Data Source)

---

## Dataset Information

The dataset contains flight-level operational data with the following key fields:

* FlightID
* RouteCode
* Origin
* Destination
* FlightDate
* FlightDurationMins
* AircraftType
* SeatsAvailable
* SeatsSold
* Revenue
* OperationalCost

---

## SQL Analysis Performed

1. Top 10 Most Frequent Routes
2. Average Revenue, Cost, and Profit per Route
3. Loss-Making (Underperforming) Routes
4. Seat Occupancy Percentage
5. Monthly Profit Trend
6. Domestic vs International Profit
7. Revenue per Minute (Operational Efficiency)
8. Top 10 Most Profitable Routes

SQL file:
`SkyRoutesAnalysis.sql`

---

## Power BI Dashboard

### Calculated Columns

* **Profit** = Revenue - OperationalCost
* **Occupancy %** = SeatsSold / SeatsAvailable * 100
* **Month** = Format(FlightDate, "YYYY-MM")

### Visualizations

* Top 10 Profitable Routes (Bar Chart)
* Monthly Profit Trend (Line Chart)
* Average Seat Occupancy % (Gauge)
* Revenue vs Cost Comparison (Stacked Column)
* Filters: RouteCode, AircraftType, Month

Dashboard file:
`RouteProfitDashboard.pbix`

---

## Key Business Insights

* A small number of routes contribute to the majority of total profit.
* Some routes show high occupancy but low profitability due to high operational costs.
* Average seat occupancy ranges between 70–85%, indicating optimization opportunities.
* Profit trends vary across months, showing seasonal demand patterns.
* Long-duration routes generate higher revenue per flight.
* Certain aircraft types are associated with lower operational efficiency.

---

## Project Structure

```
SkyRoutes-Analysis/
│
├── AirlineRoutes.csv
├── SkyRoutesAnalysis.sql
├── RouteProfitDashboard.pbix
└── README.md
```

---

## How to Use

### SQL

1. Import `AirlineRoutes.csv` into MySQL
2. Run queries from `SkyRoutesAnalysis.sql`

### Power BI

1. Open `RouteProfitDashboard.pbix`
2. Refresh data if needed

---

## Author

**Adarsh Mishra**
Aspiring Data Analyst

LinkedIn: https://linkedin.com/in/adarsh-mishra82
GitHub: https://github.com/Adarshmishra8299

---

## Project Goal

This project demonstrates skills in:

* SQL Data Analysis
* Business Insight Generation
* Data Visualization
* Dashboard Design

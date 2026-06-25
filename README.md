# Uber-Trip-Analysis-Dashboard
Interactive Uber Trip Analysis Dashboard built with Power BI, DAX, and Power Query to analyze bookings, revenue, trip efficiency, vehicle performance, and customer behavior through dynamic dashboards.

# 🚖 Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is an interactive Business Intelligence solution developed in **Power BI** to analyze Uber trip data and provide meaningful business insights. The dashboard enables stakeholders to monitor booking trends, revenue, trip efficiency, customer behavior, and operational performance through dynamic visualizations and KPIs.

This project demonstrates expertise in **Power BI, DAX, Power Query, Data Modeling, and Dashboard Design** by transforming raw trip data into actionable insights.

---

# 🎯 Business Objectives

- Analyze Uber booking trends.
- Monitor revenue generation.
- Measure trip efficiency.
- Identify peak booking hours.
- Analyze customer travel patterns.
- Evaluate vehicle performance.
- Analyze pickup and drop-off locations.
- Support business decisions using interactive dashboards.

---

# 📊 Dashboard Overview

## Dashboard 1 – Overview Analysis

### KPI Cards

- Total Bookings
- Total Booking Value
- Average Booking Value
- Total Trip Distance
- Average Trip Distance
- Average Trip Time

### Visualizations

- Bookings by Payment Type
- Bookings by Trip Type (Day/Night)
- Vehicle Type Analysis
- Daily Booking Trends
- Top Pickup Locations
- Most Preferred Vehicle Type
- Location Analysis

### Features

- Dynamic KPI Selection
- Dynamic Titles
- Interactive Slicers
- Tooltips
- Conditional Formatting
---

## Dashboard 2 – Time Analysis

Provides insights into booking demand across different time intervals.

### Visualizations

- Area Chart (10-Minute Booking Trend)
- Line Chart (Bookings by Day)
- Heatmap (Hour vs Day)

### Business Insights

- Peak Hours
- Off-Peak Hours
- Weekday vs Weekend Analysis
- Hourly Booking Distribution

---

## Dashboard 3 – Details

Detailed report page with drill-through functionality.

### Features

- Detailed Trip Records
- Drill-through Navigation
- Bookmark Navigation
- View Full Data
- Export Data

---

# 📈 Key Performance Indicators (KPIs)

| KPI | Description |
|------|-------------|
| Total Bookings | Total number of completed bookings |
| Total Booking Value | Total revenue generated |
| Average Booking Value | Average revenue per booking |
| Total Trip Distance | Total distance travelled |
| Average Trip Distance | Average distance per trip |
| Average Trip Time | Average trip duration |

---

# 📌 Business Questions Answered

- How many bookings were completed?
- How much revenue was generated?
- Which payment method is most popular?
- Which vehicle type generates the highest revenue?
- Which locations have the highest demand?
- Which day has maximum bookings?
- Which hour has the highest ride demand?
- Which trips cover the longest distance?
- What is the average trip duration?

---

# 🛠 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- SQL
- Microsoft Excel

---

# 📚 Power BI Features Used

- Data Cleaning
- Data Transformation
- Star Schema Data Model
- Relationships
- DAX Measures
- Dynamic Measure Selector
- Dynamic Titles
- Drill Through
- Bookmarks
- Tooltips
- Conditional Formatting
- Matrix Visuals
- Heatmaps
- KPI Cards
- Slicers
- Interactive Dashboards

---

# 📐 DAX Measures

Some of the DAX measures used include:

```DAX
Total Bookings =
COUNTROWS(Trips)
```

```DAX
Total Booking Value =
SUM(Trips[Booking_Value])
```

```DAX
Average Booking Value =
DIVIDE([Total Booking Value],[Total Bookings])
```

```DAX
Total Trip Distance =
SUM(Trips[Trip_Distance])
```

```DAX
Average Trip Distance =
AVERAGE(Trips[Trip_Distance])
```

```DAX
Average Trip Time =
AVERAGE(Trips[Trip_Duration])
```

Dynamic Measure Selection using:

- SWITCH()
- SELECTEDVALUE()
- CALCULATE()
- USERELATIONSHIP()
- DIVIDE()
- COUNTROWS()
- SUM()
- AVERAGE()
- MAX()

---

# 📂 Repository Structure

```
Uber-Trip-Analysis-Dashboard
│
├── Dataset
    │── Uber_Trip_Details.xlsx
│   ├── Location Table.xlsx

│
├── PowerBI
│   └── Uber_Trip_Analysis.pbix
│
├── Images
│   ├── Dashboard1.png
│   ├── Dashboard2.png
│   ├── Dashboard3.png
│   ├── DataModel.png
│
├── DAX
│   └── Uber Trip Analysis - DAX Measures.doc
│
├── Documentation
│   └── Business Requirement.pdf
│
└── README.md
```

---

# 📷 Dashboard Preview

## Dashboard 1 – Overview Analysis

![Dashboard 1]https://github.com/Manohar-Eedarada/Uber-Trip-Analysis-Dashboard/blob/main/DashBoard1.jpeg

---

## Dashboard 2 – Time Analysis

![Dashboard 2]https://github.com/Manohar-Eedarada/Uber-Trip-Analysis-Dashboard/blob/main/DashBoard2.jpeg

---

## Dashboard 3 – Details

![Dashboard 3]https://github.com/Manohar-Eedarada/Uber-Trip-Analysis-Dashboard/blob/main/DashBoard3.jpeg

# 🚀 Project Highlights

✔ Interactive Power BI Dashboard

✔ Dynamic KPI Selector

✔ Time-Based Analysis

✔ Vehicle Performance Analysis

✔ Revenue Analysis

✔ Location Intelligence

✔ Drill-through Reports

✔ Professional Dashboard Design

✔ Business Requirement Driven Development

✔ End-to-End Data Analytics Project

---

# 🎓 Skills Demonstrated

- Business Intelligence
- Data Analytics
- Data Visualization
- Dashboard Development
- DAX
- Power Query
- Data Modeling
- Business Analysis
- Problem Solving

---

# 📌 Conclusion

The **Uber Trip Analysis Dashboard** demonstrates how raw trip data can be transformed into meaningful business insights using **Power BI**. By leveraging interactive dashboards, dynamic DAX measures, and effective data modeling, the project enables users to analyze booking trends, revenue performance, trip efficiency, vehicle utilization, location-based demand, and time-based ride patterns.

Key Power BI features such as **Power Query, DAX, dynamic measure selection, drill-through, bookmarks, tooltips, slicers, and conditional formatting** were implemented to create an interactive and user-friendly reporting solution.

This project highlights my ability to:
- Build end-to-end Business Intelligence solutions.
- Design interactive and insightful Power BI dashboards.
- Perform data cleaning, transformation, and modeling.
- Develop dynamic DAX measures and KPIs.
- Translate business requirements into actionable analytics.
- Support data-driven decision-making through effective visualizations.

Overall, this project showcases my skills in **Power BI, DAX, Power Query, Excel, and Business Analytics**, making it a strong addition to my data analytics portfolio.


# 👨‍💻 Author

**Eedarada Manohar**

📧 Email: eedaradamanohar03@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/manohar-eedarada-035161253/

🌐 Portfolio: https://manohar-eedarada.github.io/Portfolio_website/


---


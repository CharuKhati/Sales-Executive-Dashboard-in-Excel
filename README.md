# 📊 Sales Executive Dashboard (Excel)

An interactive Excel dashboard that tracks and visualizes the performance of sales executives across multiple regions in India. Built using PivotTables, PivotCharts, Slicers, and formula-driven KPIs to enable real-time, single-click filtering and analysis.


🔍 Overview

This dashboard consolidates daily sales data for 27+ sales executives across 8 regions (Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, Surat) into a single, filterable view. It highlights top and bottom performers, tracks target achievement, and surfaces regional trends — all from raw daily transactional data.


✨ Features


Region Slicer — Filter the entire dashboard by region with a single click, powered by a slicer connected to 4 linked PivotTables via Report Connections.
KPI Calculations — Automated formulas for:

Target Hit % = Total Sales ÷ Target
Away From Target % = 1 − Target Hit %



Top 5 / Bottom 5 Performer Charts — Horizontal and vertical bar charts ranking sales executives by total sales.
Target Hit % Breakdown — Pie chart showing each executive's share of target achievement.
Away From Target Trend — Line chart tracking how far each executive is from hitting their target.
Single-Page Dashboard Layout — Clean, color-coded design built for at-a-glance executive reporting.



🗂️ Data Structure

Raw data includes the following fields per sales executive:

ColumnDescriptionEmp CodeUnique employee identifierSales ExecutiveEmployee nameRegionOne of 8 regionsDay1–Day5Daily sales figuresTotal SalesSum of Day1–Day5TargetFixed monthly sales target (500)Target Hit %Total Sales ÷ TargetAway From Target %1 − Target Hit %


🛠️ Tools & Techniques Used


Microsoft Excel (PivotTables, PivotCharts)
Slicers + Report Connections (one slicer controlling multiple PivotTables)
Formula-driven KPI calculations
Data visualization: bar charts, pie charts, line charts
Dashboard layout and formatting best practices


🚀 How to Use


Download or clone this repository.
Open Sales_Executive_Dashboard.xlsx in Microsoft Excel (desktop recommended for full slicer functionality).
Click any region in the slicer bar at the top to filter the entire dashboard.
Explore the Top 5 / Bottom 5 charts, Target Hit % pie chart, and Away From Target line chart — all update dynamically based on your selection.



📈 Key Insights Demonstrated


Identified top and bottom performing sales executives by region.
Highlighted executives furthest from their sales targets for management follow-up.
Enabled quick regional comparison without manual filtering of raw data.



🧠 Skills Demonstrated

Excel Data Visualization PivotTables Slicers Dashboard Design KPI Reporting Data Analysis

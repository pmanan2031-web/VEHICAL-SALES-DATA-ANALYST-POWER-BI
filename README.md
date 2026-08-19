🚗 Vehicle Sales Data Analysis Dashboard

<p align="center">
  <img src="assets/vehicle_sales_dashboard.gif" alt="Vehicle Sales Dashboard GIF" width="100%">
</p>

<p align="center">
  <b>Interactive Power BI Dashboard for Vehicle Sales Analysis</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/Data-Analysis-4F8CFF?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-2ECC71?style=for-the-badge">
</p>

📌 Project Overview

This project is an interactive Vehicle Sales Data Analysis Dashboard created in Power BI.

The dashboard helps users analyze vehicle sales using important business metrics and interactive filters. It provides insights into:

🚘 Total vehicles sold

💰 Total selling price

📊 Total MMR value

🛣️ Average odometer reading

📅 Vehicle sales by year

🚗 Vehicle body type analysis

⚙️ Transmission-based filtering

📈 Selling price by vehicle model

👥 Sales count by seller

🗺️ State-wise vehicle analysis

📋 Make, model and MMR summary

🎬 Dashboard GIF Preview

<p align="center">
  <img src="assets/vehicle_sales_dashboard.gif" alt="Vehicle Sales Dashboard Demo" width="100%">
</p>

The GIF demonstrates the main dashboard layout and interactive analysis flow.

📸 Dashboard Preview

<p align="center">
  <img src="assets/dashboard_preview.png" alt="Vehicle Sales Dashboard Preview" width="100%">
</p>

✨ Dashboard Features

Feature

Description

📊 KPI Cards

Shows important metrics such as Total Sales, Total Price, Total MMR and Average Odometer

📅 Year Filter

Filters the dashboard based on vehicle year

🚙 Body Filter

Analyzes different vehicle body types

⚙️ Transmission Filter

Filters data based on transmission type

📈 Model Analysis

Compares selling price across vehicle models

🥧 Seller Analysis

Shows vehicle sales count by seller

🗺️ State Analysis

Visualizes vehicle-related data geographically

📋 Summary Table

Displays make, model and MMR-related information

📊 Visualizations Used

1️⃣ KPI Cards

The dashboard contains four important KPI cards:

Total Vehicles Sold
Total Price
Total MMR
Average Odometer

These KPIs provide a quick summary of the complete vehicle sales dataset.

2️⃣ Sales Price by Model

A 100% Stacked Bar Chart is used to compare vehicle selling prices by different models.

This helps answer:

Which vehicle model has higher sales value?

Which model contributes more to the total selling price?

How does selling price vary across models?

3️⃣ Count Sales by Seller

A Pie Chart is used to visualize vehicle sales distribution by seller.

This helps identify:

Top contributing sellers

Sales distribution

Seller-wise performance

4️⃣ State-Wise Analysis

A Map Visualization displays vehicle data according to different states.

This makes geographical analysis easier and helps identify locations present in the dataset.

5️⃣ Make, Model & MMR Table

A Table Visualization displays:

Make
Model
Total MMR

This provides a detailed summary of vehicle brands and models.

🎛️ Interactive Filters

The Power BI dashboard contains the following slicers:

📅 Year

Filter data based on vehicle manufacturing/sales year.

🚘 Body

Filter vehicles based on body type.

⚙️ Transmission

Filter vehicles based on transmission type.

All visualizations update interactively when a filter is selected.

🧮 DAX Measures Used

The dashboard uses important calculated measures such as:

Total Sales = SUM(Table1[sellingprice])

Total Price = SUM(Table1[sellingprice])

Total MMR = SUM(Table1[mmr])

Average Odometer = AVERAGE(Table1[odometer])

The exact measure names in the PBIX file are represented in the dashboard as total sales, total price, total mmr, and avodmeter.

🛠️ Tools & Technologies

Tool

Purpose

🟡 Power BI

Dashboard development and visualization

📊 DAX

Creating calculated measures

🧹 Power Query

Data cleaning and transformation

📈 Data Visualization

Business insights and analysis

🔄 Project Workflow

flowchart LR
    A[📁 Vehicle Sales Data] --> B[🧹 Data Cleaning]
    B --> C[🔧 Data Transformation]
    C --> D[🧮 DAX Measures]
    D --> E[📊 Dashboard Creation]
    E --> F[🎛️ Add Slicers]
    F --> G[📈 Business Insights]

📂 Project Structure

Vehicle-Sales-PowerBI/
│
├── pra.pbix
├── README.md
│
└── assets/
    ├── vehicle_sales_dashboard.gif
    └── dashboard_preview.png

🚀 How to Use This Project

Step 1: Download the Project

Download or clone this repository.

Step 2: Open Power BI Desktop

Open:

pra.pbix

Step 3: Explore the Dashboard

Use the slicers for:

Year

Body

Transmission

Step 4: Analyze the Results

Click on different charts and visuals to interact with the data and explore vehicle sales insights.

📌 Key Insights You Can Explore

Which vehicle models generate higher selling prices?

Which sellers contribute the most sales?

How are vehicles distributed across states?

How does transmission affect sales?

Which body types are present in the dataset?

How does vehicle year influence the analysis?

What is the average odometer reading?

🖼️ Suggested Repository Images

For an even better GitHub project presentation, you can add screenshots of:

🏠 Main Dashboard

📊 Sales Price by Model

🥧 Seller Analysis

🗺️ State-Wise Map

🎛️ Slicers and Filters

🎬 Dashboard GIF

Recommended folder:

assets/
├── dashboard_main.png
├── sales_by_model.png
├── seller_analysis.png
├── state_analysis.png
├── filters.png
└── vehicle_sales_dashboard.gif

🌟 Future Improvements

Add monthly and quarterly sales trends

Add profit and cost analysis

Create Top N vehicle models

Add seller ranking

Add more advanced DAX calculations

Add drill-through pages

Add forecasting and trend analysis

👨‍💻 Author

Manan

<p align="center">
  ⭐ If you like this project, consider giving the repository a star!
</p>

<p align="center">
  Made with ❤️ using Power BI
</p>

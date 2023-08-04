# Supplier-Quality-Analysis

Welcome to the Supplier Quality Analysis dashboard! This Power BI project provides a comprehensive overview of suppliers' performance across key metrics, enabling us to monitor their quality and identify areas for improvement. By analyzing data related to Total Defectives, Type of Defects, Defects Outcome, Downtime, and more, we can work collaboratively with our suppliers to ensure they meet our quality standards consistently. The analysis provides insights into supplier performance, defect rates, and trends over time.

The dashboard is designed to facilitate data-driven decision-making and enhance overall supply chain efficiency by fostering a culture of continuous improvement.

<br>
<p align="center">
  <a href="https://powerbi.microsoft.com/en-in/">
    <img src="https://img.shields.io/badge/Made%20with-Power%20BI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=white">
  </a>
</p>
<br>


##  Files

The data used for this analysis includes information on supplier names, product details, defects, delivery times, and other relevant metrics. The dataset is preprocessed and transformed to make it suitable for Power BI analysis.

<br>

| Files/Folder| Description |
| ------------- | ------------- |
| **supplier_quality_analysis_data.xlsx** | This excel file contains 2017-2021 data including details of orders, category, defect type, material type, location, etc. |
| **supplier_quality_analysis_dashboard.pbix** | This file contains final dashboards created with Microsoft Power BI |
<br>
<p align="center">
   <img src="https://camo.githubusercontent.com/e8dd5ec0043e31dbce1d2bef237bb4aba9e30d424356808e358d656134fd3739/68747470733a2f2f68656c6c6f6675747572652e6f72616e67652e636f6d2f6170702f75706c6f6164732f323031372f31302f4d65746965725f4c6f67697374696369656e2e676966" width="400" >
</p>

## Methodology

1. Connect PowerBI to Excel Data to Load and Transform data in PowerQuery

2. Data Modelling to build Relations between the tables to establish star schema.

3. Create calculated columns and key DAX measures

4. Design an interactive report to analyze and visualize the data

5. Visuals used: Matrix, Slicers, Line Charts, Tree Maps, KPIs, Cards (Single and Multi-row), Gauge, Map, Clustered Bar chart, donut charts, Line and Clustered Column Charts, Forecasting analysis.

6. Used Bookmarks and Selection for layering of visuals and then use them in Actions as per suitability.

7. Used Drill-through filters, page level, report level and Visual level filters.
    
8. Created a interactive and dynamic dashboard at the end.

## Power BI Reports

The project includes the following Power BI reports:

#### Overview
The Overview page provides a high-level summary of our suppliers' performance, showcasing key KPIs and metrics at a glance. It includes visualizations that reveal trends, outliers, and areas of concern, helping us quickly assess the overall quality status.

#### Top/Bottom Analysis
On this page, we perform a comprehensive Top/Bottom analysis of our suppliers based on various quality metrics. This analysis allows us to identify our top-performing suppliers, as well as those who may require additional attention or support to improve their performance.

#### Downtime Analysis
The Downtime Analysis page focuses on understanding the factors contributing to downtime in our supply chain. By analyzing data related to downtime events and their root causes, we can develop strategies to minimize disruptions and optimize productivity.

## Insights
The Insights page presents in-depth findings and actionable insights derived from the data analysis. We discuss trends, patterns, and opportunities for improvement, which will guide our decision-making processes and quality improvement initiatives.

1. Overall downtime for a year has been increased by more than 3 times since 2017.

2. Supplier 4 lead to highest downtime of 300+ hours between 2017-2021 with 8420 defects
quantity which is about 2.75% of total quantity.

3. Delivery Logistics category has 69.5% defects outcome as "Reject", which also has maximum
contribution in overall downtime.


## Preview

Here's a preview of the Supplier Quality Analysis Dashboard:

Overview:
<p align="center">
   <img src="https://github.com/abhishekm9396/Supplier-Quality-Analysis/assets/126942017/1a311188-02b2-4d31-9acf-a9c470135e90" width="700" >
</p>
Schema:
<p align="center">
   <img src="https://github.com/abhishekm9396/Supplier-Quality-Analysis/assets/126942017/dc58146a-776d-4e88-809f-92057c94839b" width="700" >
</p>

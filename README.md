# Opportunity Management & Performance Dashboard

## Project Overview:

This repository focuses on analyzing and visualizing **Opportunity Management** data to track performance, revenue, and team efficiency across different market segments. The data, extracted from **Smartsheet**, is processed in **Excel** with pivot tables and slicers, and further visualized using **Power BI** to create an interactive dashboard showcasing team performance, opportunity influx, revenue trends, and sector profitability.

---
## Screenshots:
![image](https://github.com/user-attachments/assets/4cedbf79-b828-47fa-9b28-fe85ab1398c0)
![image](https://github.com/user-attachments/assets/f33fcd9e-7f4f-49ed-90a6-a8edb88e2d17)
![image](https://github.com/user-attachments/assets/0d443dc7-70a8-4265-894d-c2387eac332f)

## Tools & Technologies:
- **Smartsheet**: Data extraction source.
- **Excel**: Pivot table analysis with slicers for interactive filtering.
- **Power BI**: Advanced data visualizations including charts, cards, and timelines.
---
## Data Structure:

### Key Headers (Fields):
- **Opportunity Number**: Unique identifier for each opportunity.
- **Customer Name**: Name of the client involved in the opportunity.
- **Request Type**: Type of service request (e.g., GSCaaS ISA).
- **Partner Required**: Indicates whether a partner is needed.
- **Engagement Date**: Date of customer engagement.
- **Status**: Current status of the opportunity (e.g., Pending, Closed).
- **Service Groups**: Service departments involved in the opportunity.
- **Revenue Fields**: 
  - Opportunity Revenue
  - Opportunity Margin
  - Hardware Revenue
  - Services Revenue
  - PMO Revenue

These fields, along with others such as **Country of Origin**, **Market Segment**, **SLA Timer**, and **Solution Date**, form the basis for tracking and analysis.

---

## Excel Data Analysis:

### Key Pivot Tables:
- **Team Performance**: Shows how each team member is performing based on completed opportunities and overall revenue generated.
- **Opportunity Influx**: Analyzes the number of new opportunities by date, request type, and engagement status.
- **Revenue by Sector**: Highlights which sectors (e.g., Hardware, Services, PMO) are generating the most revenue.
- **Profitability by Sector**: Identifies the sectors with the highest profit margins.

### Slicers:
- **Timeline Slicer**: Filters the data by engagement date.
- **Category Slicers**: Enables filtering by opportunity status, customer, and market segment.

The analysis enables in-depth insights into **opportunity trends**, **sector-wise revenue**, and **team efficiency**.

---

## Power BI Visualizations:

Power BI is used to build an interactive dashboard that provides key metrics and insights into the performance and management of opportunities.

### Visuals Used:
- **Clustered Bar Chart**: Displays opportunity type vs. total revenue to showcase the most profitable opportunity categories.
- **Card Visuals**: Highlights key metrics such as total revenue, opportunity count, and team performance.
- **Funnel Chart**: Visualizes the flow of opportunities through different stages from "Engaged" to "Closed" or "Lost."
- **Stacked Area Chart**: Tracks the trend of opportunity influx and revenue over time.
- **Pie Graph**: Breaks down opportunities by sector (e.g., Hardware, Services) to show the contribution of each sector to total revenue.

These visualizations offer a dynamic way to filter data by engagement date, status, and team member, allowing decision-makers to make informed choices.
---

## Repository Structure:

```bash
Opportunity-Management-Dashboard/
│
├── data/                             # Raw and processed data files
│   ├── Opportunities_Smartsheet.csv  # Extracted data from Smartsheet
│   └── Opportunity_Analysis.xlsx     # Excel analysis with pivot tables
├── powerbi/                          # Power BI dashboard file (.pbix)
├── README.md                         # Project overview and instructions
├── assets/                           # Images used in the README
│   ├── excel-pivot-example.png       # Screenshot of Excel pivot table
│   └── powerbi-dashboard-example.png # Screenshot of Power BI dashboard

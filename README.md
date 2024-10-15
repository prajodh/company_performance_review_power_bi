![image](https://github.com/user-attachments/assets/66b75d81-7571-4529-8e24-8410403b18c2)

# Plant Co Sales Performance Review Report

This repository contains a Power BI report analyzing the performance of Plant Co Sales. The report focuses on key business metrics such as gross profit percentage, sales, and quantity, offering comparisons between Year to Date (YTD) and Prior Year to Date (PYTD). The data visualization empowers stakeholders with insights into the company’s growth, profitability, and trends.

## Project Overview

### Key Features:
- **Dynamic reporting using DAX**: Utilized advanced DAX expressions to create measures for Year to Date (YTD) and Prior Year to Date (PYTD) comparisons.
- **Switch-based visualizations**: Implemented switch logic to allow easy toggling between different metrics (gross profit percentage, sales, quantity) for both YTD and PYTD data.
- **Data integration**: Integrated data from multiple sources such as Excel and SQL databases to provide a comprehensive analysis of Plant Co Sales' performance.
- **Interactive Visualizations**: Designed visually appealing and interactive reports with:
  - **Treemap**: For hierarchical data visualization of sales across different categories.
  - **ArcGIS Maps**: To visualize geographic distribution of sales.
  - **KPI visual**: To showcase key performance indicators like profit margins and year-on-year growth.
  - **Line and Column Clustered Charts**: For time-series analysis of sales, gross profit, and quantities.

### Measures and Metrics:
- **Gross Profit Percentage**
- **Sales**
- **Quantity Sold**
- **Year to Date (YTD) Performance**
- **Prior Year to Date (PYTD) Performance**

### Visualizations:
- **Treemap**: Visualizes hierarchical data for product categories and their contribution to total sales.
- **ArcGIS Map**: Displays the geographic sales distribution, providing insight into regional performance.
- **KPI Visuals**: Shows critical KPIs such as total sales and gross profit percentage, allowing management to track progress towards business goals.
- **Line and Column Clustered Chart**: Combines line and column charts to compare historical performance and identify trends over time.

## Technologies Used
- **Power BI**: Main platform for data modeling and visualization.
- **DAX (Data Analysis Expressions)**: Used for creating calculated columns and measures.
- **Excel & SQL**: For data integration and preparation.
- **ArcGIS**: For mapping and geographic analysis.

## How to Use
1. **Clone the repository**:  
   `git clone https://github.com/prajodh/PowerBI-PlantCoSales-Performance-Review.git`
   
2. **Open the Power BI report**:  
   Load the `.pbix` file in Power BI Desktop.

3. **Data Integration**:  
   Ensure that the linked SQL database and Excel files are available and properly mapped to the report’s data source settings.

4. **Interact with the report**:  
   - Use the slicers to filter data by year or region.
   - Switch between KPIs to compare sales, quantity, and gross profit over YTD and PYTD.
   - Drill down into specific categories or regions for detailed insights.

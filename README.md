# DataModeler-powerbi
Power BI dashboard project showcasing data cleaning, data modeling, and interactive visualizations to analyze sales performance and key business metrics.

Power BI Dashboard Project
  
 Overview
This project showcases the complete workflow of data analysis using Power BI.
It focuses on converting raw data into meaningful insights through data cleaning, transformation, modeling, and visualization.
The final dashboard presents key metrics such as revenue, average revenue, and return percentage to help understand business performance.

  Objectives
Perform data cleaning using Power Query
Transform and structure raw data
Build a proper data model with relationships
Create calculated measures using DAX
Design an interactive and user-friendly dashboard
Generate insights for decision-making

Tools & Technologies
Power BI
Power Query Editor
DAX (Data Analysis Expressions)
Excel / CSV dataset

 Project File
DataModeler.pbix – Contains data model, transformations, and dashboard

 Project Workflow
1. Data Import
Loaded dataset into Power BI
Verified structure and columns
2. Data Cleaning (Power Query)
Removed null and duplicate values
Renamed columns for clarity
Changed data types (text, number, date)
Filtered unnecessary data
3. Data Transformation
Created new calculated columns
Split and merged fields where required
Standardized formats for consistency
4. Data Modeling
Created relationships between tables
Designed fact and dimension tables
Ensured proper schema for analysis
5. DAX Calculations

Created measures for key metrics:
Avg_Revenue = 
DIVIDE(
    SUM('Sales_Fact - Sheet1'[Revenue]),
    DISTINCTCOUNT('Sales_Fact - Sheet1'[SalesID])
)

 Dashboard Features
KPI Cards for:
Total Revenue
Average Revenue
Return Percentage
Pie Chart for category distribution
Interactive slicers/filters
Simple and clean layout for better readability

 Key Insights
A few categories contribute the majority of revenue
Return percentage highlights areas with potential loss
Some segments perform better than others
The dashboard helps identify trends and patterns quickly

 How to Use
Download the .pbix file from this repository
Open it using Power BI Desktop
Click on Refresh to update data (if required)
Use filters and visuals to explore insights

 Future Improvements
Add more advanced visuals (bar charts, trend analysis)
Improve dashboard design and user experience
Include real-time or larger datasets
Add forecasting and predictive analysis
 
 Author
Nandini Rajput
B.Tech CSE Student | Aspiring Data Analyst


# Visualizing Road Accident Data for Safer Roads

![Image](https://media.istockphoto.com/id/1349610019/vector/car-accident-with-drivers-man-and-woman-vector-illustration.jpg?s=612x612&w=0&k=20&c=w111hIV0cUSdQX70XyGnvJdOnterFwe8PWqI18cfT1I=)

**Project Overview:**

This data analysis project aims to create an Excel dashboard using the "Road Accident Dataset" sourced from Kaggle. The project involves five main steps: Data Cleaning, Data Processing, Data Analysis, Data Visualization, and creating the final Dashboard. 
The objective is to provide insights into road accidents for the years 2021 and 2022, focusing on various key performance indicators (KPIs) and their relationships with different factors.

**Stakeholders:**

- Ministry of Transport
- Road Transport Department
- Police Force
- Emergency Services Department
- Road Safety Corps
- Transport Operators
- Traffic Management Agencies
- Public
- Media

**Data Description:**

- Dataset Source: [Kaggle](https://www.kaggle.com/)
- Dataset Name: [Road Accident Dataset](https://github.com/krvipin15/Data-Analytics-Project/blob/1aca00cff98358b3f14aec55f8c7785c47e20a37/Excel-Projects/Road-Accident-Analysis/Dataset_%26_Dashboard.xlsx)
- Data Size: 3.07 Million rows and 21 columns

**Key Performance Indicators (KPIs):**

![Data Analysis Sheet](https://github.com/jagritsharma24/road-accident-analysis/blob/main/Images/Road_Accident_Analysis_img.png?raw=true)

1. Primary KPI - Total Casualties after the accident: This KPI will provide an overview of the total number of casualties that occurred after each road accident.

2. Primary KPIs with respect to accident severity and vehicle type:
   - Total Casualties & Percentage of total by accident severity: This KPI will show the total casualties and their percentage concerning different accident severity levels.
   - Maximum casualties by type of vehicle: This KPI will identify the type of vehicle involved in accidents resulting in the highest number of casualties.

3. Secondary KPI - Total Casualties with respect to vehicle type: This KPI will show the total number of casualties based on the type of vehicles involved in accidents.

4. Monthly trend comparison of casualties for the Current Year and Previous Year: This KPI will display the monthly comparison of casualties between the current year (2022) and the previous year (2021).

5. Maximum casualties by Road Type: This KPI will identify the road types where the maximum number of casualties occurred.

6. Distribution of total casualties by Road Surface: This KPI will showcase the distribution of total casualties based on different road surface conditions.

7. Relation between Casualties by Area/Location & by Day/Night: This KPI will analyze the relationship between casualties and factors like area/location and day/night conditions.

Here's a summarized version of the steps to create the Road Accident Dashboard:

**Steps to create the Road Accident Dashboard:**

1. Data Cleaning:
+ Adjust the first column for text underneath.
+ Apply filters to remove blanks, nulls, and duplicates in the primary key column.
+ Check for spelling mistakes using filters.
+ Handle blank values in specific columns.

2. Data Processing:
+ Add new columns for Month and Year.
+ Use formulas to extract month and year from the Accident Date column.

3. Data Analysis:
+ Create a Pivot Table to calculate Total Casualties by Accident Severity.
+ Calculate percentages of Total Casualties for each Accident Severity.
+ Create a donut chart to visualize the distribution of casualties by Accident Severity.
+ Use a Timeline filter to analyze data based on date.

4. Secondary KPIs:
+ Create a Pivot Table to calculate Total Casualties by Vehicle Type.
+ Use calculated items to combine different vehicle types.
+ Create a table for Car Casualties.

5. Data Visualization (Dashboard):
+ Create a new sheet named "Dashboard"
+ Customize the appearance by removing gridlines and adding background colors.
+ Use shapes and text boxes to create the layout of the dashboard.
+ Copy and paste charts and tables from other sheets to the dashboard.
+ Format the dashboard elements for better visualization.

**Road Accident Dashboard:**

![Dashboard](https://github.com/jagritsharma24/road-accident-analysis/blob/main/Images/Road_Accident_Dashboard_img.png?raw=true)

**Conclusion:**

This data analysis project will provide valuable insights into road accidents, highlighting crucial KPIs and their associations with various factors. 
The Excel dashboard will facilitate the stakeholders in understanding the patterns, trends, and areas of concern related to road safety for the years 2021 and 2022.

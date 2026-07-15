# HOTEL-STAY-ANALYSIS
**CAPSTONE PROJECT – HOTEL STAY ANALYSIS | Power BI & SQL Server**

**Domain & Data Overview – Hospitality / Hotel Management**

This project is based on the Hospitality domain, analysing operational data 
from 15 hotels with 13000+ records. The dashboard provides insights into customer occupancy, revenue, 
profit, employee staffing, and hotel performance. It helps management monitor financial trends, optimize 
workforce planning, and improve business decisions. Designed an optimized data model and created 
advanced DAX measures to track occupancy, customer stays, revenue, employee wages, and profitability 
trends.

**Key business areas covered:** Check-ins (Night Stays) & Revenue Analytics, Employee Overview, 
Customer Analytics, Workforce Utilization, Trend Analysis and Expenses & Profitability Analysis.

- Extracted, transformed, and loaded (ETL) data from SQL Server to build a clean and structured 
dataset for accurate and reliable analysis and reporting. 
- Designed a data model (Star schema) with well-defined relationships so different datasets 
(Customers, Hotels, Employees) flowed smoothly and connected correctly. 
- Used DAX formulas to create Calculated Columns that support reporting and build complex 
calculations (Measures) using DAX. 
- Defined business KPIs like Check-ins, Check-outs, Customers Staying (on a particular date), and 
Employees on duty (on a particular date) through complex DAX calculations. 
- Created separate pages for Overview, Revenue & Expenses, Profit, Trend Analysis, Employees and 
Customer insights to ensure the detailed analysis and insights. 
- Optimised the report pages with well-defined Slicer visuals (Hotel Name, Date Range, ...) to filter the 
report for better analytical purposes. 
- Enabled Drill-through option to navigate to detailed hotel insights. 
- Using buttons with Numeric Parameter and Filter table enabled a dynamically changing Top & 
Bottom Revenue in a “Revenue by Hotels” visual. 
- Used Bookmarks and Buttons to create sub-pages within a single report page and to toggle the 
Filter pane in report pages. 
- Customized report visuals with brand aligned themes, intuitive UI design, Interactive slicers, and 
dynamic tooltips to improve user engagement. 
- Used Buttons to implement a Page navigation in a report to ensure the improved user experience. 
- Implemented Row-Level Security (RLS) to ensure secure and role-based (Hotel) data visibility. 
- Improved report performance by using Bookmarks and Buttons (Visual switch), optimizing queries, 
and speeding up load times. 
- Used Field Parameters to enable dynamic measure/dimension switching within a single visual, 
reducing the number of visuals on the report page and improving rendering performance. 
- Used SQL Server for end-to-end data validation at every stage of the report development, ensuring 
consistency and accuracy between source data and Power BI report figures.
- Published report in Power BI Service workspace and built a dashboard consolidating key visuals to 
provide with a real-time view of business performance.

## 1 Home/Landing Page
![Home Page](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Home%20or%20Landing%20Page.png)

## 2 Operational Overview
### Arrivals & Departures
![Sub-page 1](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Operational%20Overview%20-%20Arrivals%20%26%20Depatures.png)
### Occupancy
![Sub-page 2](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Operational%20Overview%20-%20Occupancy.png)

## 3 Employee Overview
![Employee Overview](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Employee%20Overview.png)

## 4 Revenue & Expenses
### Revenue
![Revenue](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Revenue%20%26%20Expenses%20-%20Revenue%20I.png)
### Expenses
![Expenses](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Revenue%20%26%20Expenses%20-%20Expenses.png)

## 5 Profitability Analysis
![Profitability Analysis](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Profitability%20Analysis.png)

## 6 Trend Analysis
![Trend Analysis](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Trend%20Analysis%20-%20I.png)

## 7 Staffing Status
![Staffing Status](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Staffing%20Status.png)

## 8 Customer Insights
![Customer Insights](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Customer%20Insights.png)

## Drill-Through Page
![Drill-Through](https://github.com/SuriyaShines/HOTEL-STAY-ANALYSIS/blob/main/Drill-Through%20Page.png)

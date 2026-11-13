# Harshul-Ecommerce-Sales-PowerBI-Dashboard
End-to-end interactive Power BI sales dashboard analyzing Harshul Ecommerce performance across states, product categories, and payment modes. Built using Power Query for ETL, relational data modeling, and custom DAX measures to track revenue, profit trends, and order volume.




## Project Overview
An end-to-end interactive Business Intelligence dashboard built in Microsoft Power BI to track, analyze, and visualize online sales data for Harshul Ecommerce. The project transforms raw transactional datasets into actionable insights across regional sales, customer payment behavior, seasonal profitability, and product performance.

## Key Performance Indicators (KPIs)
* **Total Sales Amount:** 438K
* **Total Profit:** 37K
* **Total Quantity Sold:** 5,615 units
* **Average Order Value (AOV):** 121K (Sum of AOV)

## Project Learnings & Technical Implementation
* **Data Extraction & Cleaning (Power Query):** Imported raw `Orders` and `Details` CSV datasets, handled missing values, standardized data types, and extracted date hierarchies (Month, Quarter).
* **Data Modeling & Connections:** Built relational connections and joined multi-table datasets (`Orders` and `Details`) using `Order ID` (One-to-Many relationship) to enable seamless cross-filtering.
* **DAX & Calculations:** Engineered custom calculated columns and DAX measures to manipulate data, compute profit margins, and enable user-driven parameters for dynamic reporting.
* **Interactive Controls:** Implemented custom filters, State dropdowns, and Quarter slicers (`Qtr 1` – `Qtr 4`) to allow interactive drill-down across the report.
* **Data Visualizations Used:** Designed a comprehensive visual layout utilizing **KPI Cards**, **Stacked Bar Charts**, **Stacked Column Charts**, **Donut Charts**, **Pie Charts**, **Area Charts**, **Line Charts**, and **Interactive Slicers**.

## Key Business Insights
* **Regional Performance:** **Maharashtra** and **Madhya Pradesh** lead all states in total sales volume.
* **Seasonal Profitability:** Profit peaks sharply in **November** (driven by Q4 festive demand), while **July** and **September** saw noticeable profit dips.
* **Category & Sub-Category Mix:** **Clothing** accounts for the highest share of units sold (**62%**), whereas **Printers** and **Bookcases** generate the highest net profit among sub-categories.
* **Customer Payment Trends:** **Cash on Delivery (COD - 44%)** and **UPI (21%)** are the most preferred payment modes, followed by Credit Cards, Debit Cards, and EMI.

## Tools & Technologies
* **Microsoft Power BI Desktop** (Power Query, Data Modeling, DAX, Report Design)
* **Microsoft Excel / CSV** (Raw Data Source)

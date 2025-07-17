📊 Dynamic Retail Dashboard Project

🚀 Objective
The goal of this project is to present meaningful business insights using interactive dashboards built on retail order data. The analysis helps Walmart understand key metrics and trends to support leadership decisions. This project includes sales, profitability, returns, and customer segmentation insights.

📁 Dataset Description
The project is based on three datasets extracted from an Excel workbook:

1. Orders
Column	Description
Order ID	Unique ID for each transaction
Returned	Whether the order was returned
Order Date / Ship Date	Purchase and shipment timeline
Customer Info	Customer ID, Name, Segment
Region Info	City, State, Country, Region, Market
Product Info	Category, Sub-Category, Product Name
Metrics	Sales, Quantity, Discount, Profit, Shipping Cost, Priority

2. Returns
Column	Description
Order ID	ID of returned order
Market	Market (LATAM, EU, etc.)
Returned	Yes/No flag for return status

3. People
Column	Description
Person	Sales rep responsible
Region	Region under their control

📌 Problem Statements
✅ 1. Key Performance Indicators (KPIs)

Total Sales

Total Profit

Total Returns

Profit Margin %

Average Order Value
<img width="1436" height="166" alt="image" src="https://github.com/user-attachments/assets/b544ef3b-b7c8-4ff9-8c8e-27bd65d1745b" />

📉 2. Sales and Profit Analysis

Month-over-month and year-over-year trends

Profitability by Market and Region
<img width="786" height="517" alt="image" src="https://github.com/user-attachments/assets/a7d09656-a04a-44d8-855b-310fd9005620" />

📦 3. Category-Wise Profit

Deep-dive into product performance by category and sub-category
Highlight underperforming products

<img width="717" height="515" alt="image" src="https://github.com/user-attachments/assets/2f5f5814-78ab-4f53-825e-4e44fc6e0f8b" />

👥 4. Segment-Wise Sales Share (%)

Compare sales among Consumer, Corporate, and Home Office segments

<img width="713" height="513" alt="image" src="https://github.com/user-attachments/assets/e0adca21-6806-47b5-b18d-74244b30f1f7" />

🌍 5. Sales by Country

Geo-level analysis of sales trends
Identify countries with high/low profitability

<img width="588" height="339" alt="image" src="https://github.com/user-attachments/assets/e6c7b843-ee62-42dd-8f84-ff5e0edd3956" />

🔍 Steps to Solve

Data Cleaning

Convert date columns to proper datetime format

Remove nulls and duplicates

Standardize categorical fields

Data Merging

Join Orders with Returns and People based on keys like Order ID and Region

Data Analysis

Perform EDA using pivot tables and charts in Excel or Power BI

Calculate KPIs and segment breakdowns

Use conditional formatting to highlight key trends

Dashboard Creation

Use slicers for interactive filtering (Region, Category, Segment, etc.)

Use visual elements: Bar charts, Maps, Line graphs, KPIs

Make dashboard dynamic with auto-updating visuals

Insights Summary

Write observations below the dashboard or in a PowerPoint

Highlight recommendations: focus on profitable categories, reduce return rates, etc.

📸 Dashboard Preview
<img width="1129" height="584" alt="image" src="https://github.com/user-attachments/assets/35d29b1b-b3c3-49d5-b25b-3a5b7e35cabf" />


🛠 Tools Used

Microsoft Excel
Pivot Tables, Slicers, Conditional Formatting
Data Cleaning and Merging techniques

👤 Author
Your Name:David.M
Contact: davidmmsd@gmail.com

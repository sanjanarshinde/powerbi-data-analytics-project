# ShopNest Store – Power BI Capstone Project

An end-to-end Power BI dashboard built on a Brazilian retail e-commerce dataset. The project covers data cleaning, data modelling, DAX measures and interactive visuals that answer eight business questions about sales, delivery performance, payments, customer ratings and revenue growth.

## Dataset
Nine related tables: orders, order items, order payments, order reviews, products, customers, sellers, product category translations and geolocation. A dedicated date table (`Dim_Date`) was added for time analysis.

## What's in the Dashboard
- Main Dashboard page with all 8 visuals on one page
- 4 KPI cards: Total Sales, Total Orders, Total Revenue, Delayed Orders
- 3 slicers: Year, State, Product Category
- Drill-through page (Order Detail): from any month in the delayed vs on-time chart to the individual order records
- Detail pages: a full-screen page for each question

## Business Questions Answered
| # | Question | Visual |
| 1 | Top 10 product categories by total sales | Bar chart |
| 2 | Delayed orders in each category | Bar chart |
| 3 | Monthly delayed vs on-time orders (with drill-through) | Clustered column chart |
| 4 | Most used payment methods | Pie chart |
| 5 | Top 10 and bottom 10 rated products (min. 5 reviews) | Bar charts |
| 6 | State-wise sales performance | Column chart |
| 7 | Quarterly seasonal sales patterns | Line chart |
| 8 | Total revenue and yearly trend | Line chart + KPI card |

## Key Findings
- Total sales: $13.22M. Total revenue (sales + freight): $15.42M.
- Top categories:Health_Beauty, Watches_Gifts and Bed_Bath_Table.
- Regional concentration: São Paulo (SP) generates about 38% of total sales, far ahead of Rio de Janeiro and Minas Gerais.
- Payments: about 75% of payments are made by credit card, followed by boleto at about 19%.
- Delivery: delayed orders are a small share of the total, with spikes in November 2017 and March 2018.
- Growth: revenue grew from 2016 to 2018. 2016 and 2018 are partial years, so a full seasonal pattern can't be confirmed from this dataset.

## DAX Measures Used
Total Sales, Total Freight, Total Revenue, Total Orders, Delayed Orders, Order Count, Payment Count, Revenue YoY %, Avg Product Rating, Review Count, and rank measures for the top and bottom rated products. A calculated column, Delivery Status, classifies each order as On Time or Delayed.

## Files
| File | Description |
| `CAPSTONE_PROJECT.pbix` | Power BI dashboard (open with Power BI Desktop) |
| `ShopNest_Capstone_Project_Report.docx` | Project report with the insights for each question |


## Tools
Power BI Desktop · DAX · Power Query

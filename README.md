# Sales & Revenue Analysis Dashboard

## Project Overview
An analysis of sales transactions using Microsoft Power BI and Excel. The project explores revenue trends, product performance, regional sales, and customer segments.

## Dataset
- 9,800 transaction rows
- 18 original columns
- Main fields: Order Date, Order ID, Customer ID, Region, Category, Sub-Category, Product Name, and Sales.

## Key KPIs
- Total Revenue: $2,261,536.78
- Total Orders: 4,922
- Total Customers: 793
- Average Order Value: $459.48
- Unique Products: 1,861

## Dashboard Visuals
- Monthly revenue trend
- Revenue by region
- Revenue by category
- Top 10 products by revenue
- Revenue by customer segment

## Files
The prepared assignment package includes:
- `Sales_Revenue_Analysis_Assignment.xlsx` — workbook with source data, summary tables, charts, and DAX formulas.
- `train.csv` — original dataset.
- `Sales_Revenue_Analysis_Report.pdf` — project report.
- `PowerBI_DAX_Measures.txt` — DAX measures for Power BI.

## Open in Power BI
1. Open Power BI Desktop.
2. Select **Get Data → Excel workbook**.
3. Import the `Sales Data` sheet from the Excel workbook.
4. Create the measures using `PowerBI_DAX_Measures.txt`.
5. Add slicers for Order Date, Region, and Category.
6. Save the interactive report as `Sales_Revenue_Analysis.pbix`.

## Data Notes
The supplied dataset does not include quantity or profit fields. Therefore, this project does not calculate total quantity or profit. The date columns are interpreted in day-first format.

## Conclusion
The project summarizes sales performance and helps identify revenue trends, high-performing products, regional contributions, and customer-segment performance.

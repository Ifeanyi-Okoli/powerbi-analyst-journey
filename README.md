# Retail Sales Dashboard - Power BI

![Power BI Retail Sales Dashboard Screenshot]
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/84152b67-f434-449d-9ead-c632b8178862" />

## Project Objective

This Power BI dashboard analyzes retail sales data from multiple stores to provide actionable insights for business decision-making. The main goals are:

- Track overall sales performance (total revenue, units sold)
- Identify top-performing stores and product categories
- Support data-driven decisions on inventory, promotions, and store operations

Built as a personal data visualization project to demonstrate Power BI skills in data cleaning, modeling, DAX measures, and interactive reporting.

## Dataset Description

- **Source**: Sample retail sales data (Excel file: `retail_sales.xlsx`)
- **Time period**: January 2024 (sample dates: 01/01/2024 – 01/02/2024)
- **Stores**: London, Reading
- **Key columns**:
  - **Date** → Transaction date
  - **Store** → Location of sale (e.g., London, Reading)
  - **Product** → Item sold (e.g., Milk, Bread, Eggs)
  - **Category** → Product group (e.g., Dairy, Bakery)
  - **Units Sold** → Quantity sold
  - **Revenue** → Total sales value (£)

Data was imported into Power BI, cleaned (data types adjusted: Date → Date, Revenue/Units Sold → Decimal/Whole Number), and modeled for analysis. No relationships needed (single flat table).

## Business Questions Answered

The dashboard visualizes answers to these key questions:

- What is the **total revenue** across all stores and periods? → Card visual
- Which **store** generates the highest revenue? → Bar chart (Revenue by Store)
- Which **product category** drives the most sales? → Column chart (Revenue by Category)
- How do sales compare between London and Reading?
- Which categories perform best in each store? (Potential future expansion)

## Dashboard Highlights

- **Total Revenue** KPI card
- **Revenue by Store** clustered bar chart
- **Revenue by Category** clustered column chart
- Clean, interactive layout with filters (if added)

## Tools & Technologies

- Power BI Desktop
- Data source: Excel
- Features used: Data modeling, DAX (implicit sums), visual formatting, slicers (optional)

## How to Use / Explore

1. Download the `.pbix` file from this repo
2. Open in Power BI Desktop
3. (Optional) Connect to your own updated Excel file via **Home → Transform data**

Feel free to fork, extend, or use as inspiration!

## Future Improvements

- Add time intelligence (monthly trends, YoY growth)
- Include product-level breakdowns
- Add slicers for Date, Store, Category
- Create tooltips and drill-through pages
- Publish to Power BI Service

Star ⭐ the repo if you find it useful!

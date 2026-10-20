
# ClipKart Sales Performance Dashboard (FY 2024)

An interactive Power BI dashboard that analyses e-commerce sales for **ClipKart** across categories, cities, products and months.

<img width="1432" height="809" alt="Dashboard" src="https://github.com/user-attachments/assets/cf5b0245-8edb-4a6a-a123-b7fc46f9dabd" />


## Objective
Give a quick view of sales performance and answer three questions:
1. Which categories, cities and products drive revenue?
2. How does revenue change month by month?
3. How does product price relate to revenue per order?

## Key metrics
| Metric | Value |
|---|---|
| Total Revenue | ₹6.16M |
| Total Orders | 1,000 |
| Total Quantity Sold | 2,469 |
| Average Order Value | ₹6.16K |
| Top Product Revenue | ₹837.62K (Phone) |

## Key insights
1. Revenue is split almost equally across Clothing (34.4%), Electronics (33.5%) and Groceries (32.1%).
2. Chennai is the top-performing city, followed by Kolkata.
3. Phone, Bread and Jacket are the top three products by revenue.
4. Higher-priced products earn more revenue per order, and revenue rises in clear bands by quantity.

## Dashboard features
- KPI cards for revenue, orders, quantity and average order value
- Monthly revenue trend, stacked by category
- Top 5 products and top cities by revenue
- Revenue share donut chart
- Price vs revenue scatter chart
- Slicers for Category, City and Date range
- Consistent colour theme, ₹ currency formatting and an insight line

## Tools used
- Power BI Desktop
- DAX (calculated column and measures)
- Data modelling and formatting in Power BI

## Data
- File: `ClipKart_ecommerce_data.csv`
- Columns: Date, OrderID, Category, Product, City, Price, Quantity, Revenue
- Calculated column: `Revenue = ClipKart_ecommerce_data[Quantity] * ClipKart_ecommerce_data[Price]`
- Measures: Total Orders, Avg Order Value, Top Product Revenue

## Repository structure
```
clipkart-sales-dashboard/
├── README.md
├── ClipKart report FY - 2024.pbix   # Power BI file
├── ClipKart_Dashboard.pdf           # PDF export of the report
└── ClipKart_ecommerce_data.csv      # Dataset
```

## How to open
1. Download `ClipKart report FY - 2024.pbix`.
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Use the Category, City and Date slicers to explore the data.

## What I learned
- Choosing the right chart for each question
- Writing DAX measures and formatting currency
- Using slicers to make a report interactive
- Designing a consistent layout and adding an insight line so the dashboard tells a story

## Contact
Abdul Muqheeth | https://www.linkedin.com/in/abdulmuqheeth/ | abdulmuqheeth05@gmail.com

# Online Sales Dashboard (Power BI)

An interactive one-page **Power BI** dashboard that analyses an e-commerce store's orders: sales, profit, product categories, regions and payment methods.

## What the dashboard shows

| Visual | Insight |
|---|---|
| KPI cards | Total profit and total number of orders |
| Gauge | Profit against total sales amount |
| Line chart | Sales amount over time, by order date |
| Bar chart | Profit by product category |
| Map | Sales amount by state |
| Pie chart | Share of orders by payment mode |
| Slicers | Filter everything by order date, state and category |

## Data model

The dashboard joins two tables:

- **Orders:** Order ID, Order Date, State and other customer details
- **Details:** Order ID, Amount, Profit, Category and PaymentMode

## How to view

1. Install [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop). It is free and runs on Windows.
2. Download [`Online_Sales_Dashboard.pbix`](Online_Sales_Dashboard.pbix) and open it.
3. Use the slicers to filter by date, state or category.

## Skills demonstrated

Power BI · data modelling (relationships between tables) · aggregations · KPI and geo visualisation · interactive filtering

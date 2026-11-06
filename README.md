# Sales & Profit Performance Dashboard

An interactive Power BI dashboard analyzing sales, cost, and profit across products, suppliers, regions, and months, built from an inventory and sales dataset (Q1 2026).

## Business Problem
Which products, suppliers, and regions drive the most sales and profit? Are sales and profit trending up or down, and where should the business focus?

## Dataset
- **Source:** Practice (training) dataset
- **Period:** January – March 2026
- **Size:** 150 orders, 15 columns
- **Fields:** Order_ID, Date, Product, Category, Region, Supplier, Quantity_Sold, Unit_Price, Unit_Cost, Sales, Cost, Profit, Stock_Quantity, Reorder_Level, Payment_Method

## Tools Used
Power BI (DAX, KPI cards, slicers, charts) | Excel

## What I Did
1. Cleaned and prepared the data in Excel
2. Created measures: Total Sales, Total Cost, Total Profit, **Profit Margin = Profit / Sales**
3. Built KPI cards for orders, quantity, cost, sales, profit, and margin
4. Built charts by month, supplier, product, and region
5. Added slicers for Month and Region

## Key Metrics
| Metric | Value |
|---|---|
| Total Orders | 150 |
| Units Sold | 693 |
| Total Sales | 148K |
| Total Cost | 100K |
| Total Profit | 48K |
| Profit Margin | 32.3% |

## Key Insights
- **Khartoum** is the top region (45K sales, 30.3%), followed by Port Sudan (42K). **Omdurman** is the lowest (24K).
- **Laptop** and **Monitor** lead in sales (about 41K and 38K), but **Monitor** earns the highest profit, while Laptop has a lower margin.
- **Supplier C** has the highest sales and profit; **Supplier B** is the lowest.
- Sales and profit declined from March to January in the monthly trend charts.
- Accessories (Mouse, Keyboard, Headset) contribute the least to total sales.

## Recommendations
- Increase focus on **Monitor**, which delivers the best profit.
- Review Laptop pricing or supplier cost to improve its margin.
- Develop sales plans for **Omdurman**, which lags behind other regions.
- Consider expanding orders with **Supplier C**, and review the terms with Supplier B.

## Notes
This project uses a practice dataset and is intended to demonstrate dashboard design and analysis skills.

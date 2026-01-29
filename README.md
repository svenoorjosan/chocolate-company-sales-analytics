# Chocolate Company Sales Analytics (Power BI)

Sales analytics dashboard built in Power BI for a fictional chocolate company.  
This project covers data modeling (star schema), DAX measures (including time intelligence), and an interactive report with KPIs, trends, and drilldowns.

## Preview
![Dashboard Screenshot](./Screenshot%202026-01-28%20204714.png)

## Power BI Report
- PBIX file: `ChocolateCompany_SalesAnalytics.pbix`
- (Optional) Live report link (Power BI Service): https://app.powerbi.com/view?r=eyJrIjoiMTZlYjQ3OTUtMjk4OS00NjhmLWI2MDktYWQ1YWYyMzgxZmIwIiwidCI6IjhjZDM2MGMyLTA2OGItNGUzNi04ZGI1LTI3YjM1NzkyZjUzZiIsImMiOjZ9

## What’s included
- KPI cards: Sales, Boxes, Shipments, Cost, Profit, Profit %
- Month-over-month change indicators
- Trend chart with a measure selector (field parameters)
- Low Box Shipments (LBS) analysis (shipments under 50 boxes)
- Performance tables for Salesperson and Product (with conditional formatting)

## Data model
Star schema:
- Fact: `Shipments`
- Dimensions: `Products`, `People`, `Geography`, `Calendar`

## How to use
1. Download this repo.
2. Open `ChocolateCompany_SalesAnalytics.pbix` in Power BI Desktop.
3. If prompted for data source paths, update them to match your local file locations.
4. Refresh and explore the report.

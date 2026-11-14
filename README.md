# Global-Retail-Performance-Dashboard
excel, data-analytics, sales-analysis, dashboard, pivot-table, data-cleaning, business-intelligence, retail-analytics
# Global Retail Performance Dashboard

Excel-based analysis of 1,500 retail orders (2023-2025) with an executive dashboard.

## Overview
This project analyzes a retail sales dataset using Microsoft Excel and Advanced Excel functions to convert raw transaction data into business insights.

## Dataset
- 1,500 order records, 19 columns
- Period: Jan 2023 - Jun 2025
- 5 regions, 7 products, 4 stores, 6 salespersons

## Key Metrics
| Metric | Value |
| --- | --- |
| Total Sales | $4,379,992.43 |
| Total Orders | 1,500 |
| Units Sold | 15,616 |
| Average Order Value | $2,919.99 |
| Return Rate | 24.8% |

## What I Did
- Cleaned data (filled 370 missing Promotion values, standardized dates and currency)
- Validated TotalPrice = Quantity x UnitPrice x (1 - Discount)
- Built analysis by region, product, customer type, store, salesperson, payment method and promotion
- Return rate analysis per product
- Created an executive dashboard with KPIs and charts

## Tools
Microsoft Excel, Pivot Tables, COUNTIF/SUMIFS, IFERROR, Excel Tables

## Dashboard Preview
![Dashboard](screenshots/dashboard.png)

## Files
- `data/` - raw and cleaned datasets
- `Retail_Dashboard.xlsx` - final workbook

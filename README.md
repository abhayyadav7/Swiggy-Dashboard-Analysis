# Swiggy Dashboard Analysis

## Project Overview
An Excel-based Swiggy dashboard project built to analyze order, delivery, financial, customer, restaurant, payment, and product data. The workbook presents key performance indicators (KPIs), interactive filters, and visual summaries across multiple analysis pages.

## Key Metrics
- Total Orders: 200,000
- Delivered Value: ₹34.59 Cr
- Net Revenue: ₹6.92 Cr
- Average Order Value: ₹1,841
- On-time Deliveries: 23.1%
- Cancellation Rate: 6.0%

## Dashboard Pages
- **Home** – Dashboard landing page
- **Overview** – Business overview and key metrics
- **Restaurants** – Restaurant performance
- **Delivery** – Delivery performance
- **Customers** – Customer experience
- **Payments** – Payments and revenue
- **Products** – Menu and item sales
- **Order Details** – Order-level details

## Interactive Features
- Filters for City, Service, Year, and Date Range
- Reset Filters button
- Refresh button
- PDF export for dashboard pages
- Monthly delivered value and city-wise delivered value visualizations
- Orders by service and customer discounts by coupon

## Data Sources
The project uses 14 CSV source files:

**Fact tables**
- `Fact_Orders.csv`
- `Fact_OrderItems.csv`
- `Fact_Financials.csv`
- `Fact_Delivery.csv`
- `Fact_Payments.csv`
- `Fact_Reviews.csv`

**Dimension tables**
- `Dim_City.csv`
- `Dim_Restaurant.csv`
- `Dim_Customer.csv`
- `Dim_DeliveryPartner.csv`
- `Dim_PaymentMode.csv`
- `Dim_Menu.csv`
- `Dim_Coupon.csv`
- `Dim_Service.csv`

The source data covers orders from January 2024 through June 2026.

## Tools Used
- Microsoft Excel 
- Power Query
- Power Pivot
- PivotTables and charts
- Excel VBA macros for dashboard actions




# BikeStats-Dashboard: Sales Performance Overview
An interactive Power BI dashboard built to explore and analyze sales trends in the bicycle industry—covering product categories, revenue performance, brand-level breakdowns, and city-wise insights.

## Purpose
The BikeTrack Dashboard is a data-driven visual reporting tool designed to monitor and analyze bike sales over time. It enables users to identify high-performing brands, popular categories, city-level distribution, and key revenue metrics. The dashboard is useful for sales analysts, retailers, inventory planners, and business managers aiming to optimize decision-making through visual insights.

## Tech Stack
The dashboard was developed using the following tools and technologies:

📊 Power BI Desktop – Primary tool for creating the interactive report and visuals.

📂 Power Query – Used to clean, transform, and filter the raw sales data.

🧠 DAX (Data Analysis Expressions) – Implemented for calculated measures like running totals, YTD/QTD/MTD revenue, and goal comparisons.

📁 Data Modeling – Relationships were established among product, customer, and order tables to enable dynamic filtering.

📄 File Format – .pbix for report file and .png snapshots for documentation.

📚 Data Source
| File Name         | Description                                                      |
| ----------------- | ---------------------------------------------------------------- |
| `customers.csv`   | Customer-level data including location and demographic info.     |
| `order_items.csv` | Line-item breakdown of each order (product, quantity, price).    |
| `orders.csv`      | Master order table with order IDs, customer IDs, and dates.      |
| `products.csv`    | Product details including brand and category references.         |
| `staffs.csv`      | Staff member data (likely for assigned sales or store handling). |
| `stocks.csv`      | Inventory data indicating stock levels at stores.                |
| `stores.csv`      | Store metadata such as city, name, and location.                 |
| `brands.csv`      | Brand lookup table for all product brands.                       |
| `categories.csv`  | Product category details (e.g., Road Bikes, Mountain Bikes).     |

## Features / Highlights
• Business Problem
In the competitive retail space, especially in niche categories like bicycles, understanding the performance of different product categories, sales trends, and regional variations is key to scaling operations, optimizing inventory, and increasing profit margins.

• Goal of the Dashboard
To deliver an intuitive, interactive, and filterable report that:

Helps businesses explore sales by year, brand, category, and geography.
Tracks revenue growth or decline over time.
Breaks down performance across different bicycle types and brands.
Provides detailed revenue tracking at daily, monthly, and quarterly levels.

## Walkthrough of Key Visuals
🔹 KPIs (Top Row)
Total Revenue: ₹7.69M

Total Customers: 1445

Total Quantity Sold: 7078 units

Discount Amount: ₹497.57

🔹 Revenue Growth Visuals
Growth Chart (2018 vs 2017): ₹293.41K increase (+7.44%)

Decline Segment (2018 vs 2017): ₹8.96K dip from goal

🔹 Revenue Breakdown (Right Pane)
Tree view by Category → Brand → City

Top category: Mountain Bikes (₹2.7M)

Leading brand: Trek

Top cities: Baldwin, Santa Cruz

🔹 Time-based Trends (Line Chart)
Revenue over Year & Quarter: Fluctuations from Jan 2016 to mid-2018

Highlights seasonal or cyclical buying behavior

🔹 Category & Geography Insights
Bar Chart: Revenue by category and city (Baldwin, Rowlett, Santa Cruz)

Pie Chart: Revenue distribution by brand (Trek leading with 59.86%)

🔹 Detailed Revenue Table
Includes fields:

Revenue_sum – Daily revenue

running_total – Cumulative revenue

YTD_rev, QTD_rev, MTD_rev – Year/Quarter/Month-to-date performance

Total Revenue Validated: ₹7.68M

### Business Impact & Insights
Brand & Category Insights: Mountain Bikes and Trek dominate overall sales.

Regional Focus: Baldwin emerges as the top-performing city/store.

Time Performance: Consistent growth up to 2018 with minor declines spotted.

Operational Use: Sales and marketing teams can prioritize top products and high-value regions.

Strategic Planning: Informs stock planning, promotional strategies, and business expansion.

## Screenshots / Dashboard Previews

#### Snapshot 1 – Summary KPIs, Category-wise Tree View  
![Advanced View](https://github.com/Omimishra/BikeStats-Dashboard/blob/main/data/Advanced%20View%20Snapshot.png?raw=true)

#### Snapshot 2 – Time Trend, Revenue by Brand and City  
![Normal View](https://github.com/Omimishra/BikeStats-Dashboard/blob/main/data/Normal%20view%20snapshot.png?raw=true)

#### Snapshot 3 – Detailed Revenue Table with MTD, QTD, YTD metrics  
![Detailed Table](https://github.com/Omimishra/BikeStats-Dashboard/blob/main/data/Detailed%20sales%20table.png?raw=true)


# blinkit-data-analytics-dashboard
BlinkIT Grocery Sales Dashboard (Power BI)  Interactive Power BI dashboard analyzing BlinkIt (India's quick-commerce grocery app) sales data. Tracks KPIs like total sales, average sales, item count, and rating, with breakdowns by item type, fat content, outlet size, location tier, outlet type, and establishment year, plus slicers for filtering.
## 📌 Overview
The dashboard helps answer key business questions such as:
- Which item categories drive the most revenue?
- How do sales differ across outlet sizes, location tiers, and outlet types?
- How does fat content (Low Fat vs Regular) affect sales?
- How have sales trended by outlet establishment year?
- How do average sales and ratings compare across outlet types?

## 📊 Key Metrics (KPIs)
- **Total Sales**
- **Average Sales**
- **Number of Items**
- **Average Rating**

## 📈 Visualizations
| Visual | Purpose |
|---|---|
| KPI Cards | Headline metrics at a glance |
| Donut Chart | Sales share by Item Fat Content |
| Donut Chart | Sales share by Outlet Size |
| Bar Chart | Total Sales by Item Type |
| Clustered Bar Chart | Sales by Outlet Location Type, split by Fat Content |
| Line Chart | Sales trend by Outlet Establishment Year |
| Funnel Chart | Sales by Outlet Location Type |
| Matrix / Table | Outlet Type breakdown: Total Sales, Items, Avg Sales, Avg Rating, Item Visibility |

## 🎛️ Interactivity
Dynamic slicers for **Outlet Location Type**, **Outlet Size**, and **Item Type**,
plus a metric-selector slicer to switch the measure displayed across charts.

## 🛠️ Tech Stack
- **Power BI Desktop**: data modeling, DAX measures, report design
- **DAX**: calculated measures (Total Sales, Avg Sales, No. of Items, Avg Rating)
- **Custom UI**: themed layout with custom KPI backgrounds and icons

- 
## dataset used:
<a href=https://github.com/vasu2307/blinkit-data-analytics-dashboard/blob/main/BlinkIT%20Grocery%20Data.xlsx>excel file<a/>
<a href=https://github.com/vasu2307/blinkit-data-analytics-dashboard/blob/main/data%20analysis%20dashboards.pbix>view dashboard<a/>

## dashboard:
<img width="1231" height="697" alt="Screenshot 2026-10-06 120044" src="https://github.com/user-attachments/assets/52318de6-4c05-45cb-8879-8224fddfa2b7" />

## Project Insights
Dataset covers 8,523 Blinkit grocery items across multiple outlets.
Total Sales: $1.20M.
Average Sales per item: $141.
Average Customer Rating: 3.92 / 5.
Low Fat items bring 64.6% of sales ($776K).
Regular items bring 35.4% of sales ($425K).
Low Fat leads on volume (5,517 items vs 3,006), not price.
Fruits & Vegetables is the top category ($178K, 14.8%).
Snack Foods is a close second ($175K, 14.6%).
Household is third ($136K, 11.3%).
The top 3 categories make up about 41% of all sales.
Seafood, Breakfast and Starchy Foods together contribute under 4%.
Household and Dairy have the highest avg sales per item ($149 and $148).
Baking Goods has the lowest avg sales per item ($126).
Medium outlets lead with 42.3% of sales.
Small outlets contribute 37%.
High-size outlets contribute only 20.7%.
Tier 3 cities generate the most sales (39.3%, $472K).
Tier 2 follows with 32.7%.
Tier 1 is the lowest at 28%.
Low Fat beats Regular in all three location tiers.
Supermarket Type 1 dominates with 65.5% of sales.
Grocery Store, Type 2 and Type 3 each hold about 11–13%.
Outlets established in 2018 lead by year (17% of sales).
Outlets from 2011 are the lowest (6.5%).
Avg sales per item stay flat (~$141) across every segment.
Ratings are uniform (~3.9) across all categories and outlets.
Meat has the best rating (3.98).
Breads has the lowest rating (3.83).
Revenue differences come from sales volume, not price or ratings.


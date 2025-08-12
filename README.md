# Blinkit Sales Dashboard

## Project Overview
This project analyzes Blinkit sales data, offering insights into total sales ($1.20M), items sold (8.523K), average sales (141), and average rating (4). It visualizes trends across item types, outlet sizes, locations, and establishment years to help optimize inventory, marketing, and operations for the grocery delivery platform.

## Key Visualizations
- **Summary Metrics**: Cards for total sales ($1.20M), items sold (8.523K), average sales (141), and average rating (4)
- **Sales by Outlet Establishment Year Line Chart**: Peaks at $205K in 2022, declining from $132K in 2012 to $129K in 2020
- **Sales by Item Type Bar Chart**: Top categories: Fruits and Vegetables ($178K), Snack Foods ($175K), Household ($136K), Frozen Foods ($119K)
- **Sales by Outlet Size Pie Chart**: Medium (42.3%, $507.90K), High (37.0%, $444.78K), Small (20.7%, $248.99K)
- **Sales by Outlet Location Type Bar Chart**: Tier 3 ($472.13K), Tier 2 ($393.15K), Tier 1 ($336.40K)
- **Filters**: Dropdowns for outlet location type and item type

## Insights and Analysis
- **Top Performers**: Fruits/Vegetables and Snacks drive ~30% of sales ($353K combined), suggesting focus on fresh produce promotions
- **Outlet Trends**: Medium-sized outlets contribute most (42%), while Tier 3 locations lead sales—expand in high-tier urban areas
- **Temporal Growth**: Sales rose from 2012 but dipped post-2018; 2022 peak indicates recovery, potential from post-pandemic demand
- **Rating Impact**: Average rating of 4 correlates with high sales in top categories; low performers like Seafood ($9K) may need quality checks
- **Efficiency**: Average sales per item at 141; small outlets underperform (20.7% share), recommending resource reallocation to medium/high

## Technologies Used
- **Data Visualization**: Power BI for interactive dashboards with charts, pies, and filters
- **Data Source**: Likely CSV/Excel files for sales data import
- **Querying**: DAX for calculations (e.g., SUM sales, AVG rating)
- **Other**: Potential Python (Pandas) for preprocessing, though not shown

## Project Steps
1. **Data Collection**: Gather sales dataset with columns like item type, outlet size, location, year
2. **Data Cleaning**: Handle formats, aggregates in Power BI or Excel
3. **Dashboard Design**: Create visuals—summary cards, bar/pie/line charts, filters
4. **Analysis**: Compute metrics (e.g., total sales by category) for insights
5. **Testing**: Apply filters, validate trends
6. **Deployment**: Share .pbix file or publish to Power BI service

## How to Use
1. Clone repo: `git clone <repo-url>`
2. Open dashboard: Load .pbix file in Power BI Desktop
3. Apply filters: Select outlet type/item to drill down
4. Explore: Hover on charts for details; export reports
5. Customize: Edit in Power BI for new visuals

## Contact
For questions, reach out to [your-email@example.com] or open an issue on GitHub.

## License
MIT License - Free to use, modify, and distribute. See LICENSE file for details.

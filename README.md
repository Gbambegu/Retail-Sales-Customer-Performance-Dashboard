# Retail-Sales-Customer-Performance-Dashboard
# Executive Summary

This analysis examined retail sales data from Power BI, summarising total sales, discounts, and product performance across multiple regions and suppliers. The results show that Furniture, Clothing, and Electronics are the leading categories, accounting for the majority of net revenue. Furniture contributed the highest share at $ 65,000, followed by Clothing at $ 23,000, and Electronics at $18,000.

Regional analysis revealed that the North region achieved the highest revenue performance, while the South recorded the lowest. Supplier analysis showed that Supplier A sold the highest quantity, indicating strong distribution and customer demand. Monthly sales trends showed a sharp increase in April, followed by a decline in May, suggesting potential seasonality or demand fluctuations.

# Key recommendations include:

1. Prioritise marketing and inventory investment in top-performing categories, particularly Furniture and Electronics.
2. Strengthen partnerships with high-performing suppliers (especially Supplier A).
3. Investigate weaker regional performance to balance sales distribution.
4. Monitor monthly sales trends to anticipate seasonal demand and optimise stock.
5. Develop targeted promotional strategies around peak months to stabilise revenue across periods.
These actions will improve decision-making, enhance supply chain coordination, and support data-driven retail growth.
# Data Understanding

The analysis used sales data visualised in Power BI, integrating information from transactional records covering product categories, subcategories, regions, and suppliers.
The dataset captures performance metrics such as:
1. Total Sales: 106K
2. Total Quantity Sold: 220 units
3. Total Discount Amount: 14K
4. Regions Covered: North, East, West, South
5. Major Categories: Furniture, Clothing, Electronics
6. Subcategories: Laptop, Table, Mobile, Shirt, Sofa
7. Suppliers: A, B, C
8. Countries: Canada, France, Germany, UK, USA
This dataset provides a comprehensive view of product performance and revenue contribution across various geographies and time periods.
# Methodology
# Data Cleaning
Data was cleaned in Power Query Editor before visualisation:
- Removed duplicate and irrelevant fields.
- Standardised date and currency formats.
- Replaced missing values with averages or “Unknown.”
- Renamed columns for clarity.
- Created a calculated field for Revenue = Quantity × Unit Price × (1 - Discount/100).
- Merged multiple data sources (Sales, Products, Region, Supplier).
After these steps, the dataset was structured and reliable for analysis and visualisation.
# Feature Engineering
New metrics and relationships were introduced using DAX:
1. Total Sales, Total Quantity, and Total Discount Amount as calculated measures.
2. Relationships are built in a star schema linking sales to product, region, and supplier dimensions.
3. A time-based relationship established for trend analysis by month.
4. Seven new columns were created to ensure the analysis was conducted thoroughly

# Data Exploration
Initial exploration in Power BI included:
1. KPI visuals for Total Sales, Quantity, and Discount Amount.
1. Bar charts for Net Revenue by Category and Region.
2. Line chart for Net Revenue by Month.
3. Interactive slicers by Country for comparative insights.

# Data Analysis

# Revenue Performance
Total revenue amounted to $106000, with total discounts of $14000 and 220 units sold.
Furniture led all categories with 65K, representing over 60% of total revenue. Clothing contributed $23000, while Electronics generated $18000.

In terms of subcategories, Laptops and Tables achieved the highest net revenue (above 25K each), confirming the strong role of technology and home-related products in driving sales.

# Regional Performance

The North region dominated performance with the highest revenue, exceeding 30K, followed by the East and West regions. The South region reported the weakest results, suggesting potential gaps in customer engagement or market reach.

# Supplier Analysis
Among suppliers:
- Supplier A sold the highest quantity, close to 100 units.
- Supplier B followed with around 80 units.
- Supplier C sold the least, under 60 units.

Supplier A’s consistent performance highlights reliability in both distribution and customer demand. Future supplier evaluation should include fulfilment capacity, product quality, and customer ratings.

# Temporal Performance

Revenue fluctuated across months. Sales started low in January and February, climbed steadily in March, and peaked sharply in April. A sharp drop occurred in May, followed by a moderate rebound in June. This suggests demand concentration in the second quarter, possibly due to promotions or seasonal factors.
# Category and Subcategory Insights

- Furniture: Highest-performing category, strong across all months.
- Clothing: Moderate contribution, potential for targeted promotions.
- Electronics: Stable performance with opportunity for growth through marketing.
- Subcategories (Laptop, Table, Mobile): Drive the majority of category sales and should remain central to inventory and marketing plans.

# Decision-Making and Recommendations
# 1. Strengthen Core Product Lines
The analysis shows that Furniture dominates sales performance. Management should focus resources on expanding this category through variety, premium options, and targeted promotions.
Electronics also show strong potential; investing in new models and accessories can drive further growth.
# 2. Optimise Supplier Partnerships
Supplier A consistently outperformed others. The company should strengthen collaboration with Supplier A and evaluate opportunities to scale successful products to underperforming regions. Low-performing suppliers (B and C) may need performance reviews or contract renegotiations.

# 3. Address Regional Imbalances
The North region outperforms the South. To ensure balanced growth, management should identify distribution gaps, customer needs, and marketing presence in the South and West. Localised campaigns and improved logistics can close the performance gap.
# 4. Leverage Monthly Trends
April’s performance peak indicates a seasonal or promotional opportunity. Future campaigns should align with this period to maximise returns. Low-performance months (January, May) should include discount offers or limited-time promotions to sustain revenue flow.
# 5. Enhance Data Monitoring
The Power BI dashboard effectively tracks performance. Continuous data refresh and monitoring will help detect emerging patterns early. Management should use monthly reports to compare regions, suppliers, and categories in real time.

# Conclusion
The analysis provides a clear picture of sales behaviour across product categories, suppliers, and regions. Furniture remains the company’s revenue leader, supported by strong supplier performance and stable monthly growth. The North region sets the benchmark for performance, while the South and West offer untapped opportunities.

Future strategy should focus on reinforcing supplier partnerships, optimizing category-level marketing, and using temporal insights to plan campaigns. By aligning operations and promotions with data-driven insights, the company will enhance revenue consistency, improve market reach, and sustain long-term profitability.

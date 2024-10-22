# PowerBI-project
## Dynamic Business Performance Dashboard in Power BI

This project demonstrates the creation of an end-to-end Power BI dashboard designed to analyze business performance for a fictional manufacturing company. The project covers data transformation, relationship modeling, and advanced Power BI visuals like treemaps, scatter plots, and waterfalls. 
The report offers dynamic insights into key metrics such as sales, gross profit, and quantity, utilizing DAX measures, switch measures, and conditional formatting to visualize growth opportunities and potential pain points. Features include YTD vs PYTD comparisons, custom switch measures, and drill-down functionality across multiple hierarchies (country, product type).

### 1. Data Transformation:
Source Data: Excel dataset with sales, account, and product hierarchy tables.
Preprocessing: Loaded data into Power Query to clean up columns, remove duplicates, and ensure correct data types.
Virtual Tables: Created a custom date table for time-based analysis from 01.01.2022 to 31.12.2024.

### 2. DAX Measures & Calculations:
Developed YTD, PYTD (prior year-to-date), and YTD vs PYTD switch measures for sales, quantity, and gross profit.
Calculated variables for Gross Profit %, YTD vs PYTD comparisons, and built out measures for trend analysis.

### 3. Data Model:
Established relationships between tables using unique identifiers (Account ID, Product ID).
Created calculated columns for a product family, group, and hierarchy navigation.

### 4. Visualizations & Dynamic Reporting:
Dynamic Headings: Automatically updated based on slicer values for better user understanding of selected metrics.
Slicers: Provided slicers for easy switching between sales, quantity, and gross profit across years and metrics.

### 5. Key Visuals:
YTD vs PYTD Waterfall Chart: Detailed comparison of performance by product type, country, and month, with drill-down capabilities.
Scatter Plot: Showed Gross Profit % vs YTD values, enabling easy segmentation of high-value accounts.
Stacked Column & Line Chart: Illustrated trends over time for different product types and regions, allowing for performance tracking.
Tree Map: Highlighted the bottom 10 countries by YTD vs PYTD, providing a clear view of underperforming regions.

### 6. Conditional Formatting & UX Enhancements:
Applied conditional formatting in various visuals (e.g., red for negative growth, green for positive) to enhance clarity.
Integrated average lines in scatter charts for quick assessment of performance relative to benchmarks.
Customized dropdowns and filters for intuitive user navigation ensure the dashboard is interactive and user-friendly.

This project showcases how Power BI can deliver meaningful, actionable insights, driving business decisions through advanced analytics and intuitive visual designs.

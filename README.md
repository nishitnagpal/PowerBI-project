# 📊 Dynamic Business Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-10B981?style=for-the-badge)

> An end-to-end Business Intelligence solution providing dynamic insights into sales, gross profit, and quantity metrics for a manufacturing company. 

*(**Note:** Insert a high-quality GIF or Screenshot of your dashboard here to instantly grab the recruiter's attention!)*
`![Dashboard Preview](./dashboard-preview.gif)`

## Project Objective
To transform raw Excel sales data into an interactive, intuitive dashboard that allows stakeholders to instantly identify growth opportunities, track Year-to-Date (YTD) performance against the previous year (PYTD), and pinpoint underperforming regions or products.

## Key Business Insights
* **Performance Tracking:** Enabled instant YTD vs. PYTD comparisons across multiple hierarchies (Country, Product Type).
* **Segmenting High-Value Accounts:** Utilised scatter plots (Gross Profit % vs YTD values) equipped with average benchmark lines to easily segment and identify top-performing accounts.
* **Risk Identification:** Highlighted the bottom 10 underperforming countries using Treemaps, providing executives with a clear view of where intervention is needed.

## Technical Implementation

**1. Data Transformation & Power Query**
* Extracted raw Excel datasets encompassing sales, accounts, and product hierarchies.
* Cleaned and preprocessed data using Power Query (removed duplicates, enforced data types).
* Created a custom virtual Date Table to enable robust time-intelligence analysis.

**2. Data Modelling**
* Architected a relational data model establishing one-to-many relationships between fact and dimension tables via unique identifiers (Account ID, Product ID).
* Engineered calculated columns for product families, groups, and hierarchy navigation.

**3. Advanced DAX Measures**
* Developed dynamic Time-Intelligence measures (YTD, PYTD).
* Implemented complex `SWITCH` measures allowing users to toggle the entire dashboard's context between Sales, Quantity, and Gross Profit seamlessly.
* Calculated vital variables for Gross Profit % and trend analysis comparisons.

**4. Interactive Visualizations & UX**
* **Dynamic Headings:** Titles automatically update based on user slicer selections to prevent cognitive overload.
* **Waterfall Charts:** Detailed variance analysis of performance by product type, country, and month.
* **Conditional Formatting:** Applied dynamic colour coding (e.g., red for negative growth, green for positive) across visuals to enhance immediate readability.

## View the Report
Since this report utilises advanced features, the best way to experience the interactivity is by viewing the demo video below or downloading the static PDF report:
* [📄 View High-Res PDF Report](./Performance Report.pdf)
* [🎥 Watch Video Walkthrough](./powerbi-demo.mp4)

# Business-Insights-360-AtliQ-Hardwares
# Business Insights 360 - AtliQ Hardwares

### Dashboard Link: [Power BI Report](https://app.powerbi.com/groups/2389143c-96ed-4fbd-8a9a-45c0ead4862c/reports/a8435c73-9d56-44ea-afa7-a696712df3d5/62180739fa60d1551321?experience=power-bi)

## Problem Statement

This dashboard provides AtliQ Hardwares with comprehensive insights into their business performance. It helps the organization understand key metrics such as **Net Sales**, **Gross Margin**, and **Profitability**, and identifies areas for improvement across different regions, products, and customers. The dashboard also allows the tracking of **forecast accuracy**, **customer performance**, and **market trends**, providing actionable insights for decision-makers.

## Key insights include:
- Monitoring performance over time to identify growth opportunities.
- Analyzing customer and product profitability to optimize resources.
- Understanding the impact of sales and operational delays on business performance.

### Steps Followed

- **Step 1**: Load data from MySQL into Power BI using a custom gateway to ensure real-time updates.
- **Step 2**: Open Power Query Editor and review the dataset. Column profiling was done for error detection and quality assessment.
- **Step 3**: Filtered out null values for accurate average calculations (e.g., Net Sales, Gross Margin).
- **Step 4**: Applied theme and customized the report's layout for a professional look.
- **Step 5**: Created key visuals including KPI cards, bar charts, and line graphs to represent **Net Sales**, **Gross Margin**, and **Profitability** trends.
- **Step 6**: Added visual filters (Slicers) to segment data by **Region**, **Customer Type**, and **Product**.
- **Step 7**: Used **bar charts** to show regional P&L changes and **scatter plots** to visualize customer performance.
- **Step 8**: Calculated **Forecast Accuracy** and visualized it using **line charts** and **trend indicators**.
- **Step 9**: Added custom **calculated columns** using DAX for performance segmentation (e.g., Age Group for customers).
- **Step 10**: Integrated customer data into interactive visuals with drill-downs for detailed insights into regional and product-level performance.
- **Step 11**: Published the final report to Power BI Service for shared access and real-time updates.

### Insights

- **Total Net Sales**: $4.97B
  - **Net Profit**: -13.98%
  - **Gross Margin**: 38.08%
  - Breakdown by region and product shows the highest growth in **NA** and **Notebook** segments.

- **Key Metrics**:
  - **Forecast Accuracy**: 81.17%
  - **Net Error**: -2.47M
  - **Customer Performance**: Top customers contributing to Net Sales include **Amazon**, **AtliQ eStore**, and **AtliQ Exclusive**.

- **Forecast Accuracy**: Shows a consistent increase in the accuracy of sales and margin forecasts, allowing for more precise business planning.

- **Market Trends**: A detailed **Market Share** report was created to understand competitive positioning.

### Insights Delivered

- **Customer Insights**: Analyzed the **Top Customers** and their Net Sales performance, leading to better customer targeting and strategic decisions.
- **Product Insights**: Focused on the **Notebook** and **Accessories** segments, providing a clear understanding of their profitability and areas for cost optimization.
- **Sales Performance**: Sales by region showed significant variations, helping the company identify high-performing and underperforming markets.

### Technology Stack
- **Tools Used**: Power BI, MySQL, Excel
- **Data Sources**: MySQL database (connected via Power BI Gateway)
- **Data Transformation**: Cleaned and modeled using Power Query, Power Pivot, and DAX for complex calculations.

### Impact
- Improved decision-making with interactive and tailored dashboards.
- Enhanced operational efficiency by automating data reporting processes.
- Provided real-time visibility into business performance across multiple dimensions (sales, products, regions).

## About the Developer
As a Data Analyst, I specialize in creating tailored business intelligence solutions using Power BI. My expertise includes integrating multiple data sources, performing advanced data transformations, and delivering actionable insights through intuitive visualizations.

---

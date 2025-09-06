## powerbi-superstore-sales-dashboard

### Superstore Sales Forecasting & Business Intelligence Dashboard
Transforming Retail Data into Actionable Insights with Power BI

### 1. About the Project 

This project delivers an end-to-end Power BI Sales Dashboard designed to analyze and forecast retail superstore performance. The purpose of the dashboard is to provide decision-makers with actionable insights by tracking KPIs such as sales, profit, orders, and shipping performance across regions, categories, and customer segments. By integrating advanced data modeling, DAX calculations, and forecasting techniques, the project not only highlights past and present business performance but also predicts future sales trends. The goal is to showcase how business intelligence and analytics can transform raw data into strategic decisions that improve profitability, optimize inventory, and strengthen market competitiveness.

--- 

### 2. Tech Stack & Skills Used

The dashboard was built using the following tech stack:

- **Power BI Desktop** – Data modeling, interactive dashboards, and DAX calculations  
- **DAX (Data Analysis Expressions)** – Created calculated columns, measures, and KPIs  
- **Data Transformation** – Used Power Query for data cleaning and preparation  
- **Time Intelligence Functions** – Trend analysis and year-over-year/month-over-month comparisons  
- **Forecasting Tools** – Applied Power BI’s built-in forecasting with confidence intervals  
- **Data Visualization** – Line charts, bar charts, maps, KPI cards, slicers, and filters for interactivity  
- **Business Acumen** – Combined retail domain understanding with analytics for actionable insights  

---

### 3. Data Source

The dataset originates from Kaggle’s Superstore Sales dataset, a widely-used retail dataset ideal for business analytics and forecasting tasks.  
It contains 4 years of transactional data from a fictional global superstore.

**Key fields include:**  
`Order ID`, `Order Date`, `Ship Date`, `Region`, `State`, `City`, `Category`, `Sub-Category`, `Product Name`, `Sales`, `Quantity`, `Discount`, `Profit` — enabling rich analytics across various dimensions.

---

### 4. Highlights of the Project

- Built an interactive Power BI dashboard for analyzing Superstore Sales and Profit.  
- Performed regional, segment, category, and payment mode analysis to identify sales distribution.  
- Implemented time-series analysis & forecasting to predict future sales trends with confidence intervals.  
- Designed KPI cards for instant tracking of Orders, Sales, Profit, and Shipping performance.  
- Added a geospatial map to visualize sales and profit distribution across different U.S. states.  
- Leveraged DAX measures and Power Query for advanced calculations and clean data modeling.  
- Delivered actionable business insights to support strategic decisions in marketing, inventory, and logistics.  

---

### 5. Key Insights of the Project

- West region had the highest sales but weaker profit margins due to higher discounts.  
- Furniture category underperformed compared to Technology and Office Supplies.  
- Corporate customers drove higher revenue per order, while Consumers bought more frequently.  
- Same-Day shipping increased costs disproportionately, reducing profitability.  
- Sales forecasting projected a consistent upward trend in the next quarters.  

---

### 6. Business Impact

- Helped identify low-profit categories where discount strategies must be revisited.  
- Optimized supply chain planning by highlighting costly shipping practices.  
- Supported targeted marketing strategies by segmenting high-value customers.  
- Enhanced overall profitability and strategic decision-making by aligning data insights with business goals.  

---
### 7. Screenshots

Here’s how the interactive Superstore Sales Dashboard looks in Power BI:  
![Superstore Sales Dashboard](https://github.com/sinharitamvaraa/powerbi-superstore-sales-dashboard/raw/main/snapshot%20of%20sales%20dashboard%20.jpg)

## Sales forecasting view :  
![Sales Forecasting Visualization](https://github.com/sinharitamvaraa/powerbi-superstore-sales-dashboard/raw/main/snapshot%20of%20live%20sales%20forecast%20.jpg)

## Sales & Profit by State Map
This map visualizes the **sum of sales and profit across U.S. states**, helping identify high-performing regions. Each bubble represents a state's total sales volume, with larger bubbles indicating higher revenue. When hovering over a state (e.g., California), a tooltip displays exact figures — **California recorded the highest sales ($335K) and profit ($49K)**. This geographic breakdown supports regional performance comparisons and informs targeted regional strategies.

![Sales and Profit by State](https://raw.githubusercontent.com/sinharitamvaraa/powerbi-superstore-sales-dashboard/main/map-visual.jpg)

## KPI Metrics & Region Slicers
This panel highlights key performance indicators such as Orders, Sales, Profit, and Shipping Days, all dynamically updated using the region slicer at the top. In the displayed snapshot, only the Central region is selected, so the KPIs and charts reflect region-specific performance — showing 5,239 orders, $341K in sales, and $27.45K in profit. The interactive slicer empowers users to toggle between regions (East, West, South, Central) or select multiple for comparison, making this dashboard both intuitive and analytically powerful.

![KPI Panel and Region Slicers](https://raw.githubusercontent.com/sinharitamvaraa/powerbi-superstore-sales-dashboard/main/kpi-panel%20and%20slicers%20.jpg)

## Zoom Slider for Sales Trend Exploration
This visualization features two line charts showing sales trends from January 2019 to January 2021. The top chart displays the overall sales timeline, while the bottom chart uses an interactive zoom slider focused on **November 2020 to January 2021**. This zoom slider enables users to drill down into specific date ranges, revealing detailed daily sales fluctuations with peaks over 10K. Compared to earlier single-chart views, this setup provides both a broad overview and precise, focused analysis, enhancing the ability to explore sales patterns effectively.

![Zoom Slider - Sales Over Time](https://github.com/sinharitamvaraa/powerbi-superstore-sales-dashboard/blob/main/zoom-slider.jpg)


---



# Power-BI

# Sales-Dashboard

### Dashboard Link :https://app.powerbi.com/groups/me/reports/5762c1ab-e2d8-4b99-88b2-2f2138f967ab/ReportSection?experience=power-bi
## Problem Statement

An online sales dashboard is a visual representation of key metrics and performance indicators related to online sales activities. It provides a real-time or near-real-time snapshot of sales data, enabling businesses to monitor their online sales performance, identify trends, and make data-driven decisions. Here's a detailed description of what an online sales dashboard typically includes:

1.Overview of Sales Performance: The dashboard typically starts with a high-level overview of sales performance, displaying total sales revenue, number of orders, and other top-line metrics. This section gives stakeholders a quick understanding of how the online sales channel is performing overall.

2.Sales Trends and Patterns: The dashboard may include visualizations that show sales trends over time, such as daily, weekly, or monthly sales trends. Line charts, area charts, or bar charts can be used to illustrate patterns in sales volume, revenue, or order frequency, helping businesses identify seasonal trends or growth opportunities.

3.Product Performance: This section of the dashboard focuses on analyzing the performance of individual products or product categories. It may include metrics such as best-selling products, revenue by product category, or average order value by product. Heat maps, pie charts, or treemaps can be used to visualize product sales distribution and identify top-performing products.

4.Customer Analysis: Understanding customer behavior is crucial for optimizing online sales strategies. The dashboard may include metrics related to customer demographics, acquisition channels, and purchasing habits. Visualizations like customer segmentation charts, customer lifetime value (CLV) analysis, or customer acquisition cost (CAC) can provide insights into customer preferences and help tailor marketing efforts accordingly.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : In the report view, under the view tab, theme was selected.
- Step 5 : Visual filters (Slicers) were added for four fields named "State", "Ordered Date".
- Step 6 : Four card visuals were added to the canvas, one representing sum of Profit, Sum of amount, Sum of quantity, sum of AOV  
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
      
- Step 7 : In the report view, under the insert tab, two text box is added to the canvas, that is Sales Dashboard
- Step 8 : In the visual there are six different types of visual represents the sales dashboard.

        
A card visual was used to represent sum of profit
  
![Sum of Profit](https://github.com/kusumahp/Power-BI/assets/156166019/76ac4417-0af4-41a9-af2d-05e0a36983e7)

 
 
 A card visual was used to represent sum of quantity.
 
 
![Sum Of Quantity](https://github.com/kusumahp/Power-BI/assets/156166019/7051719d-27ae-4891-a2c9-b8696bf17a6f)
 
 - Step 9  : The report was then published to Power BI Service.
 
 # Report Snapshot (Power BI DESKTOP)

 
![SalesDashboard](https://github.com/kusumahp/Power-BI/assets/156166019/c336dd31-138a-4798-b3fe-a52a586d35db)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Profit = 37k

                   
### [2] Highest sales by states

    a) Maharashtra
    b) Madhya Pradesh
    c) Uttar Pradesh
    d) Delhi
  
   
  These ratings will change if different visual filters will be applied.  
  
  


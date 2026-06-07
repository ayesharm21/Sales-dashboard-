# Sales Data Analysis Dashboard

### Dashboard Overview

This dashboard helps businesses analyze sales performance, profitability, promotional effectiveness, and regional sales trends. It enables stakeholders to identify top-performing and low-performing products, monitor sales growth over time, compare performance across different periods, and make data-driven decisions.

The dashboard also helps users understand customer purchasing behavior, evaluate promotional campaigns, and identify opportunities to improve revenue and profitability.

The report consists of four analytical pages:

1. Overview Dashboard
2. Top & Bottom 5 Products Analysis
3. Sales, Profit & Quantity Comparison Analysis
4. Detailed Order Analysis

---

## Problem Statement

This dashboard helps business stakeholders understand overall sales performance and profitability across different products, promotions, cities, and time periods. Through various visualizations, they can identify high-performing products, evaluate promotional effectiveness, analyze regional sales trends, and compare business performance between selected periods.

Since product performance, profitability, and customer demand vary significantly across categories and regions, the dashboard provides valuable insights that can support inventory planning, promotional strategies, and business growth.

---

### Business Requirements

#### Overview Dashboard

- Sales by City
- Number of Orders
- Average Discount Value by Promotion Category
- Profit vs Net Sales Analysis
- Sales Trend Analysis

#### Product Analysis

- Top 5 Products by Sales, Profit, and Quantity Sold
- Bottom 5 Products by Sales, Profit, and Quantity Sold

#### Comparison Analysis

- Compare Sales between any two selected periods
- Compare Profit between any two selected periods
- Compare Quantity Sold between any two selected periods

#### Detailed Analysis

- View transaction-level order details
- Enable filtering and drill-down analysis

---

### Steps Followed

- Step 1 : Loaded the sales dataset into Power BI Desktop.

- Step 2 : Opened Power Query Editor and enabled:
  - Column Quality
  - Column Distribution
  - Column Profile

- Step 3 : Reviewed the dataset and validated data quality by checking for missing or inconsistent values.

- Step 4 : Created a Date Table to support time intelligence calculations and comparison analysis.

- Step 5 : Established relationships between fact and dimension tables for efficient data modeling.

- Step 6 : Created DAX measures to calculate:
  - Total Sales
  - Net Sales
  - Total Profit
  - Quantity Sold
  - Number of Orders
  - Average Discount Value

- Step 7 : Created an Overview Dashboard containing:
  - Sales by City
  - Number of Orders
  - Average Discount Value by Promotion Category
  - Profit vs Net Sales Analysis
  - Sales Trend Analysis

- Step 8 : Created Top & Bottom 5 visuals to analyze products based on:
  - Sales
  - Profit
  - Quantity Sold

- Step 9 : Implemented comparison visuals allowing users to compare:
  - Sales
  - Profit
  - Quantity Sold

  between two selected periods.

- Step 10 : Created a detailed order-level analysis page containing transaction-level information.

- Step 11 : Applied themes, formatting, and visual enhancements to improve dashboard appearance and usability.


---

# Snapshot of Dashboard (Power BI Desktop)

### Overview Dashboard                                                                      

"https://github.com/user-attachments/assets/1b53bc1a-14d8-49a7-9676-22dc807d3e54" />

This page provides a high-level summary of business performance, including sales distribution across cities, total orders, promotional discount analysis, profitability trends, and sales performance over time.

---

### Top & Bottom 5 Products Analysis

"https://github.com/user-attachments/assets/97eeea51-3035-4ff6-8a2f-49866536ffb8" />

This page identifies the highest and lowest performing products based on Sales, Profit, and Quantity Sold.

---

### Sales, Profit & Quantity Comparison Analysis

"https://github.com/user-attachments/assets/8ede14cd-a358-4fc6-aee3-d3806bfbf755" />

"https://github.com/user-attachments/assets/fea45588-b3c8-4e40-9637-5ae018f9cf87" />

This page allows users to compare Sales, Profit, and Quantity Sold between two selected periods.

---

### Detailed Order Analysis

"https://github.com/user-attachments/assets/c7832ee0-d284-4a91-a07c-8607d497dce2" />

This page provides transaction-level details and supports filtering and drill-down analysis.

---

# Insights

A four-page interactive report was created on Power BI Desktop and then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total Number of Orders = 3,510

Thus, the business processed a significant number of customer transactions during the reporting period.

---

### [2] Sales by City

Sales are distributed across major Indian cities including:

- Mumbai
- Delhi
- Bengaluru
- Hyderabad
- Chennai
- Kolkata

Thus, metropolitan cities contribute significantly to overall business revenue.

---

### [3] Average Discount Value by Promotion Category

- Weekend Flash Sale recorded the highest average discount value.
- Clearance Sale recorded the second-highest average discount value.
- Festive Diwali recorded the lowest average discount value.

Thus, promotional strategies vary significantly across campaigns and influence customer purchasing behavior.

---

### [4] Profit vs Net Sales Analysis

A strong positive relationship exists between Profit and Net Sales.

Thus, as Net Sales increase, Profit also increases, indicating healthy business performance.

---

### [5] Sales Trend Analysis

Sales remained relatively consistent between 2020 and 2024, with several peak-performing periods observed throughout the timeline.

Thus, the business demonstrates stable sales performance with seasonal fluctuations in customer demand.

---

### [6] Top Performing Products

- Apple iPhone 14
- Apple MacBook Air
- Sony Bravia 55" TV
- Samsung Galaxy S21
- HP Pavilion Laptop

These products generated the highest Sales and Profit.

Thus, premium electronic products contribute significantly to overall revenue and profitability.

---

### [7] Bottom Performing Products

- Tupperware Lunch Box
- L'Oreal Shampoo
- Nivea Body Lotion
- Dove Soap Pack
- Colgate Toothpaste

These products generated the lowest Sales and Profit.

Thus, these products may require revised pricing, promotional efforts, or inventory strategies.

---

### [8] Quantity Sold Analysis

- Apple iPhone 14 recorded the highest quantity sold.
- Several household and personal care products recorded the lowest quantities sold.

Thus, customer demand is strongest for premium technology products.

---

### [9] Comparison Analysis

Users can compare Sales, Profit, and Quantity Sold between any two selected periods.

Thus, business growth, seasonal performance, and campaign effectiveness can be evaluated effectively.

---

### [10] Detailed Order Analysis

The dashboard provides transaction-level information for:

- Sales
- Profit
- Discounts
- Net Sales
- Products
- Customers
- Promotions

Thus, users can perform detailed drill-down analysis and identify factors affecting business performance.

---

## Overall Conclusion

The Sales Data Analysis Dashboard provides a comprehensive view of business performance across products, promotions, regions, and time periods.

Key findings include:

- A total of 3,510 orders were processed.
- Premium technology products generated the highest sales and profit.
- Weekend Flash Sale offered the highest promotional discount.
- Major Indian cities contributed significantly to overall revenue.
- Profit increases consistently with Net Sales.
- Sales remained stable across the reporting period with identifiable peak-demand periods.

Thus, the dashboard enables stakeholders to make informed decisions regarding product strategy, promotional planning, and business growth.

---

## Business Recommendations

1. Focus marketing and inventory planning on top-performing products.
2. Investigate low-performing products and optimize promotional strategies.
3. Leverage high-performing cities for targeted marketing campaigns.
4. Analyze peak sales periods to improve forecasting and inventory planning.
5. Monitor promotional effectiveness to maintain a balance between sales growth and profitability.

---

## Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Data visualization

---

## Project Files

- Sales_Data_Analysis.pbix



- Dataset File
(https://github.com/user-attachments/files/28677217/Store%2BData.xlsx) 

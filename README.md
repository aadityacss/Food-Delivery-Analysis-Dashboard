# 🍔 Food Delivery Data Analysis Dashboard

## 📌 Short Description & Purpose
This project features a comprehensive Power BI dashboard designed to analyze food delivery operations and restaurant performance. The purpose of this analysis is to provide actionable business intelligence to management, helping them optimize delivery times, identify top-performing restaurant partners, and track customer satisfaction trends across multiple cities.

## 💻 Tech Stack Used
*   *Data Visualization & Modeling:* Power BI
*   *Data Processing & Storage:* Microsoft Excel 
*   *Querying & Calculated Measures:* DAX (Data Analysis Expressions)

## 📂 Data Source
The data was sourced from an internal operations <a href="https://github.com/aadityacss/Food-Delivery-Analysis-Dashboard/blob/main/Food-Delivery-Data.xlsx">Dataset</a> which includes transaction-level details such as Order ID, Order Date, Customer ID, Restaurant Name, City, Food Category, Order Value, Quantity, Delivery Time, Ratings, and Order Status.

## 🚀 Features and Highlights

### 1. Business Problem
Management lacked visibility into operational bottlenecks and partner performance. Specifically, they needed a data-driven way to identify:
*   Where and why delivery bottlenecks are occurring.
*   Which restaurant partnerships are driving the highest revenue and volume.
*   How delivery performance correlates with customer satisfaction trends.

### 2. Dashboard Goal
To provide an interactive, high-level overview and deep-dive capabilities into two main areas:
*   *Delivery Analysis:* Tracking average, minimum, and maximum delivery times across different cities and identifying the proportion of delayed vs. delivered orders.
*   *Restaurant Analysis:* Evaluating restaurant performance based on total revenue, order volume, and month-over-month revenue trends.

### 3. Key DAX Measures Used
To enable dynamic filtering and accurate KPI tracking, several DAX measures were created. Key examples include:
*   *Min Delivery Time:* Min Delivery Time = MIN('Sheet1'[Delivery Time])
*   *Max Delivery Time:* Max Delivery Time = MAX('Sheet1'[Delivery Time])

### 4. Key Visuals & Dashboards
*   *KPI Cards:* High-level metrics tracking Total Revenue (4M), Total Orders (5K), Average Delivery Time (29.60 mins), and Average Rating (4.13).
*   *100% Stacked Bar Charts:* To visualize order status (Delivered, Delayed, Cancelled) normalized by city.
*   *Treemap / Donut Charts:* To instantly highlight top-earning restaurants.
*   *Time-Series Line Chart:* To track revenue generation by restaurant across different months (February, March, April).

### 5. Business Impact & Insights
*   *Delivery Bottlenecks:* The overall average delivery time is ~29.60 minutes. However, by tracking the maximum delivery time (up to 89 minutes) and the delayed order status (~5.1%), management can now investigate specific regional routes causing major delays.
*   *Restaurant Performance:* The Treemap clearly highlights the most lucrative partnerships, with "Taco Bell" and "Mainland China" driving significant portions of the 4M total revenue. This guides future marketing and partnership focus.
*   *Customer Satisfaction:* By monitoring the Average Rating (4.13) alongside delivery times, the business can accurately correlate operational speed with customer happiness.

## 📸 Dashboard Snapshots

### Overview Dashboard
![Overview Dashboard] <img width="1450" height="807" alt="Food Delivery Overview" src="https://github.com/user-attachments/assets/6dae1a43-0265-462b-a433-d793592a7201" />


### Delivery Analysis Report
![Delivery Analysis Report](Delivery-Analysis-Dashboard.png)

### Restaurant Analysis Report
![Restaurant Analysis Report](Restaurant-Analysis-Dashboard.png)

# Velocity Motors Sales Dashboard
## Background 
You are a data analyst at Velocity Motors, a dynamic automobile dealership renowned for its extensive portfolio of car models sourced from multiple manufacturers. The company is committed to offering customers a broad selection of vehicles, competitive pricing, and exceptional customer service. To enhance decision-making and operational efficiency, the Head of Operations has entrusted you with developing a centralized platform to visualize sales performance and uncover key trends. This platform aims to provide actionable insights that support strategic planning and drive business growth.

# High Level Insights

## 1. Overall Sales Trends
- **Sales Growth**: The Year-over-Year (YoY) sales growth in 2023 was 23% compared to 2022, reflecting a positive trend in overall sales performance.
- **Volume Growth**: The number of cars sold in 2023 saw a 24% YoY increase, indicating a strong upward trajectory in sales volume.
- **Average Sales Stability**: Despite the overall YoY growth, the average sales per unit showed a modest decline of 0.7% compared to the previous year, suggesting minor fluctuations in pricing or sales mix.
  
## 2. Emerging Patterns and Anomalies
- **Seasonal Peaks**:
  - Both 2022 and 2023 experienced sales peaks in **September** and **November**.
  - An anomaly was observed in **May 2023**, which saw a **59% increase** in sales compared to May 2022, marking a unique early-year peak.

## 3. Performance by Product Categories and Regions
- **Top Categories (2023)**:
  - **SUVs** led the sales with **27%** of total yearly sales, surpassing **Hatchbacks** (22%), which had topped in 2022 with **28%**.
  - **Sedans** maintained their share at **20%** for both years.
  - This shift may indicate changing customer preferences favouring SUVs.
  
- **Colour Preferences**:
  - **Pale White** dominated with **47%** of total sales in 2023, up from **45%** in 2022.
  - **Black** remained stable at **33%**, while **Red** saw a decline, dropping from **22%** in 2022 to **19%** in 2023.
  
- **Regional Contribution**:
  - Sales were evenly distributed across regions, with **13% share** each.
  - **Austin** and **Scottsdale** emerged as top-performing regions, contributing **17%** and **14%** to total sales, respectively.

## 4. Brand and Dealer Performance
- **Top 10 Dealers**: The leading dealers remained consistent across 2022 and 2023, showing no significant changes in sales distribution.
  - Progressive Shippers Cooperative Association
  - Rabun Used Car Sales
  - Race Car Help
  - Ryder Truck Rental and Leasing
  - Saab-Belle Dodge
  - Scrivener Performance Engineering
  - Star Enterprises Inc
  - Suburban Ford
  - Tri-State Mack Inc
  - U-Haul Co

# Objective
We're tasked to design and develop a dynamic and interactive Car Sales Dashboard using Power BI. The dashboard will visualize critical KPIs related to the car sales, as well as provide charts and tables to help analyze sales data on a granular level, enabling stakeholders of Velocity Motors to understand their sales performance over time and make data-driven decisions. 

## KPI Requirements for Dashboard
### Sales Overview
- **Year-to-Date (YTD) Total Sales**: The total number of cars sold from the beginning of the current year up to the present date, providing an overview of sales performance for the year.
- **Month-to-Date (MTD) Total Sales**: The total number of cars sold in the current month up to the present date, enabling tracking of monthly sales performance.
- **Year-over-Year (YOY) Growth in Total Sales**: The percentage change in total sales compared to the same period in the previous year, indicating the trend in sales performance.
- **Difference between YTD Sales and Previous Year-to-Date (PTYD) Sales**: The numerical difference between YTD total sales of the current year and total sales of the same period in the previous year, showing the increase or decrease in sales compared to the previous year.

### Average Price Analysis
- **YTD Average Price**: The average selling price of cars from the beginning of the current year up to the present date.
- **MTD Average Price**: The average selling price of cars in the current month up to the present date.
- **YOY Growth in Average Price**: The percentage change in average price compared to the same period in the previous year, indicating the trend in average price.
- **Difference between YTD Average Price and PTYD Average Price**: The numerical difference between YTD average price of the current year and average price of the same period in the previous year, showing the increase or decrease in average price compared to the previous year.

### Cars Sold Metrics
- **YTD Cars Sold**: The total number of cars sold from the beginning of the current year up to the present date.
- **MTD Cars Sold**: The total number of cars sold in the current month up to the present date.
- **YOY Growth in Cars Sold**: The percentage change in the number of cars sold compared to the same period in the previous year, indicating the trend in car sales.
- **Difference between YTD Cars Sold and PTYD Cars Sold**: The numerical difference between YTD cars sold of the current year and cars sold of the same period in the previous year, showing the increase or decrease in car sales compared to the previous year.

## Visualization Requirements for Dashboard
- **YTD Sales Weekly Trend**: A line chart to illustrate the weekly trend of YTD sales.
- **YTD Total Sales by Body Style**: A pie chart to visualize the distribution of YTD total sales across different car body styles.
- **YTD Total Sales by Colour**: A pie chart to depict the contribution of various car colours to the YTD total sales.
- **YTD Cars Sold by Dealer Region**: A map chart to geographically visualize the YTD sales distribution of different dealer regions.
- **Company-Wise Sales Trend in Grid Form**: A tabular grid that displays the sales trend for each company.
- **Detailed Grid Showing All Car Sales Information**: A detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc.

## Data 

1. **Car ID:** Unique identifier for each car.
2. **Date:** Date of the sale.
3. **Customer Name:** Name of the customer purchasing the car.
4. **Gender:** Gender of the customer.
5. **Annual Income:** Annual income of the customer.
6. **Dealer Name:** Name of the dealership where the sale occurred.
7. **Company:** Manufacturer or company associated with the car.
8. **Model:** Model of the car.
9. **Engine:** Engine specifications of the car.
10. **Transmission:** Transmission type of the car.
11. **Color:** Color of the car.
12. **Price ($):** Total price of the car in dollars.
13. **Dealer Number:** Dealer number associated with the dealership.
14. **Body Style:** Body style of the car (e.g., sedan, SUV, truck).
15. **Phone:** Contact phone number of the customer.
16. **Dealer Region:** Geographical region of the dealership.  


    You can access the dataset [here](https://docs.google.com/spreadsheets/d/1UNvvsnQ136UyFt-L3lfDvOksTtUMm49n/edit#gid=1275895711).

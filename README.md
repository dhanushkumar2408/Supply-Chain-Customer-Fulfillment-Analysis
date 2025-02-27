# Supply Chain Analysis Project

## Business Problem
AtliQ Mart, a growing FMCG manufacturer headquartered in Gujarat, India, is operational in three cities: Surat, Ahmedabad, and Vadodara. The company aims to expand to other metro and Tier 1 cities in the next two years. However, a few key customers did not extend their annual contracts due to service issues. The suspected reason is that essential products were either not delivered on time or not delivered in full over a continued period, resulting in poor customer service.

## Overview
The objective of this project is to analyze the supply chain performance of AtliQ Mart by evaluating various supply chain metrics, identifying gaps in service delivery, and providing actionable recommendations to improve customer satisfaction.

## Tools Used
- Power BI
- DAX (Data Analysis Expressions)
![DAX](https://github.com/user-attachments/assets/e20d63ca-58c4-48a9-bfb9-dab5d477fa0c)


## What I Have Done
1. **Data Cleaning and Preparation:**
   - Processed the dataset to ensure consistency and remove missing values.
   - Created necessary calculated columns using DAX.

2. **Data Modeling:**
   - Established relationships between tables such as Orders, Customers, Products, and Shipments.
   - Created measures using DAX for performance KPIs.

3. **Dashboard Creation:**
   - Supply Chain Overview
   - Order Level Analysis
   - Line Level Analysis

4. **Filters Applied:**
   - Date
   - Month/Day
   - Product Category/Name
   - City
   - Customer Name
     
![Data Model](https://github.com/user-attachments/assets/2864950a-b9f4-4406-abdb-23b3910a3783)


## Insights
### Supply Chain Overview
- Critically low OTIF (On Time In Full) at **29.02%**, indicating major service issues.
- High Volume Fill Rate (**92%-97%**) suggesting quantity accuracy when shipped.
- Significant delivery delays, especially **3+ days late deliveries**.

### Order Level Analysis
- Consistent low OTIF performance across customers (**6% to 42%**).
- Fluctuations in performance metrics over time.
- Visual comparison showed large gaps between actual KPIs and targets.

### Line Level Analysis
- Low LIFR (Line Item Fill Rate) at **65.96%**, indicating fulfillment inefficiencies.
- Customer-specific variations in unfilled lines.
- Product-specific fulfillment challenges with higher unfilled rates.
- Regional performance disparities across Surat, Ahmedabad, and Vadodara.

## Recommendations
1. **Improve LIFR by Root Cause Analysis:**
   - Focus on inventory accuracy, warehouse operations, and order processing.

2. **Customer-Specific Fulfillment Improvements:**
   - Allocate dedicated inventory for key customers.
   - Improve product availability communication.

3. **Product-Specific Fulfillment Challenges:**
   - Optimize supplier reliability, lead times, and safety stock.

4. **Regional Fulfillment Disparities:**
   - Standardize best practices across cities.
   - Optimize inventory distribution and transportation routes.

5. **Inventory Management Practices:**
   - Implement real-time inventory tracking systems.
   - Improve demand forecasting.

6. **Customer Communication & Transparency:**
   - Real-time order tracking.
   - Structured inquiry and complaint handling.

## Data Model
The data model connects multiple tables such as:
- Orders
- Customers
- Products
- Shipments

![Data Model](https://github.com/user-attachments/assets/45fec006-402d-4f12-b3f6-b8ea83986f76)


## Conclusion
The analysis highlights significant fulfillment inefficiencies impacting customer satisfaction. The recommendations provide actionable insights to improve the supply chain performance, customer relationships, and operational efficiency.


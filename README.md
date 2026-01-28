# 🎯 Product Growth Analyst  
## Funnel & Cohort Retention Analysis  
### [Python] Cohort Analysis: Customer Retention, Segmented by Quantity & Revenue  

---

# I. Introduction

## 1. About Cohort Analysis

### What is Cohort Analysis?

Cohort analysis is an analytical technique that categorizes and divides data into groups (cohorts) with common characteristics prior to analysis. This technique helps isolate, analyze, and detect patterns in the lifecycle of users to optimize customer retention and better understand behavior.

Businesses use cohort analysis to understand trends over time and tailor product and service offers to specific user groups.

### Three Major Types of Cohorts

- **Time-based:** Groups customers by when they first used the product or service.  
- **Segment-based:** Groups customers by product type or service tier.  
- **Size-based:** Groups customers by company or order size.

## 2. Business Questions

Using Python to create time-based cohorts analysis that allows stakeholders to assess and compare retention, order items quantity and order revenue from different cohorts of customer to optimize and tailor products and services offers to these specific cohorts.

## 3. About the Dataset

The dataset is from Kaggle: [Online Sales in USA](https://www.kaggle.com/datasets/ytgangster/online-sales-in-usa).

Overview of dataset:

### Dataset Overview

![Dataset Overview](https://github.com/user-attachments/assets/8c7d6562-43fa-43a1-bb6b-d7baadf70be4), consists of 36 columns and 286392 entries, records online sales data of different products, several merchandise and electronic in different states in USA from October 2020 to September 2021.

### Selected Columns for Cohort Analysis
<img width="346" height="609" alt="image" src="https://github.com/user-attachments/assets/51c5861e-bbfc-4c68-8093-fb27585a5e35" />

Since the goal of this project is to analysize time-based cohorts, let's extract just necessary columns as follows:


<img width="569" height="170" alt="image" src="https://github.com/user-attachments/assets/1d3d7897-fbad-4559-96da-553362ff357d" />

## 4. About This Project

This project focuses on performing time-bases Cohort Analysis: Customers will be divided into acquisition cohorts depending on the years that they become customers. Due to the wide spread of customer acquisition years (from 1978 to 2017), this project will create 5-year-bins and then assign each of customer’s transaction from October 2020 to September 2021 into these bins.

The goal of this project is to point out the significant trends and patterns in retention rate, order items quantity and revenue of different customer cohorts based on their acquirement time, then give recommendations to optimize sales and marketing strategies to improve overall performance.

The project will follow these steps:

1. Install the environment
2. Import and clean the dataset
3. Assign cohorts
4. Calculate retention rates
5. Segment data by Quantity and Revenue
   
### Project Objectives

- Identify trends in retention
- Analyze order quantity behavior
- Analyze revenue patterns
- Generate strategic recommendations

### Project Workflow

1. Environment setup  
2. Data cleaning  
3. Cohort assignment  
4. Retention calculation  
5. Segmentation by quantity & revenue  

---

# II. Data Visualization

## 1. Number of Customers per Cohort

<img width="866" height="542" alt="image" src="https://github.com/user-attachments/assets/d5f537fb-2021-4f34-90fa-54b57f9ffb52" />

## 2. Customer Retention & Retention Rate

<img width="879" height="563" alt="image" src="https://github.com/user-attachments/assets/ce3d3cce-c74a-43da-b91e-5f2b1e6434a4" />
<img width="875" height="566" alt="image" src="https://github.com/user-attachments/assets/9a778fa2-1666-48db-bf73-83087f6550c7" />

## 3. Cohorts by Quantity

<img width="856" height="581" alt="image" src="https://github.com/user-attachments/assets/7611362f-eebd-4fc5-87f9-94846514a992" />

## 4. Cohorts by Revenue

<img width="881" height="566" alt="image" src="https://github.com/user-attachments/assets/4fe9687f-76f0-43a7-bd44-e3fd5a4f1aa5" />

---

# III. Key Insights

### Customer Base
- Long-term customers exist since 1978.
- New customer acquisition has steadily increased.

### Retention
- Peak retention: December 2020 (~33%) due to holiday season.
- Secondary peak: April 2021 (~22%).
- Lowest retention: February and Aug–Oct.

### Order Quantity
- Highest items per order: Feb 2021 for 1983–1988 cohort (~6 items).
- Quantity peaks in March and July.

### Revenue
- Highest value cohort: 1988–1993.
- August 2021: Orders exceeded $1,000 for this cohort.
- Strong seasonal spikes in Dec, Mar, and Apr.

---

# IV. Strategic Recommendations
- Newly acquired customers have been increasing steadily and have brought in a significant amount of orders and revenue. However, when converted to percentages, almost all cohorts, both old and new customers, have very similar trends and patterns in retention rate and revenue. In some cases, old customers even have higher average order values and sales amounts per order than new customers.
- Apart from acquisition new customers, it's important to maintain and leverage the business relationship with old, long-lasting customers. This brings a lot of benefits: less marketing costs, better feedback, positive word-of-mouth marketing, sustainable revenue, less churn, etc.
- It's necessary to investigate more about other factors such as Customer Acquisition Cost. Instead of spending expensive amount of money to acquire a new customer, it's worth to care old customer better: personalize customer experience, stay in touch, offer loyalty programs, offer incentives, etc.

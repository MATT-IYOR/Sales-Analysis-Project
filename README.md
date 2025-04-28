# Sales-Analysis-Project

## Table of contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Recomendations](#recomendations)

### Project Overview

The online_sales_dataset records online and in-store transactions, detailing products, sales channels, payment methods, shipping costs, and return statuses across multiple countries for customer and logistics analysis.
![Screenshot 2025-04-28 094944](https://github.com/user-attachments/assets/297b9fc5-c5a1-494d-917c-e1f19912ef02)
![Screenshot 2025-04-28 095048](https://github.com/user-attachments/assets/a64e06d6-b624-424c-ac3b-3e93dde9bdd6)

### Data set

The link source is attached:
[online_sales_dataset.xlsx](https://github.com/user-attachments/files/19941118/online_sales_dataset.xlsx)


### Tools

- Power BI- For data cleaning and Visualization

### Data Cleaning/Preparation

### Cleaning

1. I uploaded the dataset into Power Query
2. I cheked for incorrect data type and corected them
3. Merge separated Year,Month and Day columns to create a single date column
4. Check for missing values
5. Remove duplicates

### Preparation

I created the following measures for visualization that would help with getting the result needed.

1. Average order value and average order value percentage
2. Toatal customers and total customer percentage
3. Total sales and total sales percentage

EDA involved exploring the Sales dataset to answer the following questions

- What is the total revenue over time?
- Which products are the top-selling by quantity and revenue?
- How does sales performance vary across countries?
- What are the monthly or seasonal sales trends?
- Who are the top customers by sales value?

### Results/Findings

The analysis results are summarized as follows
1. January,June and December have the higest order to shipment delays with numbers upto 21-23 days.
2. Less orders are shipped from the puerto rico warehouse even though the puerto rico products provides better profit margin. e.g More O Brians Men's Neoprene was prioritized over Team Golf Pittersburgh even though Team Golf Pittersburgh had better profit Margin

### Recomendations

- Focus on improving Standard Class shipping to puerto rico and USA.
- Reallocate resources to peak months to avoid delays.
- Promote faster shipment modes for high-priority products.
- Reduce use of costly same-day shipments where delays are still high (not worth the cost) particularly for January,June and December



# Amazon-Sales-Data-Analysis

### Project Overview

This data analysis aims to provide insights into the sales performancee of Amazon over a period of , across seven Regions and 76 Countries. We intend to ideentify trends and patterns. Determine which regions and countries had more sales generally and in the individual products. The highest performing Sales Channel and Order priority.

### Data Sources

Sales Data: The primary dataset used for this analysis is the "Amazon Sales Data.csv" which containsdetailed information about each sales made by the company.

### Tools 

- Pandas - Creating Dataframe
- Python - Programming
- Seaborn
- Matplotlib

### Data Cleaning and Preparation

- The data came in clean, so there was no need to do a data cleaning process. 
- The date column was conveerted to datetime so as to prepare the data to get the delivery date for the products.

### Exploratory Data Analysis (EDA)
EDA involved exploring the sales data to answer questions such as

1. Products with the highest revenue and Profit
2. Products with the highest and least units sold
3. Countries and Regions with the highest revenue
4. Correlation between Revenue and Profit for each product in every country and Region
5. Correlation between Number of units sold, Revenue and Profit for each product in every country and Region
6. Percentage profit for each product
7. Percentage profit for each product for each product in every country and Region
8. Number of sales made through each sales channel
9. The highest and least used sales channel for each product.
10. The highest and least used sales channel for each product in every country and Region.
11. Order Priority for each product sold.
12. Time of delivery for each product
13. Products with the highest and least units sold in every country and Region.

### Data Analysis
It includes some interesting codes such as

for x in AmaCopydf.index:
  if AmaCopydf.loc[x, "Sales Channel" ] == "Offline" :
    AmaCopydf.loc[x, "Sales Channel" ] = "1"
elif AmaCopydf.loc[x, "Sales Channel" ] == "Online" :
  AmaCopydf.loc[x, "Sales Channel" ] = "2"

### Results

The analysis as can be seen, clearly shows the performance of each product in every Region and Country and  also a general performance namely,

- Total Units Sold
- Total Profit
- Total Revenue
- Percentage profit
- Most Sales Channel used
- Time of deelivery
- Delivery time

These insights will help Amazon develop a amrketing strategy for each product in every region and country and also determinee which products to prioritize and the sales channels to be focused on.

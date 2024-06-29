# Technical Report on Sales Data Insights

## Introduction
This report analyzes a dataset consisting of sales transactions to uncover key insights and patterns. The dataset includes various attributes such as order details, product types, sales amounts, customer information, and deal sizes. The purpose of this review is to identify trends and significant metrics that can inform business strategies and decisions. 

## The Dataset
The dataset was made available by [HNG](https://hng.tech/internship), [link](https://hng.tech/premium) and consists of 2823 rows and 25 columns.

## Data Cleaning Steps
Before conducting the analysis, a copy of the dataset was made and imported into Excel where several data-cleaning steps were performed to ensure the dataset was accurate and ready for analysis:

1. **Checked for Duplicates**: Verified the dataset and found no duplicate records.
2. **Checked Data Types**: Ensured all columns had appropriate data types.
3. **Merged Name Columns**: Combined the `CONTACTLASTNAME` and `CONTACTFIRSTNAME` columns into a single `FULLNAME` column.
4. **Renamed Columns**: Renamed `PRICEEACH` to `UNIT_PRICE`, `SALES` to `REVENUE`, `QTR_ID` to `QUARTER`, and `YEAR_ID` to `YEAR`.
5. **Converted Month ID**: Transformed `MONTH_ID` into `MONTH_NAME` using the first three characters of the month name.
6. **Quarter Column Prefix**: Added the prefix `Q-` to the `QUARTER` column for better understanding.
7. **Merged Address Columns**: Combined `ADDRESSLINE1` and `ADDRESSLINE2` into a single `ADDRESS` column.
8. **Deleted Irrelevant Columns**: Removed columns with blanks such as `STATE` and `POSTALCODE` as they were irrelevant to the analysis.<br>
The cleaning process made the data more concise, focusing on essential fields and ensuring data integrity for more accurate analysis.

### Tool Used
POWER QUERY EDITOR

## Observations
The analysis of the dataset reveals the following insights:

1. **Total Revenue and Orders**: 
   - The total revenue generated is $10,032,628.85.
   - A total of 2,823 orders were recorded.
   - The average quantity per order is 35 units.

2. **Product Popularity**:

   ![Image alt text](https://i.postimg.cc/Bb8G1CPp/Task-01.png)
   - Classic Cars are the most ordered product category with 967 orders.
   - Trains are the least popular product with only 77 orders.

3. **Geographical Distribution**:
   
   ![Image alt text](https://i.postimg.cc/q7jfbF8Q/Task-02.png)
   - The USA leads in the number of orders with a total of 1,004 orders.
   - Ireland has the lowest number of orders, amounting to 16.

4. **Revenue by Year**:

    ![Image alt text](https://i.postimg.cc/rpR2Ks12/Task-03.png)
   - The year 2004 generated the highest revenue of $4,474,162.60, accounting for 47% of the total revenue.
   - The year 2003 had the lowest revenue at $1,791,486.71, accounting for only 18% of total revenue

5. **Monthly Revenue**:

    ![Image alt text](https://i.postimg.cc/fLx4fPqH/Task-04.png)
   - November is the highest revenue-generating month with $2,118,885.67.
   - June records the lowest revenue with $454,756.78.

6. **Deal Sizes**:
   - Medium-sized deals are the most common with 1,384 orders.
   - Large deals are the least frequent with only 157 orders.
  
   **THE DASHBOARD**:

    ![Image alt text](https://i.postimg.cc/RFmp4ZGR/Task-00.png)

## Conclusion
The analysis highlights that Classic Cars are the most popular product category, and the USA is the primary market for sales. The year 2004 and the month of November stand out as the most profitable periods across all years. Medium-sized deals are predominant, suggesting a focus on this segment could be beneficial.

### Recommendations for Further Analysis
1. **Customer Segmentation**: Analyzing the customer base to identify key demographics and purchasing patterns.
2. **Product Performance**: Investigating the factors contributing to the popularity of Classic Cars and underperformance of Trains.
3. **Seasonal Trends**: Examining monthly sales data in more detail to understand seasonal influences.
4. **Deal Size Optimization**: Exploring strategies to increase the number of large deals.

These insights can help tailor marketing strategies, optimize inventory management, and enhance customer targeting efforts.

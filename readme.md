# MYSQL_Project: Walmart Sales Data Analysis

This project endeavors to delve into the Walmart Sales dataset with the goal of comprehending the performance of key branches and products, analyzing sales trends across various products, and examining customer behavior. The objective is to explore opportunities for enhancing and optimizing sales strategies. The dataset utilized in this project was sourced from the Walmart Sales Forecasting Competition hosted on Kaggle.

 ## Dataset Link: https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting



### NOTE: While refering to the sql query, it should be noted that a single question might contain couple of queries in order to solve. Firstly the author has solved to get overall view of the acceptable
### answer (skeleton query) and later there will be combination of these skeleton query to answer the requred question.


 
## Description of Dataset:

There are two datasets in this repository. The dataset named WalmartSalesData.csv is the initial dataset in which the author started his Exploratory Data Analysis endevour. The second dataset (WalmartSalesData_Recreated.csv) is the dataset with appropriate application of feature engineering.

## WalmartSalesData.csv:

![image](https://github.com/Prithak8/MYSQL-Project-Walmart_Sales_Data_Analysis/assets/109690999/becc5433-9169-4979-8190-8c29df119150)


## WalmartSalesData_Recreated.csv


![image](https://github.com/Prithak8/MYSQL-Project-Walmart_Sales_Data_Analysis/assets/109690999/20ee1e05-62ec-4151-9b14-49e496339392)


## Product Evaluation
Conduct an in-depth analysis of the data to grasp the performance of various product lines, identifying both top-performing lines and those in need of improvement.

## Sales Review
This analysis aims to decipher sales trends for products, providing insights to assess the effectiveness of different sales strategies and to pinpoint necessary modifications for enhancing sales figures.

## Client Examination  (Customer)
Uncover distinct customer segments, purchasing patterns, and the profitability associated with each segment through this analysis.

# Methodology Employed

### Data Preparation: 

Initially, data inspection is carried out to detect and handle NULL and missing values, utilizing data replacement techniques when necessary.
### Database Creation: 

A database is established, including table creation and data insertion.

### Identification of Null Columns: 

Columns containing null values are identified, although our database has none due to the implementation of NOT NULL constraints during table creation, effectively filtering out null values.

## Feature Enhancement:
New columns are generated from existing ones to enrich the dataset.

### Introduction of "time_of_day": 
This new column provides insights into sales activity during different parts of the day (Morning, Afternoon, Evening), aiding in understanding peak sales periods.

### Inclusion of "day_name": 
This column captures the day of the week for each transaction (Mon, Tue, Wed, Thur, Fri), facilitating analysis of branch activity patterns throughout the week.
### Integration of "month_name": 
This column extracts the month of the year for each transaction (Jan, Feb, Mar), enabling assessment of sales and profit trends across different months.




# Business Questions To Answer


## Generic Question

How many unique cities does the data have?

In which city is each branch?


## Product


How many unique product lines does the data have?

What is the most common payment method?

What is the most selling product line?

What is the total revenue by month?

What month had the largest COGS?

What product line had the largest revenue?

What is the city with the largest revenue?

What product line had the largest VAT?

Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales

Which branch sold more products than average product sold?

What is the most common product line by gender?

What is the average rating of each product line?


## Sales


Number of sales made in each time of the day per weekday

Which of the customer types brings the most revenue?

Which city has the largest tax percent/ VAT (Value Added Tax)?

Which customer type pays the most in VAT?


## Customer


How many unique customer types does the data have?

How many unique payment methods does the data have?

What is the most common customer type?

Which customer type buys the most?

What is the gender of most of the customers?

What is the gender distribution per branch?

Which time of the day do customers give most ratings?

Which time of the day do customers give most ratings per branch?

Which day fo the week has the best avg ratings?

Which day of the week has the best average ratings per branch?


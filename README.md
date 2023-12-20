# Sales and Customer Data Analysis

## Table of Contents:

- [Project Overview](ProjectOverview)
  

- [Data Sources](DataSources)

- [Tools](Tools)

- [Data Cleaning/Preparation](DataCleanining/Preparation)

- [ExploratoryDataAnalysis](ExploratoryDataAnlaysis)

- [Data Analysis](DataAnalysis)

- [Results/Findings](Results/Findings)

- [Recommendations](Recommendations)


## Project Overview

This data analysis project aims to provide insights into the sales performance of an e-commerce company over the past year. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance

Created dashboard in Power BI for understanding Sales and Customer Data  with the help of visualizing relevant KPIs and metrics in the dataset provided.

Utilized the resources provided, including podcasts and articles, to enhance your understanding of data visualization and upskilling.
 
 
### Data Sources:[Download Here](https://www.kaggle.com/datasets/dataceo/sales-and-customer-data/data)

 The Primary Data set used for Data Analysis is 
 
 "Customerdata.xls " , 
 
 "Sales Data.xls"
 
 files containing detail information about Sales and Customer Data
 
### Tools:

-Excel

-Power BI

### Data Cleaning/Preparation:

Data Loading and Inspection

Handling Missing Values

Data Cleaning and formatting

###  Exploratory Data Analysis:

Overall Sales 
Which Category has Maximum Sales and Quantity
Predicting sales W.r.t to Malls, Age Category,Gender,Payment Method etc..
Analysing Data wrt Csutomised Date

### Data Analysis:(Some DAX Expressions)

Day of Week Name = FORMAT('sales_data'[weekday],"dddd")

price ranges = if(sales_data[price]<500,"Low","High")

weekday = WEEKDAY(sales_data[invoice_date],2)

weekday/weekend = if(sales_data[weekday]>5,"Weekend","Weekday")

Date-Time = NOW()

### Results/Findings:

Sales have been steadily decreased over the past Year

product Category Clothign is having Maximum Sales an Quantity

### Recommendations:

Product Category Souvenir has less quantity and sales

Products related to Male Category shall be increased







# Kraken Koffee 2023 Half-Time Review

## Interactive Power BI dashboard can be downloaded [here](https://github.com/ddolgova/Kraken_Koffee/blob/main/Kraken%20Coffee.pbix).

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Modeling](#data-modeling)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Results and Insights](#results-and-insights)

### Project Overview

This report provides an analysis of the performance of Kraken Koffee's three Florida locations. The insights gathered from this report are useful to pinpoint opportunities for performance improvement, to forecast the sales performance for the remainder of the year, identify top performing products, set sales goals, and identify patterns in store attendance volume. 

<img width="303" alt="Kraken_Koffee_Whole" src="https://github.com/user-attachments/assets/d3d6ea18-6d0d-4882-bef5-27e2149b6072">

<img width="1225" alt="Kraken_Koffee1" src="https://github.com/user-attachments/assets/c15c6ebd-8129-4c91-a9f1-caa4fb7318d5">

<img width="1220" alt="Kraken_Koffee2" src="https://github.com/user-attachments/assets/599efc01-6951-44de-b75c-879aaba8cb18">

<img width="1219" alt="Kraken_Koffee3" src="https://github.com/user-attachments/assets/3203cf3a-7706-4a4e-b010-1fe83ef43613">

### Data Sources

Kraken Koffee Sales Data: The main dataset used for this report is the “Kraken_Koffee_Sales+-+Excel+Version.xlsx” file, which holds information about sales of Kraken Koffee products in the three flagship Florida stores.

### Tools

- Excel: Data cleaning 
- Power Query Editor: Data cleaning, data modeling
- Power BI: Data analysis, data modeling, report building

### Data Cleaning and Preparation

In the first phase of data preparation, I went through the following procedure:

1. Loading the data and performing the initial assessment
2. Finding and treating missing and null values
3. Data formatting
4. Cleaning unnecessary special characters

### Data Modeling

In the next phase of data preparation, I did the following:

1. Inspecting the source data to determine the best modeling approach
2. Referencing a clean copy of the source data to create the fact and dimension tables
3. Determining the cardinality and relationships between the fact and dimension tables
4. Creating some initial DAX measures
5. Organizing DAX measures by order of complexity, making a table for nested and formatting measures.

### Exploratory Data Analysis
EDA included investigating the housing data to answer the following questions:

- Which Kraken Koffee Products are driving revenue so far in 2023?
- Which product is our strongest seller, and which product is our highest revenue generator?
- At what time of day do our Florida locations see the most revenue?
- What is an appropriate sales goal for 2023 based on current trends and predictions by data forecasting?
- What are some actionable recommendations to improve store performance based on findings in this report?

### Results and Insights

So far in 2023 there has been $698,812 in revenue across 149,116 transactions.
The strongest seller in terms of revenue is Davy Jones’ Sustainably Grown Organic Hot Chocolate Lg but this varies by location.
The most popular time of day for business at the Florida locations is around 10AM. Sales don’t usually take off until after 7AM and have mostly subsided by 8PM. This has resulted in the management team considering reevaluating opening and closing times to reflect the wind-up and drop-off in business during the earlier and later parts of the day.
Based on average daily sales so far in 2023, it is reasonable to have a sales target of $1,409,207 for the first year of sales. 

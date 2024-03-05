# PROJECT: QUANTIUM-DATA-ANALYTICS-VIRTUAL-INTERNSHIP-RETAIL-STORE-PERFORMANCE-ANALYSIS-AND-INSIGHTS

# OBJECTIVE:

    The objective of the dataset provided in the Quantium Data Analytics Virtual Internship is typically to analyze sales data from retail stores in order to gain insights into customer behavior, product performance, and overall store performance. By exploring the dataset, participants are expected to perform tasks such as:

    1. Identifying trends and patterns in sales data over July 2018 to June 2019 for 272 stores.
    2. Comparing the performance of different stores & product categories.
    3. Analyzing customer transaction data to understand purchasing behavior.
    4. Implementing statistical analyses to test hypotheses and make data-driven decisions for Control Stores and Trial Stores (A/B Testing or statistical Hypotheses Testing).
    5. Creating visualizations to communicate findings effectively.


## TABLE OF CONTENTS:

- [Introduction](#introduction)
- [Data Preprocessing](#data-Preprocessing)
- [Data Visualization](#data-visualization)
- [Statistical Analysis (A/B Testing)](#statistical-analysis)
- [Insights](#Insights)

## Introduction:

    Welcome to the Quantium Data Analytics Internship Task! This project focuses on analyzing sales data from retail stores to gain insights into customer behavior and inform strategic decisions within the chip category. The analysis aims to provide valuable insights that will contribute to the supermarket's strategic plan for the chip category in the upcoming half-year.

## Variables

*  **DATE**: Represents the date of the transaction.

* **TXN_ID**: Transaction ID, a unique identifier for each transaction.

*  **STORE_NBR**: Store number where the transaction occurred.

*  **PROD_NBR**: Product number of the item purchased in the transaction.

*  **PROD_NAME**: Name of the product purchased.

*  **PRODUCT**: Type or category of the product purchased.

*  **BRAND_NAME**: Brand name of the product purchased.

*  **grams**: Weight of the product purchased in grams.

*  **PROD_QTY**: Quantity of the product purchased in the transaction.

*  **TOT_SALES**: Total sales amount for the transaction.

*  **LYLTY_CARD_NBR**: Loyalty card number associated with the customer making the transaction.

*  **LIFESTAGE**: Life stage of the customer.

*  **PREMIUM_CUSTOMER**: Type of premium customer.


## Data Preprocessing:

    In this section, we should ensure that the dataset provided should be in a good quality. Good Quality in the sense no inconsistences, more reliability, scalability and completeness. Here, I have checked about missing data, Data types of the variables using for the analysis, Proper identification for variables and for data cleansing part i have used the Z-score method-which is a statistical methodology to clean out the outliers in the dataset which will be capable of giving skeptical on insights for the Stores performances.


## Data Visualization

Utilizing various visualization techniques, the project aims to present a clear and insightful overview of the sales data. This section includes visualizations of trends, patterns, and anomalies in the dataset.

## Statistical Analysis

### Monthly Sales Experience of Each Store

This section delves into the monthly sales data for each store, providing insights into the variations and trends over time.

### Comparison: Control Stores vs Trial Stores

A comparative analysis between control stores and trial stores, examining key metrics to identify any significant differences in sales performance.

### Pearson Correlation

Utilizing the Pearson correlation coefficient to quantify the relationship between trial and control stores in terms of total sales.

### Hypothesis Statements

- H0: There is a significant relationship between the Trial store and Control stores in terms of Total Sales (i.e., r=0).
- H1: There is a significant relationship between the Trial store and Control stores in terms of Total Sales (i.e., r≠0).

## Total Sales

Analyzing and interpreting the total sales data to gain insights into the overall performance of the stores.

## Average Price Per Unit

Examining the average price per unit across stores, providing insights into pricing strategies and potential impacts on sales.

## Independent Sample t-Test

### Hypothesis

- H0: There is no significant difference between the means of Control stores and Trial store in terms of the (measure). i.e., μi = μj
- H1: There is a significant difference between the means of Control stores and Trial store in terms of the (measure). i.e., μi ≠ μj

## Average Transaction Per Customer

Analyzing the average transaction per customer to understand customer behavior and its influence on sales.

## Conclusion (Task 3)

In the final section, the project concludes by summarizing the findings from the data visualization and statistical analysis. This includes key insights, recommendations, and implications for future actions.

Feel free to explore each section for more details on the analysis and findings.

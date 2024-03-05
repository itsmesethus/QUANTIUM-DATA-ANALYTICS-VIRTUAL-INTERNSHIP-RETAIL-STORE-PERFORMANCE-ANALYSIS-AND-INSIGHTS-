# PROJECT: QUANTIUM-DATA-ANALYTICS-VIRTUAL-INTERNSHIP-RETAIL-STORE-PERFORMANCE-ANALYSIS-AND-INSIGHTS

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


# OBJECTIVE:

   The objective of the dataset provided in the Quantium Data Analytics Virtual Internship is typically to analyze sales data from retail stores in order to gain insights into customer behavior, product performance, and overall store performance. By exploring the dataset, participants are expected to perform tasks such as:

*  Identifying trends and patterns in sales data over July 2018 to June 2019 for 272 stores.
* Comparing the performance of different stores & product categories.
* Analyzing customer transaction data to understand purchasing behavior.
* Implementing statistical analyses to test hypotheses and make data-driven decisions for Control Stores and Trial Stores (A/B Testing or statistical Hypotheses Testing).
*  Creating visualizations to communicate findings effectively.


## TABLE OF CONTENTS:

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Data Visualization](#data-visualization)
- [Statistical Hypotheses Testing](#statistical-hypotheses-testing-(A/B-Testing))
- [Insights](#insights)

## Introduction:

   Welcome to the Quantium Data Analytics Internship Task! This project focuses on analyzing sales data from retail stores to gain insights into customer behavior and inform strategic decisions within the chip category. The analysis aims to provide valuable insights that will contribute to the supermarket's strategic plan for the chip category in the upcoming half-year.


## Data Preprocessing:

In this section, we should ensure that the dataset provided should be in a good quality. Good Quality in the sense no inconsistences, more reliability, scalability and completeness. Here, I have checked about

*  Missing data
*  Data types of the variables using for the analysis
*  Proper identification for variables
*  Data cleansing Z-score method-which is a statistical methodology to clean out the outliers in the dataset.
    

## Data Visualization:

   Visulaizations such as 

* Boxplot for PREMIUM_CUSTOMERS.
* Distplot for TOT_SALES.
* WordCloud for BRAND_NAME to findout which brand/ product is much loved by the customers. 
* Barplot for  top categories sold for all the stores.
* PieChart for the PREMIUM_CUSTOMERS.
* Barplot for the type of Customer population(Life Stages) visiting to the stores often.
* Multiple Barplot for PREMIUM_CUSTOMERS categories by the LIFESTAGE.
* Multiple Barplot for PREMIUM_CUSTOMERS categories by  top  10 Product names solded.
* Barplot for Top 10 stores among 272 stores based on their revenues scored.
* LinePlot for the Sales of the stores peaked based on the monthly basis.
* Stacked Barplot for the Product Quantity pruchased by the customers.

## Statistical Hypotheses Testing (A/B Testing):

   In this part lot of data preparations was actually taken part. Created a pivot table for PROD_QTY and STORE_NBR based on their Total Sales.Utilized groupby and merge commands to create the proper structure for the dataset to be acessed for Statistical tests. For the Stores Comparisons based on their revenue performance I have splitted the stores into two categories. They are ,


   * Control Stores - stores are usually not fall under any criteria or conditions to follow when takend under the study or experiments based on its performances. (or) These are similar stores or locations where the intervention or change is not implemented. Control stores are used as a reference point to compare against the trial stores.

   * Trial Stores - stores are ones need to staisfy the certain conditions and everything will be monitored based on its real time performances and it will receives some extra treaments when compare to control stores. (or)  These are stores where the intervention or change is implemented. For example, if a new marketing campaign is being tested, trial stores might receive the new advertising materials or promotions.

   (Note: Level of Significance = 0.05)

    1. ONE-WAY ANOVA( Analysis of Variance ) - To determine if there are significant differences in the means of multiple groups and provides insights into which specific groups may differ from each other
    
     - Tested for any statistically significant difference among the PREMIUM_CUSTOMERS and PROD_QTY purchasng behavior for customers.

     - Tested for any statistically significant difference among the PREMIUM_CUSTOMERS and LIFESTAGE(population categoris of people) purchasing behavior for customers.

     - Tested for any statistically significant difference among the LIFESTAGE(population categoris of people)  and PROD_QTY purchased by customers.


    2. PEARSON CORRELATION - To test the statistical relationship or association between the performance of Control Stores and Trial Stores.
     
     - Hypotheses Statements,
         
        H0: There is significant relationship between the Trial store and Control stores in terms of Total Sales(ie., r=0)
        H1: There is a significant relationship between the Trial store and Control stores in terms of Total Sales(ie., r≠0).

    3. Independent t-test -  To determine if there are significant differences between the means of two independent groups

    - Hypotheses Statements,(NOTE: measure which may denote sales generated, Total sales, Average Transaction done)

        H0: There is no significant difference between the means of Control stores and Trial store in terms of the (measure). ie., μi = μj
        H1: There is no significant difference between the means of Control stores and Trial store in terms of the (measure). ie., μi ≠ μj

## Insights:

**From EDA:**
    
* Paso Sasla, El Paso, Sweet chilli and popd Swt are most prefered brands among the other brands among the population. *The SaltBinegar, Cheese and SourBream are the top 3 products highly consumed by the people from the dataset.

* The Premium customer segmentation among the people and its about 38.5% for Mainstream is the top most when considering the other two categories of Budget is about 35.2% and the premium for 28.3%.

* In the given data Older Singles/couples population is very high secondly the retireers, Older families and etc.. 
    - The older family poplulation prefers budget highly compare to other population.
    - The Retirees group prefers more on the mainstream category than other way of Premium segmentation.
    - Older Singles/Couples population prefers more on the Premium segmentation than any other  lifestage categories.
    - New families populations are the least participated among the any other population for the any preferences towards the premium segmentation.

* SaltBinegar is the top most of all 3 of the premium customer segmentation categories.

* SouthernChicken is lowest in the mainstream and premium in the top 10 products.

* SaltChips is the lowest in the budget category of the Premium customers.

* The Store no: 226 has the high amount of sales when considering the top 10 stroes. And store no:26 has the lowest among the top 10 stores based on in its total sales.

* The month December has the highest in terms of sales when compare to other months in the calendar year and the month Feb has the lowest sales among the months of the calendar years.

* The Young Singles and Couples are the top most group when compare to other groups. And Midage Singles and Couples stays at the lower level among the other groups on month wise total sales spending.

* Budget, Mainstream and Premium categories consists of Product quantity 2 than any other product quantity. And Mainstream is top most in the customer segmentation in the product quantity.


**From Statistical Hypotheses Testing:**

* There is significant effect on Premium customer categories on Total sales.

* There is a significant effect Product quantity categories on Total sales.

* There is a significant effect for Lifestage categories on Total sales.

* There is significant interaction between the Premium Customer and Lifestage over Total Sales

* There is a significant effect for Product quantity categories on Total sales.

* There is significant interaction between the Product quantity and Lifestage over Total Sales.

* The Control Stores(100,160,200) and Trial stores(77,86 and 88) have no significant corelation between control store and trail store based on the Total Sales.

* Control Store: 160, There is a significant Strong Positive correlation(uphill trend) found between the Control Store 160 and Trial store 77 based on Avg price/unit.

* There is a significant differences among the means of the Control Store(100 and 200) and Trial store 77 in terms of Total Sales.

* There is a significant differences among the means of the Control Store(100 and 200) and Trial store 78 in terms of Total Sales.

* There is a significant differences among the means of the Control Store: 200 and Trial store: 80 in terms of Total Sales.

* There is a significant differences among the means of the Control Store: 200 and Trial store: 86 in terms of Average Transaction per customer.

* There is a significant differences among the means of the Control Store: 200 and Trial store: 88 in terms of Average Transaction per customer.



 


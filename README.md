# Customer-Segmentation
## What is Customer Segmentation?
Customer segmentation is the process of dividing customers into groups based on common characteristics so companies can market to each group effectively and appropriately. A company might segment customers according to a wide range of factors, including:
* Demographics
* Transaction history
* Geography
* Psychographic

## Problem Statement
This project aims is to identify major customers. Customer segmentation is the process of segments on a transnational (extending or dividing your customers into sub-groups going beyond national boundaries based on shared features. transnational corporation.) data set which contains all the transactions occurring Because you use on-site data to optimize between 01/12/2010 and 09/12/2011 for advertising off-site, segmentation happens UK-based and registered non-store online after the fact, unlike customization and retail. The company mainly sells unique all-targeting. 
Occasion gifts. Many customers of the because you need to build triggers so that company are wholesalers. Your consumers see the advertisements Ecommerce customer segmentation divides when they arrive, you need to do your clients into smaller groups who share targeting and personalization before they have a common interest, making it easier to up with offers and calls to action.

## Data Description:(Attribute Information)
1. Invoice No:  Invoice number. Nominal, is a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
2. Stock Code: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct
3. Description: Product (item) name. Nominal.
4. Quantity: The quantities of each product (item) per transaction. Numeric.
5. Invoice Date: Invoice Date and time. Numeric, the day and time when each transaction was generated.
6. Unit Price: Unit price. Numeric, Product price per unit in sterling.
7. Customer ID: Customer number. Nominal, is a 5-digit integral number uniquely assigned to each customer.
8. Country: Country name. Nominal, is the name of the country where each customer resides.

## Steps involved:
## Exploratory Data Analysis
Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers you need, making it easier for data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumptions.

## Data pre-processing and transformation 
Data preprocessing is a data mining technique which is used to transform the raw data in a useful and efficient format. Whereas Data transformation is the process of converting, cleansing, and structuring data into a usable format that can be analyzed to support decision making processes, and to propel the growth of an organization.

## RFM analysis 
RFM analysis is a marketing technique used to quantitatively rank and group customers based on the recency, frequency and monetary total of their recent transactions to identify the best customers and perform targeted marketing campaigns.

## K-Means Clustering 
K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science.

## K-Means with Elbow Method and Silhouette Method  on RFM
Using Elbow method and Silhouette method, we get k=3 as a optimal value for 'k'

## Conclusion
 Throughout the evaluation, we went via diverse steps to carry out customer segmentation. We commenced with information wrangling in which we attempted to address null values, and duplicates and accomplished function adjustments. Next, we did a few exploratory information evaluations and attempted to attract observations from the capabilities we had in the dataset. Next, we formulated a few quantitative elements consisting of recency, frequency, and monetary referred to as RFM models for every one of the customers. We applied the KMeans clustering set of rules to those features. We additionally accomplished silhouette and elbow technique evaluation to decide the ideal no. of clusters turned into 3. We noticed clients having excessive recency and low frequency and financial values have been a part of one cluster and clients having low recency and excessive frequency, and financial values have been a part of any other cluster. However, there may be greater adjustments to this evaluation. One can also additionally pick out to cluster into greater no. relying on corporation targets and preferences. The classified function after clustering may be fed into classification-supervised machine learning algorithms that might are expecting the lessons for a brand new set of observations. The clustering also can be accomplished on a brand new set of features consisting of the kind of products every customer decide to shop for often, locating out client lifetime value (clv), segmenting on the premise of the term they visit, and lots greater. As gadget mastering has grown to be greater of an ART, there's not anything consisting of proper or wrong. We best try and get nice results which can in shape our very last targets. There is, and usually will be, a want to improve, going forward. we see that Customers are nicely separated whilst we cluster them with the aid of using Recency, Frequency, and Monetary and the ideal number of clusters is equal to 3. . 



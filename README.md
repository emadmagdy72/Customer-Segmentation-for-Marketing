# Customer Segmentation for Marketing Strategy

This project aims to develop a customer segmentation to define marketing strategies based on the behavior of credit card holders. The provided dataset summarizes the usage behavior of approximately 9000 active credit card holders over the last 6 months. The dataset consists of 18 behavioral variables at the customer level.

## Dataset Description

The dataset includes the following variables:

- **CUST_ID**: Identification of Credit Card holder (Categorical)
- **BALANCE**: Balance amount left in the account to make purchases
- **BALANCE_FREQUENCY**: Frequency of balance updates (score between 0 and 1, where 1 = frequently updated, 0 = not frequently updated)
- **PURCHASES**: Amount of purchases made from the account
- **ONEOFF_PURCHASES**: Maximum purchase amount done in one-go
- **INSTALLMENTS_PURCHASES**: Amount of purchases done in installments
- **CASH_ADVANCE**: Cash in advance given by the user
- **PURCHASES_FREQUENCY**: Frequency of purchases being made (score between 0 and 1, where 1 = frequently purchased, 0 = not frequently purchased)
- **ONEOFF_PURCHASES_FREQUENCY**: Frequency of one-off purchases (score between 0 and 1, where 1 = frequently purchased, 0 = not frequently purchased)
- **PURCHASES_INSTALLMENTS_FREQUENCY**: Frequency of purchases in installments being done (score between 0 and 1, where 1 = frequently done, 0 = not frequently done)
- **CASH_ADVANCE_FREQUENCY**: Frequency of cash in advance being paid
- **CASH_ADVANCE_TRX**: Number of transactions made with "Cash in Advanced"
- **PURCHASES_TRX**: Number of purchase transactions made
- **CREDIT_LIMIT**: Limit of Credit Card for user
- **PAYMENTS**: Amount of Payment done by the user
- **MINIMUM_PAYMENTS**: Minimum amount of payments made by the user
- **PRC_FULL_PAYMENT**: Percent of full payment paid by the user
- **TENURE**: Tenure of credit card service for the user


## Algorithms Used

In this project, the following algorithms for unsupervised learning and dimensionality reduction were employed:

- **Hierarchical Clustering**
- **K-means**
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- **Gaussian Mixtures**
- **Principal Component Analysis (PCA)**


## Clustering Analysis
![customer segmentation](https://github.com/emadmagdy72/Customer-Segmentation-for-Marketing/assets/67216285/e0a964ec-1b7b-40d2-80f1-53a62965be6f)

### Cluster 0

**Customer Behavior Overview:**
Customers in Cluster 0 prefer making purchases in installments rather than opting for cash advances.

**Purchase Behavior:**
- Mean amount of purchases made in installments: $761.84
- High number of purchase transactions (mean of approximately 23 transactions)
- Around 76% of customers exhibit frequent purchase behavior
- Mean amount of total purchases: $1528

### Cluster 1

**Customer Behavior Overview:**
Customers in Cluster 1 exhibit a preference for making one-off purchases rather than opting for installment payments.

**Purchase Behavior:**
- Majority of purchases are one-off transactions
- Avoidance of purchases in installments
- Relatively lower number of purchase transactions (mean of approximately 8 transactions)
- Around 36% of customers exhibit frequent purchase behavior
- Mean amount of total purchases: $903

### Cluster 2

**Customer Behavior Overview:**
Customers in Cluster 2 prefer using cash advances rather than making purchases in installments.

**Purchase Behavior:**
- Majority of purchases are through cash advances
- None of the customers exhibit frequent purchase behavior
- Mean amount of cash advances: $2011

### Cluster 3

**Customer Behavior Overview:**
Customers in Cluster 3 demonstrate a preference for making purchases both in installments and through cash advances.

**Purchase Behavior:**
- Mean amount of purchases made in installments: $701.84
- High number of purchase transactions (mean of approximately 25 transactions)
- Around 74% of customers exhibit frequent purchase behavior
- Mean amount of total purchases: $1501
- Mean amount of cash advances: $2080.54

### Cluster 4

**Customer Behavior Overview:**
Customers in Cluster 4 prefer using cash advances rather than making purchases in installments.

**Purchase Behavior:**
- Mean amount of purchases: $669
- Fewer purchase transactions (mean of approximately 6 transactions)
- Around 27% of customers exhibit frequent purchase behavior
- Mean amount of cash advances: $2046.54

## Business Insights

Based on the clustering analysis, different customer segments have been identified, each demonstrating unique preferences and behaviors. These insights can be utilized to tailor marketing strategies targeted at specific customer segments, thereby maximizing the effectiveness of marketing efforts.

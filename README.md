 # "CUSTOMER SEGMENTATION"

#### By Suci Aulya Putri

# Use Case Summary
**Objective Statement:**
1. Get business insight about how many product sold every month.
2. Get business insight about how much customer spend their money every month.
3. Get business insight about how many customers make transactions each month.
4. Get business insight about how much is the frequency of transactions in months, days, and hours.
5. Get business insight about the most popular products.
6. Get business insight about the most consumers by country.
7. To reduce risk in deciding where, when, how, and to whom a product, service, or brand will be marketed.
8. To increase marketing efficiency by directing effort specifically toward the designated segment in a manner consistent with that segment’s characteristics.

**Challenges:**
1. Large size of data, can not maintain by excel spreadsheet.
2. Need several coordination from each department.
3. Demography data have a lot missing values.

**Business Benefit:**
1. Helping Business Development Team to create product differentiation based on the characteristic for each customer.
2. Know how to treat customer with specific criteria.

**Expected Outcome:**
1. Know how many product sold every month.
2. Know how much customer spend their money every month.
3. Know how many customers make transactions each month.
4. Know how much is the frequency of transactions in months, days, and hours.
5. Know the most popular products.
6. Know the most customer by the country.
7. Customer segmentation analysis.
8. Recommendation based on customer segmentation.

# Data Understanding
* The data is a real online retail transaction data set of two years.

* The data consists of 2 datasets where:
  - Dataset 1: 
      * Online Retail Dataset between 01/12/2009 until 09/12/2010. 
      * Dataset 1 consists of 525461 rows and 8 columns.
  - Dataset 2: 
      * Online Retail Dataset between 01/12/2010 until 09/12/2011.
      * Dataset 2 consists of 541910 rows and 8 columns.

* This Online Retail II data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 until 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.

* [Source Data](https://www.kaggle.com/mathchi/online-retail-ii-data-set-from-ml-repository)

* Data Dictionary: 
  - Invoice: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
  - StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
  - Description: Product (item) name. Nominal.
  - Quantity: The quantities of each product (item) per transaction. Numeric.
  - Invoice Date: Invice date and time. Numeric. The day and time when a transaction was generated.
  - Price: Unit price. Numeric. Product price per unit in sterling (Â£).
  - Customer ID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
  - Country: Country name. Nominal. The name of the country where a customer resides.

# Business Understanding
**Retail** is the process of selling consumer goods or services to customers through multiple channels of distribution to earn a profit. 

This case has some **business question** using the data:
1. How many product sold every month?
2. How much customer spend their money every month?
3. How many customers make transactions each month?
4. How much is the frequency of transactions in months, days, and hours?
5. What products are the most popular?
6. Most consumers by country?
7. How about Customer segmentation analysis?
8. How about recommendation based on customer segmentation?

# Exploratory Data
## Number Of Products Sold Each Month 
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082048-329869d6-ec7f-47c1-9c63-96388b13098d.png)

Product sold in November has the highest quantity that has around 13,97% product sold from all transaction along 1 year.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082079-494e53b8-8f04-483c-87c3-b30613031889.png)

Product sold in November has the highest quantity that has around 15,42% product sold from all transaction along 1 year.

**The business team can increase sales in this month such as promoting new products to customers in this month.**

## The Amount of Money That Customers Spend on Each Month 
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082082-5fdfe03a-2b7a-4535-8276-7f0b7c7c497a.png)

Revenue in November has the highest amount that has around 14,11% revenue from total revenue along 1 year.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082086-57cdc8dc-0d32-46dc-9353-f7e9368f7f33.png)

Revenue in November has the highest amount that has around 15,6% revenue from total revenue along 1 year.

**The business team can replicate the success of sales strategies in November to be implemented in other months.**

## Number of Customers Who Make Transactions Every Month
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082088-7199606a-a6dd-4d5a-a7f2-ad8da685a295.png)

The number of customers from December 2009 to November 2010 was fluctuating. However, in general, the number of customers almost every month tends to show an increase, only in January, April, July, and August do the number of customers show a decrease.The business team can provide special discounts in January, April, July, and August to increase the number of customers and sales in this month.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082093-147c1e73-3212-47ed-bc61-0bc3a3a08126.png)

The number of customers from December 2010 to November 2011 was fluctuating. However, in general, the number of customers almost every month tends to show an increase, only in January, February,and April do the number of customers show a decrease.The business team can provide special discounts in January, February,and April to increase the number of customers and sales in this month.

## Transaction Frequency Every Month, Day, and Hour
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082130-47d17351-9d24-4b83-947a-ed99960601a7.png)

- The number of customers in November is the highest number of customers that has around 15,3% of the total customers along 1 year. The business team can increase sales by promoting new products to customers in November.
- Most consumers make transactions on Thursday, which is around 19,8% of the total daily transactions. Business teams can increase sales by promoting new products to customers on Thursday
- Most consumers order the products at 12 AM with a transaction amount of 17.8% of the total daily transactions. Business teams can increase sales by promoting new products to customers at 12 AM.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082149-6d2ee87a-f584-47e3-8033-346035db2d8f.png)

- The number of customers in November is the highest number of customers that has around 17,3% of the total customers along 1 year. The business team can increase sales by promoting new products to customers in November.
- Most consumers make transactions on Thursday, which is around 19,5% of the total daily transactions. Business teams can increase sales by promoting new products to customers on Thursday.
- Most consumers order the products at 12 AM with a transaction amount of 18,2% of the total daily transactions. Business teams can increase sales by promoting new products to customers at 12 AM.


## The Most Popular Product 
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082162-6d31fd8f-a6a4-4c6d-97f0-419a90859749.png)

White Hanging Heart T-Light Holder became the product that was most in-demand by consumers in 2010. The number of purchases of White Hanging Heart T-Light Holder reached 2369 units in 2010.The business team can provide special discounts from this product to attract more users.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082166-588e7d14-523c-44f5-b2db-86141903abbc.png)

White Hanging Heart T-Light Holder became the product that was most in-demand by consumers in 2011. The number of purchases of White Hanging Heart T-Light reached 1625 units in 2011.The business team can provide special discounts from this product to attract more users.

## The Most Customers By Country
### In 2009 - 2010
![image](https://user-images.githubusercontent.com/88583319/132082174-d6e97cac-1969-4dc8-9ef3-0911e591702a.png)

The United Kingdom became the city with the highest number of customers in 2010. The total number of customers in United Kingdom reached 302776 (91.71%) customers in 2010. The business team can focus on promotions in the United Kingdom to increase sales.

### In 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132082182-59768590-14eb-4a15-94b8-7015bb2c77d1.png)

The United Kingdom became the city with the highest number of customers in 2011. The total number of customers in United Kingdom reached 286683 (90%) customers in 2011. The business team can focus on promotions in the United Kingdom to increase sales.

# Customer Segementation

# 1. Recency, Frequency, Monetary Value (RFM) Analysis
**Recency, Frequency, Monetary Value (RFM) analysis method** is a method of customer analysis and segmentation based on customer habits. 
The variables used to perform RFM analysis are:

- Recency	: How recently the customer made a transaction.
- Frequency	: How often customers make transactions
- Monetary	: How many transactions the customer has made

**In this case**, the dataset contains transaction data from 01/12/2009 to 01/12/2011, so the RFM Value is treated as follows:
- Recency	: The difference between the last day the customer made a transaction and the day he did the analysis. In this case, the day of analysis uses the data of the last day of the transaction.
- Frequency	: The number of transactions made by customers from 01/12/2009 to 01/12/2011.
- Monetary	: Total order amount issued by customers from 01/12/2009 to 01/12/2011.

Here are the **steps** in RFM analysis: 
### 1. Calculate RFM Value

#### RFM Value in 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132128320-480ccc71-b93c-4ba9-b1e1-edbe3eccd324.png)

#### RFM Value in 2010-2011

![image](https://user-images.githubusercontent.com/88583319/132128428-22951cef-f7cf-41c2-962d-6b766e076ff8.png)


### 2. Calculate RFM Score 
   The calculation of the individual RFM Score can be done using the Quartile statistical method.
   The steps is:
   1. Split the metrics into segments using quantiles.
   2. Assign a score from 1 to 4 to Recency, Frequency and Monetary.
   3. Four is the best/highest value, and one is the lowest/worst value.

#### RFM Score in 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132128283-fb67ae04-c99d-436e-afa0-b66673d5a291.png)
#### RFM Score in 2010- 2011 
![image](https://user-images.githubusercontent.com/88583319/132129170-1644b15d-6ae9-4596-9b32-1424c4a1de48.png)

### 3. Calculate the total RFM score
   A total RFM score is calculated simply by combining individual RFM score numbers.
#### In 2009 - 2010   
  ![image](https://user-images.githubusercontent.com/88583319/132128357-f08e66b7-c186-4164-9e2d-c4e3ef43675f.png)
  
#### In 2010-2011

![image](https://user-images.githubusercontent.com/88583319/132128462-7643397d-8f68-4787-8d18-c643d14f8fef.png)


### 4. Labelling

![image](https://user-images.githubusercontent.com/88583319/132082328-911e7ea3-2e72-4b94-ba19-b3446a2474a8.png)
#### Labelling in 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132128515-1c0e5999-d7d7-4fc1-ae8c-35e33eb183f0.png)

#### Labelling in 2010 - 2011
![image](https://user-images.githubusercontent.com/88583319/132128492-3bc21b74-0d17-4165-8407-1d625b41135e.png)

## Customer Segmentation
### In 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132082332-ed358536-7aad-45b1-9e37-9976f83094b2.png)

### In 2010-2011
![image](https://user-images.githubusercontent.com/88583319/132082338-231a0285-3b25-43e7-a2df-dc8f166c168b.png)

# 2. K-Means Clustering
**K-Means clustering algorithm**  is an unsupervised machine learning algorithm that uses multiple iterations to segment the unlabeled data points into K different clusters in a way such that each data point belongs to only a single group that has similar properties.
**K-means gives the best result under the following conditions:**
1. Data’s distribution is not skewed.

![image](https://user-images.githubusercontent.com/88583319/132128560-7d1b5075-6f7b-4b46-9cbb-d1971ece36cc.png)

The data is highly skewed,therefore we will perform log transformations to reduce the skewness of each variable.I add a small constant as log transformation demands all the values to be positive.

2. Data is standardised 
    (i.e. mean of 0 and standard deviation of 1).
    
![image](https://user-images.githubusercontent.com/88583319/132128597-a9b7f09c-3266-48fb-93f5-5dbca9e33d6f.png)


## Finding the Optimal Number of Clusters Using Elbow Method
### In 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132128662-1afab1a1-c21e-403c-b43f-28aae0d61480.png)

The cluster value where this decrease in inertia value becomes constant can be chosen as the right cluster value for our data. Looking at the above elbow curve, we can choose any number of clusters between 3 to 5.

![image](https://user-images.githubusercontent.com/88583319/132128681-26b32af2-2869-4e8f-8e3b-68e4f347c6b5.png)
![image](https://user-images.githubusercontent.com/88583319/132128688-54516cd8-305b-41a9-b6a7-110a84168249.png)

From the flattened graphs and the snake plots it is evident that having a cluster value of 4, segments our customers well. We could also go for higher number of clusters, it completely depends on how the company wants to segment their customers.

### In 2010-2011
![image](https://user-images.githubusercontent.com/88583319/132128711-45400ef0-06a5-47df-8384-2ec9c01d5027.png)
The cluster value where this decrease in inertia value becomes constant can be chosen as the right cluster value for our data. Looking at the above elbow curve, we can choose any number of clusters between 3 to 5.

![image](https://user-images.githubusercontent.com/88583319/132128719-aa4697d9-f7ff-4298-94f5-8de0421fb38c.png)
![image](https://user-images.githubusercontent.com/88583319/132128723-58a90fe4-c672-4f7b-b7a6-795630ef02f0.png)

From the flattened graphs and the snake plots it is evident that having a cluster value of 4, segments our customers well. We could also go for higher number of clusters, it completely depends on how the company wants to segment their customers.

## Evaluating Model
**1. Davies Bouldin Score**

Davies Bouldin Score is a metric for evaluating clustering algorithms. The smaller Davies Bouldin Score is the more optimal the cluster.

**2. Silhouetter Score**

Silhoutter Score is a metric for evaluating clustering algorithms. The higher Silhouter Score is the more optimal the cluster.

### In 2009-2010
**1. Davies Bouldin Score**

![image](https://user-images.githubusercontent.com/88583319/132082718-bf034d66-5be6-463f-a317-830cce993f2d.png)

K-Means with 4 clusters has lowest davies bouldin score than other cluster. Therefore the optimum cluster is 4.

**2. Silhouetter Score**

![image](https://user-images.githubusercontent.com/88583319/132082719-a0c1f5b6-b52e-4f86-b6b8-3a548b63b564.png)

K-Means with 4 clusters has higher silhouette score than other cluster. Therefore the optimum cluster is 4.

### In 2010-2011
**1. Davies Bouldin Score**

![image](https://user-images.githubusercontent.com/88583319/132082723-d15265ba-2a51-4768-8cd9-5037598ec0cc.png)

K-Means with 4 clusters has lowest davies bouldin score than other cluster. Therefore the optimum cluster is 4.

**2. Silhouetter Score**

![image](https://user-images.githubusercontent.com/88583319/132082729-07b168f3-4f1d-4020-abcc-2393951f15a4.png)

K-Means with 4 clusters has higher silhouette score than other cluster. Therefore the optimum cluster is 4.

## Interpretation of The Clusters Formed Using K-means
### In 2009-2010

![image](https://user-images.githubusercontent.com/88583319/132082627-f0b23c8d-4889-4356-b456-11153f66e84a.png)

![image](https://user-images.githubusercontent.com/88583319/132082640-2473786f-a0b0-4468-b238-df2c3c0adf8a.png)

### In 2010-2011
![image](https://user-images.githubusercontent.com/88583319/132082669-9e1a68d5-c883-46fc-b664-165cde4e7973.png)

![image](https://user-images.githubusercontent.com/88583319/132082674-c4c3c921-f290-4079-9cc2-6f33adc2eee7.png)

## Recommendation
Based on the 4 clusters, we could formulate marketing strategies relevant to each cluster:

### In 2009-2010
![image](https://user-images.githubusercontent.com/88583319/132082597-1091628e-b213-448b-b1a7-6fbc80aa1d32.png)

### In 2010-2011
![image](https://user-images.githubusercontent.com/88583319/132082601-58479d0e-5ec6-4739-a167-4cbffc11fcb8.png)











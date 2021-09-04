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


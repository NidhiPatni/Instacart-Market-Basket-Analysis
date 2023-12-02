# Instacart-Market-Basket-Analysis

**What is Instacart?**
Instacart is an online grocery delivery and pick-up service that connects users with personal shoppers who handpick and deliver groceries from local stores.

**Why market Basket Analysis?**
Develop a recommendation system to suggest relevant products to customers based on their previous orders and preferences.

**Motivation behind this project.**
Personally, as a user I see this as an opportunity to analyze, unravel patterns that can enhance overall shopping experience and optimize marketing strategies.

**Problems we are going to solve via this project.**

**Problem 1:** Find out hidden association between products for better cross-selling and upselling. 
**Approach:** Implement the Apriori algorithm to identify frequent item sets and generate association rules to find product associations.

**Problem 2 :** Perform customer segmentation for targeted marketing and anticipate customer behavior.
**Approach:** Utilize K-means clustering algorithm to group users based on their purchasing patterns for customer segmentation.

**Problem 3:** Predicting which previously purchased product will be in the user’s next order. 
**Approach:** Using XGBoosting algorithm for product re-order prediction. 

**Information regarding dataset:**

**Source link :** https://www.kaggle.com/competitions/instacart-market-basket-analysis/data

**Orders.CSV :**  (3421083 rows, 7 columns) - This file contains all the orders made by different users.

**Products.CSV :**  (49688 rows, 4 columns) - This file contains the list of total products and their aisle and corresponding department details.

**Aisles.CSV :** (134 rows, 2 columns) - The data gives the unique number of aisles and their unique id.

**Departments.CSV :**  (21 rows, 2 columns) - The data has number of unique departments available and their corresponding id.

**Steps Involved:**

1. Initial Data Analysis
2. Exploratory Data Analysis
3. Feature Creation
4. Data Preparation
5. Market Basket Analysis
6. Customer Segmentation
7. XGBoost Model
8. Principal Component Analysis


 

# Customer Segmentation and Sales Predictions
---

### Problem Statement
---

In order to drive successful targetted promotions and advertisements, can we segment our customer base into similar groups?  Additionally, using the traits and data on hand, can we use linear regression to predict a user's spending within a few thousand dollars?


### Executive Summary 
---

Statistics and machine learning algorithms are some of the most powerful and interesting tools in tech right now, and their applications are seemingly endless.  The amount of customer data companies have at their fingertips in the year 2021 is staggering but then the question is, how do we use this data to help drive growth and revenue?  One helpful way to do this is customer segmentation, dividing the customer base into smaller groups with similar traits in order to evaluate trends, habits, and broader characteristics.  In this project I seek to find the ideal clustering and then evaluate models to see if we can predict how much a customer will spend based on their demographic information.


**1. Sample Details:**
- Data from Kaggle
- 2240 unique user profiles
- 29 features

**2. Sources:**
- https://www.kaggle.com

**3. Data Dictionary:**

|Feature   | Dtype  | Description  |
|---|---|---|
| ID  | int  | User ID  |
| Year_Birth  | int  | User's birth year  |
| Education  | string  | User's level of education  |
| Marital_Status  | string  | User's relationship status   |
| Income  | float  | User's income  |
| Kidhome  | int  | # of non-teenage children in a user's household  |
| Teenhome  | int  | # of teenage children in the user's household  |
| Dt_Customer  | string  | Date the the user joined the website  |
| Recency  | int  | # of days since the user's last purchase  |
| MntWines | int  | Amount spent on wine in the last 2 years  |
| MntFruits  | int  | Amount spent on wine in the last 2 years   |
| MntMeatProducts  | int  | Amount spent on meat in the last 2 years   |
| MntFishProducts  | int  | Amount spent on fish in the last 2 years  |
| MntSweetProduct  | int  | Amount spent on sweets in the last 2 years  |
| MntGoldProds  | int  | Amount spent on gold in the last 2 years  |
| NumDealsPurchases  | int  | # of purchases made with a discount  |
| NumWebPurchases  | int  | # of purchases made through the website  |
| NumCatalogPurchases | int | # of purchases made through the catalogue  |
| NumStorePurchases  | int  | # of purchases made in stores |
| NumWebVisitsMonth  | int  | # of web visits in the last month  |
| AcceptedCmp1  | int  | Bool, 1 if customer accepted the offer in the 1st campaign  |
| AcceptedCmp2  | int  | Bool, 1 if customer accepted the offer in the 2nd campaign   |
| AcceptedCmp3  | int  | Bool, 1 if customer accepted the offer in the 3rd campaign   |
| AcceptedCmp4  | int  | Bool, 1 if customer accepted the offer in the 4th campaign   |
| AcceptedCmp5  | int  | Bool, 1 if customer accepted the offer in the 5th campaign  |
| Complain  | int  | Bool, 1 if the customer has filed a complaint in the last year   |



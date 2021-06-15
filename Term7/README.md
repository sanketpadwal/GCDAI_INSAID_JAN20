# INSAID Term Project - Deap Learning Foundation
# **PREDICTING LOWEST PRODUCT PRICING USING ARTIFICIAL NUERAL NETWORK**
<img src="https://github.com/sanketpadwal/GCDAI_INSAID_JAN20/blob/main/Term7/60184848bf83e-Summer%20Sale%20Banner%20Templates.png?raw=true" width="1000" height="500" />

##### https://graphicmama.com/design-bundle/summer-sale-banner-templates?utm_source=sale-banners-article&utm_medium=image



### **Introduction- Problem Statement**
---
##### A leading global leader of e-commerce has over 150 million paid subscription users. One of the many perks of the subscription is the privilege of buying products at lower prices. For an upcoming sale, the organization has decided to promote local artisans and their products, to help them through these tough times. However, slashed prices may impact local artists. To not let discounts affect local artists, the company has decided to determine the lowest price at which a particular good can be sold.
---

### **Dataset:**
The dataset consists of various parameters such as a unique item ID, category of the market to which a product belongs, category and quality of the product, its demand rate, and its original market price. The data is present in a single csv file: slashing_prices.csv - Dataset consisting of approximately 9,798 data samples.

**Source:**<br> 
Github <br> https://raw.githubusercontent.com/sanketpadwal/GCDAI_INSAID_JAN20/main/Term7/slashing_prices.csv?_sm_au_=iVVH3LNLF2QNrsFqL321jK0f1JH33


**Data Descriptions:** 

| Column Name           | Description |
|-----------------------|-------------|
| Item_Id Unique        | item ID. |
| Date                  | Date.
| StateofCountry        | State no. of the country.
| Market_Category       | Category of the market to which the product belongs to. |
| Product_Category      | Category of the product.
| Grade                 | Quality of the product.
| Demand                |Demand rate of the product in the market.
|LowCapPrice            |Lowest price that can be offered. [target]
| HighCapPrice          |Original maximum price in the current market.


### **Objective**
---
Task is to build a predictive model using Artificial Neural Net algorithm that helps to set up a lowest-pricing model for the products in dataset.

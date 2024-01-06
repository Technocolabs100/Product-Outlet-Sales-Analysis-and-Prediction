
![Logo](https://www.leadsquared.com/wp-content/uploads/2021/11/banner-4-3.png)


# Product-outlet-sales-analysis-and-prediction

This project aims to develop a predictive model capable of estimating the sales of 1559 products in 10 different BigMart stores for the year 2013. Utilizing sales data, the model will predict whether the sales quantity for each product in a particular store will be high or low. Analyzing specific features of products and stores will help identify key factors influencing sales. In summary, this project provides a predictive approach to assess and anticipate sales trends in BigMart stores.

# Data set description

  - Item_Identifier: Product identifier (Type: String).

  - Item_Weight: Weight of the product (Type: Numeric).

  - Item_Fat_Content: Fat content of the product (Type: Categorical - String).

 - Item_Visibility: Visibility of the product in the store (Type: Numeric).

 - Item_Type: Type of product (Type: Categorical - String).

 - Item_MRP: Maximum retail price of the product (Type: Numeric).

 - Outlet_Identifier: Store identifier (Type: Categorical - String).

 - Outlet_Establishment_Year: Year the store was established (Type: Numeric).

 - Outlet_Size: Size of the store (Type: Categorical - String).

 - Outlet_Location_Type: Location type of the store (Type: Categorical - String).

 - Outlet_Type: Type of store (Type: Categorical - String).

 - Item_Outlet_Sales: Sales of the product in the store (Type: Numeric).
##  Hypothesis generation. 

The initial step in solving any business problem using machine learning is hypothesis generation. Having a clear understanding of the problem statement with strong domain knowledge is crucial, and formulating hypotheses opens the door to exploring new ideas for more in-depth problem-solving.

   - The price of the product (MRP) could be positively correlated with sales.
   - The establishment year of the store may play a role in attracting customers.
   - Product visibility in the store can impact sales.
   - Differences in size between stores could influence the capacity to stock and sell certain products.
   - The variety of store types (supermarket, grocery, etc.) may impact purchasing preferences.
## EDA

Exploratory Data Analysis (EDA) is a visual approach to understanding data from various perspectives. It involves using graphs and statistical summaries to examine data in detail.

During the Exploratory Data Analysis (EDA) phase, we handled missing values, managed outliers, and conducted both univariate and bivariate analyses. This process was crucial for enhancing the dataset's quality and gaining insights into variable relationships, setting the stage for more advanced analyses and modeling.


## Packages

```javascript
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
import xgboost as xgb
from sklearn.ensemble import RandomForestRegressor


```


## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. See LICENSE for more information 


## Authors

- [@Lamia Oualili](https://github.com/lamiaoua)



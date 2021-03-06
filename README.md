# Analysis of the online retailer sales data

This repository contains detaied analysis of Online Retail data provided by the UCI. To execute the notebooks on your local machine, please keep the order (since they do some intermediate data processing):

 1. `DataPreparation.ipynb` is devoted to the preliminary data processing. It contains mostly technical steps, but this may be important for understanding of the future notebooks.

 2. `EDA.ipynb` contains exploratory data analysis that provides relevant bustiness insights:
   * Seasonality of the business
   * Geography of customers
   * The overall company's revenue
 
 3. `Product_categorisation.ipynb` contains analysis of the products sold by the company. There is an attempt of categorisation of products by names, but in the end I deceded to choose simplier categorisation by the price of the products

 4. `Customer_categorisation.ipynb` splits the customers into groups according to their purchase patterns and product purchases, and characterises the obtained customer personas. I also suggest a way to detect churning users there, study churning dynamics in 2011, and identify the users of high risk of churning by the end of 2011.


# Business Background

Supermarket Mona operates in a competitive market, offering a diverse range of products from everyday groceries to premium items like wines and gold products. The following dataset represents customer engagement for a supermarket over the last 2 years. The data includes :
- demographic information
- purchase history across products
- customer preferred channel
- campaign acceptance history

# Business Problem

The primary business problem is how to find the best approach to optimize sales strategies, which includes how to tailor discounts, premium services, etc to match the right customer. The next step is to find which customer will be the most receptive to which strategies. By leveraging the data-driven insights, the supermarket will have increased chance of successfully executing the sales strategies and yield good response from customers, thus increasing sales.

# Data Analysis Objective 

The objective of this data analysis is to clean and analyze the supermarket's customer data to gain insights into customer segments and their shopping behaviors. The focus will be on:
- Data cleaning (filling or removing null values , allocating ambiguous data, adding summary collumns, etc)
- Visualization with tableau

In which the ultimate goal is to hopefully INCREASE SALES. The strategies are :
- Segmenting the customer base in categories (Income and product preferences)
- Recommending deals and promotions for each segment to maximize the supermarket's resources efficiency

Data Dictionary : 
People
- ID: Customer's unique identifier
- Year_Birth: Customer's birth year
- Education: Customer's education level
- Marital_Status: Customer's marital status
- Income: Customer's yearly household income
- Kidhome: Number of children in customer's household
- Teenhome: Number of teenagers in customer's household
- Dt_Customer: Date of customer's enrollment with the company
- Recency: Number of days since customer's last purchase
- Complain: 1 if the customer complained in the last 2 years, 0 otherwise

Products
- MntWines: Amount spent on wine in last 2 years
- MntFruits: Amount spent on fruits in last 2 years
- MntMeatProducts: Amount spent on meat in last 2 years
- MntFishProducts: Amount spent on fish in last 2 years
- MntSweetProducts: Amount spent on sweets in last 2 years
- MntGoldProds: Amount spent on gold in last 2 years

Promotion
- NumDealsPurchases: Number of purchases made with a discount
- AcceptedCmp1: 1 if the customer accepted the offer in the 1st campaign, 0 otherwise
- AcceptedCmp2: 1 if the customer accepted the offer in the 2nd campaign, 0 otherwise
- AcceptedCmp3: 1 if the customer accepted the offer in the 3rd campaign, 0 otherwise
- AcceptedCmp4: 1 if the customer accepted the offer in the 4th campaign, 0 otherwise
- AcceptedCmp5: 1 if the customer accepted the offer in the 5th campaign, 0 otherwise
- Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

Place
- NumWebPurchases: Number of purchases made through the company’s website
- NumCatalogPurchases: Number of purchases made using a catalog
- NumStorePurchases: Number of purchases made directly in stores
- NumWebVisitsMonth: Number of visits to the company’s website in the last month


Conclusion : Customer base are divided into income segment (low and medium, and high) and product preferences sub-segments (level 1 to 4, focussing only on level 2 and 3). Sales strategies are formulated specially for each segments , totalling to 24 distinct sales strategies.

Dashboard link (please use full screen mode) : https://public.tableau.com/app/profile/christian.manan/viz/capstone2dashboard_17176048727760/Maindashboard

Tableau story link (please use full screen mode) : https://public.tableau.com/app/profile/christian.manan/viz/capstone2story/Mainstory?publish=yes

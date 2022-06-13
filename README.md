# Customer Clustering
The used Dataset is for a UK-based and registered non-store online retail which contains all the transactions occurring between 01/12/2010 and 09/12/2011. 
The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. The I used is from [Kaggle](https://www.kaggle.com/datasets/carrie1/ecommerce-data), however the original Dataset can be found on the [UCI Machine Learning Repository ](https://archive.ics.uci.edu/ml/datasets/online+retail) Website. 

# Goal 
The Goal of this project is to divide customers into multiple groups which is achieved using RFM (Recency, Frequency, Monetary) analysis.

# Summary
After cleaning the data and eliminating missing values, I did some general Exploratory Data Analysis (EDA) to get to know the data better. 


## EDA
![Summary](https://user-images.githubusercontent.com/70484577/173429738-bef5897e-46ca-420f-b632-8ec185d4e426.JPG)


As expected most of the over 4000 customers are from the UK ![Pie_Chart_Customers_Country](https://user-images.githubusercontent.com/70484577/173429952-0d29ac2f-827b-48f7-bbf2-22938156485d.JPG)

## RFM Analysis
![RFM_Plot](https://user-images.githubusercontent.com/70484577/173433811-a0468e01-e467-4b0f-a4bb-1847d2c6dc2a.JPG)

For this clustering problem I used K-means. The created clusters can be seen below
![Final_Clusters_Table](https://user-images.githubusercontent.com/70484577/173429156-3e5f258d-9258-4dff-9621-4e820db62f2f.JPG)




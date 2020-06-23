# customer_segmentation
Customer segmentation modeling with PCA and Kmeans.

For this project, I wanted to segment the customers of an actual UK based online store. The dataset contain roughly 500k orders that took place between 01/12/2009 and 09/12/2011.
Since each row contained an individual transaction, after some EDA, I needed to convert the data to a unique customer level for modeling. 

After creating the customer level features, I performed PCA to determine how many compenents were actually needed and used the elbow and silhoutte methods to determine the optimal number of clusters to use with KMeans.

Important files in this repo:

1) all_analysis_and_modeling.ipynb<br>
This includes all of the EDA, feature engineering, modeling and data viz. 

2) customer_data.csv<br>
This is the transaction level dataset from the UK based ecommerce store. 

3) customers_master_w_clusters.pkl<br>
This is the final pickle of the the customer level dataset with the features I engineered and assigned clusters.

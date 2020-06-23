# customer_segmentation
Customer segmentation modeling with PCA and KMeans.

For this project, I wanted to segment the customers of an actual UK based online store. The dataset contains roughly 500k orders that took place between 01/12/2009 and 09/12/2011.
Since each row in the original dataset contained an individual transaction, after some EDA, I needed to convert the data to a unique customer level for modeling. 

After creating the customer level features, I performed PCA to determine how many components were actually needed and used the elbow and silhouette methods to determine the optimal number of clusters to use with KMeans.

Important files in this repo:

1) all_analysis_and_modeling.ipynb<br>
This includes all of the EDA, feature engineering, modeling and data viz. 

2) customer_data.csv<br>
This is the transaction level dataset from the UK based e-commerce store. 

3) customers_master_w_clusters.pkl<br>
This is the final pickle of the customer level dataset with the features I engineered and assigned clusters.

4) all_analysis_and_modeling_PDF.pdf<br>
If you would like to quickly see all of the code, this is a PDF of the main notebook. Please note the plotly viz does not format correctly in the PDF but it does if you run the actual notebook. 


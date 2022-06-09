# Feynn_Revati
Market Segmentation Analysis = Reading Assignment 2
#Data Preprocessing
1.   For data preprocessing => converting the binary yes,no to 1,0 similarly for gender. Standardising the features: "like","VisitFrequency","Age"
2. After applying kmeans without standardising I observed the clusters were greatly influenced by the age, because the range of that feature was huge as compared to others and thus "Age" dominated the Kmeans clustering algorithm.
 
Therefore standardisation was applied followed by PCA for dimensionality reduction => It resulted in better clustering with reduced overlap and 6 components.
 
#Exploartory data Analysis
1. The graphs were plotted before standardising the variables for better visualisation
2. The give a general overview of data w.r.t to the major features
 
#Model fitting
1. Elbow method and scree plot for PCA gave the optimal clusters to be 4 and principal components to be 6 respectively.
2. After fitting the model, boxplots were plotted to understand the trend in features. Certain major characteristics of each cluster have been highlighted via the box plots.

# Market Segmentation (Clusters 0,1,2,3)
1. Cluster 2 thinks the food is healthy
2. Customers from Cluster 1 are the most frequent visitors
3. Not much correlation between age and like (0.046)
 
 
#Inferences:
1. Customers from cluster 0 do like the food but don't find it healthy,and are the least frequent visitors.. they belong to the age grp around 40-60 yrs. Some also find it expensive. Efforts: Make food healthy + start some healthy combo meals to motivate them to buy.
2. Customers from cluster 1 have the highest visiting frequency they have given the highest number of likes. Age group is 30-40 (These will be the working population) who are currently able to afford and enjoy the existing services. But again they don't find the food healthy.. thus implementing the healthy combo options here would be a great opportunity to grow by targeting the market segment which is already in the profitable area.
3. Customers from cluster 2 belong to around 55+ of age... These people don't visit often and have given the worst rating for the food. As they are elderly there might be issues to come to McD centres, thus alternate web apps can be explored to make ordering easier for them.
Different food segments depending on the tastes of elderly people can be started to make the foreign food seem more homely.
4. Customers from cluster 3 are the 2nd most frequent visitors spanning the age group around 20-30, they have given -ve ratings and also think the food to be expensive. Introducing some product with an affordable price with a tinge of taste change can help us venture more into this segment.
 
# References: 
1. https://365datascience.com/tutorials/python-tutorials/pca-k-means/
2. https://www.geeksforgeeks.org/how-to-standardize-data-in-a-pandas-dataframe/
3. https://www.kaggle.com/code/ecemboluk/market-segmentation-with-clustering/notebook

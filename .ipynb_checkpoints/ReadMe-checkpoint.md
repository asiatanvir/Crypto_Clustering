
# Crypto Clustering

In this Jupyter notebook cryptocurrencies have been clustered by their performance in different time periods using unsupervises machine learning. The generated results are plotted to visually show the performance of clusters.


The steps for this challenge are broken out into the following sections:

* Import the Data (provided in the starter code)
* Prepare the Data (provided in the starter code)
* Find the Best Value for k Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for k Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results

Price variation of the crypto currencies provided in our original DataFrame is as below. 

![crypto_price_variation](crypto_price_variation.png)

To cluster the cryptos with KMeans model best value of k is derived using Elbow Method.  As can be seen in the below chart, Elbow method derived the best value for k as 4 under original data and PCA data.


|elbow_original                                         | elbow_PCA                            |
| -----------------------------------                   | ----------------------------------- |
| ![eblow_original_data](elbow_curve_original_data.png) | ![eblow_PCA_data](elbow_curve_pca.png) |


Thorugh the best value for k found above by using the original data & PCA data the cryptos have been  clustered according to the provided price changes. After compeleting the requisite steps the clusters generated through original data and optimized through PCA are displayed below. 

![crypto_clusters](crypto_clusters.png)

As can be seen from the chart, the clusters generated through PCA resulted in better clustering. Even clusters are more tightened up for cluster 0 and cluster 2.





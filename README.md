# Facebook-Live-sellers-in-Thailand
Clustering on  [Facebook Live sellers in Thailand, UCI ML Repo](https://www.kaggle.com/ashishg21/facebook-live-sellers-in-thailand-uci-ml-repo) with some minor changes.<br>
Clustering methods that are used in this notebook:K-means, DBSCAN and AgglomerativeClustering.<br>
## Notebook description
These notebooks include PreProcessing, EDA, Feature engineering and Feature extraction via PCA and at last the Clustering itself.<br>
I have used elbow method to determine the apropriate value for the number of clusters, so that I can use it in K-means. Also k_distance_graph is used for the same purpose but in finding the best value for epison in DBSCAN.<br>
The Dendogram has been ploted for Hierarchical Clustering.<br>
Evaluating the performance of the clustering algorithms has been done with the following metrics: Adjusted Rand index, Mutual Information based score, Homogeneity, completeness and V-measure,Silhouette Coefficient and Calinski-Harabasz Index.

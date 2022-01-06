# Clustering-Analysis-for-Stocks
- Performed stock feature scaling and feature selection
- Implemented unsupervised dimensionality reduction techniques such as PCA, Kernel PCA, T-SNE.
- Through some calculations, results from the linear PCA were also used to analyze feature importance, which was informative for identifying useful insights from the final clusters.
- Kernel PCA using the rbf kernel was found to be more successful in separating the clusters when 2 principal components were visualized on a 2-D graph.
- K-Means and OPTICS clustering methods were used, which produced similar results in terms of the characteristics of stocks within each cluster. Since the data points presented on a 2-D graph exhibited varying density, I did not implement DBSCAN.
- The Silhouette score was used to select the final set of hyperparamters for the clustering algorithm used.

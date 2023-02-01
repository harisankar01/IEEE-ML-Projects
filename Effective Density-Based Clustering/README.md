# Effective Density-Based Clustering for Incomplete Data

This paper provides a solution to perform density-based clustering on datasets that have incomplete data without loss of quality of clusters.

- CI clustering with intermediate clustering based on the KD tree.
- LI clustering: Create a kD tree with the entire dataset and use the information of neighboring points to predict the missing values of a cluster.
- DBSCAN to achieve a result(cluster).

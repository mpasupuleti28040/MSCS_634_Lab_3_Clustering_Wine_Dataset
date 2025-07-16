# MSCS_634_Lab_3_Clustering_Wine_Dataset

## Purpose:
The purpose of this lab was to explore clustering techniques, specifically K-Means and K-Medoids, using the Wine Dataset from scikit-learn. The lab helps understand how to apply these algorithms, evaluate clustering performance, and visualize the results.

## Key Insights:
- **K-Means** produced well-defined clusters with a high Silhouette Score but was sensitive to outliers.
- **K-Medoids**, although more robust to outliers, showed similar performance in terms of the Silhouette Score and ARI.
- Visualization indicated that K-Means tends to form more spherical clusters, while K-Medoids resulted in slightly more scattered shapes due to the medoid-based clustering.

## Challenges:
- Implementing the K-Medoids algorithm manually was challenging, especially when computing the new medoids. However, this was an essential part of understanding the algorithm.
- Converting the K-Medoids labels for performance metrics was another step that required careful handling.

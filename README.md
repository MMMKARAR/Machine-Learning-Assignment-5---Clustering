# Machine-Learning-Assignment-5---Clustering
This repository contains an assignment in Jupyter Notebook exploring clustering techniques using the Iris dataset. The assignment implements and evaluates KMeans and Hierarchical Clustering, with visualizations and metrics to assess clustering quality.
Objective:
To understand and apply clustering techniques (unsupervised learning) on the Iris dataset and evaluate their performance.

Tasks Performed:
1. Data Loading and Preprocessing
Dataset: The Iris dataset was loaded from sklearn.
Preprocessing:
Converted the dataset into a DataFrame.
Dropped the species column to align with the unsupervised learning objective.
Applied StandardScaler to standardize features, ensuring equal contribution of all variables.
2. KMeans Clustering
Description: KMeans partitions data into clusters by minimizing intra-cluster variance.
Implementation:
Applied KMeans with 3 clusters (based on domain knowledge of the Iris dataset).
Visualized clusters using scatter plots for the first two principal components.
Insights:
Clusters resembled the natural grouping of Iris species.
Silhouette Score: 0.494.
3. Hierarchical Clustering
Description: Builds a cluster hierarchy using agglomerative or divisive methods.
Implementation:
Used Agglomerative Clustering with 3 clusters.
Visualized the dendrogram and final clusters using scatter plots.
Insights:
The dendrogram displayed the hierarchical structure of data.
Silhouette Score: 0.450.
4. Silhouette Analysis
Metric: Calculated silhouette scores to evaluate clustering quality.
Result:
KMeans outperformed Hierarchical Clustering with a higher silhouette score.
Insights Gained:
KMeans vs. Hierarchical Clustering:

KMeans produced better-defined clusters with a higher silhouette score.
Both methods effectively separated the data, but KMeans' focus on minimizing intra-cluster variance gave it an edge.
Effect of Standard Scaling:

Standard scaling was critical to ensure all features contributed equally to clustering.
Silhouette Scores:

Both techniques achieved moderately high silhouette scores, indicating well-separated clusters.
Conclusion:
Best-Performing Method: KMeans clustering, with a silhouette score of 0.494, was slightly better suited for the Iris dataset.
Effective use of visualizations (scatter plots, dendrograms) and evaluation metrics (silhouette scores) demonstrated a solid understanding of clustering techniques.

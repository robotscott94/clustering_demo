# clustering_demo
Utilizing various cluster methods to analyze financial tools

## Purpose
Utilize k-means clustering to group different currencies based on historic price change data. Various techniques are used to hone the algorithm and produce good results.

## Tools
Scikit-learn provides tools for this sort of analysis including methods for scaling, dimensionality reduction and clustering. We used PCA for dimensionality reduction and k-means for clustering. Holoviews and Matplotlib are also used to plot the data and better illustrate the resulting clusters.

## Results
Four clusters, as determined by the elbow method, are created, and the clusters are predicted. The user can view the resulting graphs in the notebook. Regular clustering was compared to clustering the reduced data set, but the results were quite similar. This pattern may be due to the small data set, but further testing should be done to improve the results.
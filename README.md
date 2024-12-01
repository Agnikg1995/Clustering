# Clustering
Explanation of the Code Steps
Library Imports:

We bring in several libraries that will assist us throughout the analysis:
Pandas and Numpy allow for data manipulation and numerical operations.
Matplotlib and Seaborn help create visualizations to make the results easier to interpret.
Scikit-learn provides tools to load datasets and implement clustering algorithms.
Loading the Iris Dataset:

The Iris dataset, a classic in machine learning, is loaded.
We separate the features (in X) and labels (in y), where X contains the measurements of the flowers and y consists of species labels that we won't be using for clustering.
KMeans Clustering:

We use KMeans to find distinct groups in our data based on features.
By setting n_clusters=3, we're indicating that we expect three clusters in the data corresponding to the three species of Iris.
We fit the model to our dataset and predict the cluster for each observation.
Next, we visualize the results in a 2D scatter plot using PCA to simplify the data for better interpretability. Cluster centers are marked in red for easy reference.
Hierarchical Clustering:

This section applies a different approach to clustering using agglomerative clustering.
We tell the model to also look for 3 clusters and predict the classifications.
As with KMeans, we visualize the hierarchical clustering results in another scatter plot, allowing us to compare how it partitions the data.

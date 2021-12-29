# FIFA-19-football-

# About the Dataset

This dataset contains features of around 18,000 football players. Using only numerical attributes to cluster the data.

# Data Visualization and Data Preparation

I have  used matplotlib and seaborn for visualization.

For my  comfort, below mentioned are the basic visualization I have started with:

Plot histogram of count of players based on some attributes like height.

Plot histogram and kde plots on attributes like ‘Value’ and ‘Wage’

Use visualization techniques to find outliers like Ronaldo and Messi

Distribution of players in different clubs/countries on the basis of some attributes

# Data transformations:

Remove inconsistencies from ‘Value’ and ‘Wage’ columns

Missing Values and Outliers treatment

# K Means
1. Implement k-means clustering. Choose k = 3, 5, 7
2. Using only numeric attributes to cluster
3. Using elbow method and Silhouette Score to get optimal number of clusters
4. Analyzing the results/clusters formed(in every case above) based on the following
parameters:
a. How good are the clusters? Use inter and intra class similarities to measure the
goodness of clusters
b. Finding  hidden patterns if any
# Hierarchical Clustering
1. Cluster the data using Agglomerative method of your choice
2. Plotted dendrogram
3. Analyzing the cluster formed based on the following parameters:
a. How good are the clusters? Use inter and intra class similarities to measure the
goodness of clusters
b. Finding any hidden patterns if any
# DBScan
1. Using DBScan to cluster the data
2. DBScan requires 2 parameters - epsilon and minPts. Show all the experiments
performed to arrive at the final epsilons and minPts
3. Analyzing the cluster formed
a. How good are the clusters? Use inter and intra class similarities to measure the
goodness of clusters
b. Finding hidden patterns if any

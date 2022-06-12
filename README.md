# Cryptocurrencies
The purpose of this analysis was to analyze various cryptocurrencies on the market and create a report based on their features for an investment company to propose an investment portfolio for their clients. The following methods were used for the analysis:

## Preprocessing the database
Reducing the data dimension using Principal Component Analysis (PCA)
Clustering cryptocurrencies using K-Means
Visualizing classification results with 2D and 3D scatter plots
Resources
## Data Source: crypto_data.csv
Python 3.7.11, Jupyter Notebook 6.4.5 [using mlenv environment].
## Results
There were a total of 577 tradable cryptocurrencies after preprocessing the database, reduce the data dimensions using PCA, and then cluster the cryptocurrencies using K-Means.

## Finding the best value for k using an elbow curve:
elbow_curve

![image](https://user-images.githubusercontent.com/94252681/173212841-8270086d-4912-4aef-8c8c-d04f76b742ab.png)

As presented in the elbow curve above, the k value is 4. This k value in inputted into a k-means model to predict cryptocurrencies into 4 clusters.

## 3-D scatter plot with clusters
3d_graph

![image](https://user-images.githubusercontent.com/94252681/173212864-32030b32-7b5d-4636-83b3-03ad305cd660.png)

As presented in the 3-D graph above, using the PCA algorithm, the crytocurrencies dimensions were reduced to three principal components (PC1, PC2, PC3).

## 2-D plot with clusters
2d_plot

![image](https://user-images.githubusercontent.com/94252681/173212893-9934fade-1a70-4b71-8360-af7a12ee53b5.png)

As presented in the 2-D scatter plot above, using the PCA algorithm, the crytocurrencies dimensions was reduced to two principal components.

Plotting the scatter plot from two cryptocurrency features does not provide a clear visual of the different classes. The data points are hard to visually decipher as compared to the 3-d scatterplot, which is more visually easier to comprehend using the PCA algorithm.

## Summary
With a total of 577 classifications of cryptocurrencies identified based on the similarities of their features, specific features of each classification group should further be analyzed to ensure the portolio proposed from these analyses is as robust as possible for the best interest of the clients of the investment bank.

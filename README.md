# Cryptocurrencies

## Unsupervised Data - Machine Learning 

Analyse a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
We use the following methods for the analysis:

* Deliverable 1 - Preprocessing the database
* Deliverable 2 - Reducing the data dimension using Principal Component Analysis
* Deliverable 3 - Clustering cryptocurrencies using K-Means
* Deliverable 4 - Visualizing classification results with 3D scatter plots

##  Resources

* **Data Source:** crypto_data.csv, CryptoCompare
* **Software:** Python, Jupyter Notebook

##  Results 

The preprocessed and transformed output used for analysis hs 532 rows of tradble cryptocurrencies. Since we don't know what would be the output of the analysis we are using unsupervised machine learning to identify clusters of the cryptocurrencies.

### Elbow Curve:

![ElbowCurve](/Resources/Elbow_Curve.PNG)

We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.
The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### 3D Scattered Plot with Cluster:

![3dPlot](/Resources/3D_ScatteredChart.PNG)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components and the visualization layer is built using the 3 principal components

### Visualize the distinct groups that correspond to the 3 principal components 

![DistinctGroups](/Resources/hvPlot_Scattered.PNG)

The Scatter plots show the distribution and the four clusters of cryptocurrencies.

### Tradable Cryptocurriencies Table

Most of the cryptocurrencies are part of class #0 and #1.

![TradableTable](/Resources/Clustered_Table.PNG)

##  Summary

We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the clients.



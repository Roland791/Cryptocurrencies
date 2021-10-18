# Cryptocurrencies
## Unsupervised Machine Learning and Cryptocurrencies

### Overview
This module uses unsupervised learning to analyze data on the cryptocurrencies traded on the market. Our investors are interested in offering a new cryptocurrencies investment portfolio for the customers. The company, however, is lost in the immense universe of cryptocurrencies. Therefore, we will implement machine learning models to present a report of cryptocurrencies on the trading market and how cryptocurrencies could be grouped toward creating a classification for developing this new investment product.

The data needs to be processed to fit the machine learning models. Since there is no known output for what we are looking for, we are utilizing unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm to help determine investment groupings in this product.

### Goals and steps

Deliverable 1: Prepare the data for dimensions reduction with PCA and clustering using K-means.

Deliverable 2: Reduce data dimensions using PCA algorithms from sklearn.

Deliverable 3: Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.

Deliverable 4: Create plots and data tables to present the clustering results.

Please refer to the [Crypto_clustering.ipynb file](https://github.com/Roland791/Cryptocurrencies/blob/main/crypto_clustering.ipynb). 

### Data Visualization

1) a 3D scatter plot using Plotly Express to plot the clusters using the clustered_df DataFrame.

![3D Scatter](/Images/3D_Scatter.PNG)

2) A Scatter Plot created using Scaled Numbers from clustered_df Dataframe after running it through the fit_transform function.

![Scaled Cluster Scatter](/Images/Scaled_Cluster_Scatter.PNG)

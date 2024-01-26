# CryptoClustering
Using Python and unsupervised learning to predict cryptocurrency timeframe price change impact

by Jason Estrada

Libraries used:
- pandas
- sklearn
- hvplot

This project applies unsupervised learning techniques of the K-Means method to a cryptocurrency dataset and segment them into distinct clusters.
- The dataset is scaled to normalize the data
- An optimal `k` value is identified using the Elbow Method
- Fit the K-Means model with the original scaled data
- Cryptocurrencies are clustered (predicted) with K-Means using the original scaled data and plotted using `hvplot`

The scaled data is then optimized using Principal Component Analysis (PCA), and re-run using the PCA-optimized dataset to determine the clusters.

A composite plot was created to compare k and clusters between original and optimized data, providing how PCA is beneficial in meeting original data results while reducing dimensionality (therefore time/cost when running models).
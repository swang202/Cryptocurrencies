# Cryptocurrencies

The goal fo the analysis is to understand what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

In summary, there are 532 tradable cryptocurrencies. Principal Component Analysis (PCA) algorithm was applied and the dimensions was reduced to three principal components. 

Elbow curve showed the best value for K is four. 

![Elbow_curve](Results/Elbow_curve.png)

K-means algorithm was used to cluster the four cryptocurrencies clusters using the PCA data.

![K-means](Results/Crypto_cluster_PCs.png)

For visualization, we created scatter plots with Plotly and hvplot to show the total coin supply against total coin mined, in distinct groups that correspond to the three principal components. 

![K-means](Results/Coin_supply_mined.png)

A table with all the currently tradable cryptocurrencies was created using the hvplot.table() function.

![Table](Results/crypto_class.png)

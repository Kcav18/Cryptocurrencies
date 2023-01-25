# Cryptocurrencies

## Overview

Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked me to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data we are working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, we have decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. Will will also use data visualizations to share our findings with the board.

This project consists of four technical analysis parts:

- Part 1: Preprocessing the Data for PCA
- Part 2: Reducing Data Dimensions Using PCA
- Part 3: Clustering Cryptocurrencies Using K-means
- Part 4: Visualizing Cryptocurrencies Results


The technical analysis was completed in Jupyter Notebook. To view this code, [click here](https://github.com/Kcav18/Cryptocurrencies/blob/main/crypto_clustering.ipynb).

Please note that the visualizations in Part 4 do not show up when viewing the code through GitHub. The completed visualizations are below:

***The Elbow Curve below finds the best value for K:***

![Elbow Curve](https://github.com/Kcav18/Cryptocurrencies/blob/main/elbow_curve.png)

***The 3D-Scatter Plot below shows the PCA data and clusters - and each data point shows the CoinName and Algorithm on hover:***

![3-D Scatter](https://github.com/Kcav18/Cryptocurrencies/blob/main/3d_Scatter.png)

***The hvplot Scatter below was created where the X-axis is "TotalCoinsMined", the Y-axis is "TotalCoinSupply", the data is ordered by "Class", and it shows the CoinName when you hover over the data point.***

![hvplot Scatter](https://github.com/Kcav18/Cryptocurrencies/blob/main/hvplot_scatter.png)




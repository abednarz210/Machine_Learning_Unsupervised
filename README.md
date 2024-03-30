# Cryptocurrency Clusters 
## Machine_Learning_Unsupervised

![Cryptocurrency]([Resources/bitcoin-2007769_640.jpg])

## Background

As part of the Advisory Services Team of a financial consultancy. One of the clients, a prominent investment bank, is interested in offering a new 
cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. We are tasked to create a 
report that includes what cryptocurrencies are on the trading market and determine whether they can be grouped to create a classification system for this new 
investment.

## Instructions: Data Preparation


* Read crypto_data.csv into Pandas. The dataset was obtained from CryptoCompare.

* Discard all cryptocurrencies that are not being traded by filtering for currencies that _are_ currently being traded. Next, drop 
  the IsTrading column from the dataframe.
* Remove all rows that have at least one null value.
* Filter for cryptocurrencies that have been mined
* Convert data to be comprehensible to a machine learning algorithm, change to numeric values and delete unnessary columns.  
* Standardize the dataset so that columns that contain larger values do not unduly influence the outcome.



## Dimensionality Reduction

* Creating dummy variables 
* Perform dimensionality reduction with PCA. Rather than specify 
* Using PCA(n_components=0.99) create a model that will preserve approximately 99% of the explained variance,
* Reduce the dataset dimensions with t-SNE and examine scatter plot for distinct clusters



## Cluster Analysis with K-Means

* Create an elbow plot to identify the best number of clusters 


## Recommendation

We can observe the shape of the elbow curve at 4, according to the model our K value optimal number of clusters is 4. 



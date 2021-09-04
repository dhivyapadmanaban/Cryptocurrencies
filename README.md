# Cryptocurrencies

## Project Overview 
The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features. This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

- preprocessing the database,
- reducing the data dimension using Principal Component Analysis,
- clustering cryptocurrencies using K-Means,
- visualizing classification results with 2D and 3D scatter plots.

## Resources
Data Source: crypto_data.csv, CryptoCompare
Software: Python, Anaconda Navigator, Jupyter Notebook

## Results

Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.


### Clustering Cryptocurrencies using K-Means - Elbow Curve

  We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10. Using below elbow curve image, we can find the number of clusters to run K_Means algorithm.
   
 ![image](https://user-images.githubusercontent.com/83181834/132078619-7f951ab5-6513-4a01-a08c-f32de455809b.png)

### Visualizing Cryptocurrencies Results

#### 3D-Scatter plot with clusters

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

![image](https://user-images.githubusercontent.com/83181834/132078639-7b0b380c-d722-4092-a29e-f81e7a5875f9.png)

#### 2D-Scatter plot with clusters

This 2-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to two principal components.

![image](https://user-images.githubusercontent.com/83181834/132078646-5a532141-8996-4883-9c33-12c962ce617e.png)

### Tradable Cryptocurrencies Table

![image](https://user-images.githubusercontent.com/83181834/132078667-83ae806b-60cf-4750-a405-c776ed025edd.png)


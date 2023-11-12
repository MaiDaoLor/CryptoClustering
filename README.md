# Crypto_Clustering


## Description
In this challenge, we'll use our knowledge of Python, and utilize Unsupervised Larning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.



##  Process
1. I used the provided Starter_Code file [crypto_market_data.csv](/Starter_Code/Resources/crypto_market_data.csv) to run the code that creates the DataFrame.
2. Prepare the data: using standardScaler we're going to scale the data, and create a new dataframe from it calling 'df_crypto_market_data'.
3. To find the best Value for 'k' we're going to create a dictionary with the data and plot the elbow curve.

    * Plot the line chart with all the inertia values computed with the different values of 'k' to visually identify the optimal value for 'k'. 
4.  Answer the following questions:

    * What is the best value for `k`?
5. We're going to cluster the cryptocurrencies with KMeans using the scale data. 

    * Create a scatter plot using hvPlot with the new predicted clusters column. 
7. Using the original scale DataFrame, perform a PCA and reduce the the features to three principal components.
8. Answer the following the questions:

    * What is the total explained variance of the three principal components. 
9. Use the elbow method on the PCA data to find the best value for 'k'. 

    * Plot a line chart with all the inertia values computed with the different values of 'k' to visually identify the optimal value for 'k'. 
10. Answer the following questions:

    * What is the best value for 'k' when using the PCA data?
11. Cluster the cryptocurrencies for the best value for 'k' on the PCA data. 

    * Create a scatter using the hvPlot for the PCA data
12. Visually analayze the cluster analysis results by contrasting the outcome with and without using the optimization techniques. 
12. Answer the following question:

    * What is teh impact of using fewer features to cluster the data using KMeans?


## Resources:
- https://holoviz.org/tutorial/Composing_Plots.html
- Tutor: Geronimo Perez


## Contact
If there are any questions of concerns, I can be reached at:
##### [github: MaiDao Lor](https://github.com/MaiDaoLor)
##### [email: mdl06@yahoo.com](mailto:mdl06@yahoo.com)


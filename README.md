# Cryptocurrencies


 An old dataset about cryptocurrencies is clustered with the K-means algorithm.

 Tools used: pandas, sklearn (k-clusters, pca, rescalers), and hvplot.


### Mismatches with provided output.

 This task was given with expected output, and ours diverges from it at PCA analysis. The differences are similar to the effects of varying the random state for the algorithm, but none of the random states from 0 to 100 match the provided output.

 The end result of our analysis (the actual clusters) is very similar to the end result provided. Here are a couple views of the same plot of the clusters, with colors indicating our cluster labels and shapes indicating provided cluster labels.

![one view.](/image1.png)

![two view.](/image2.png)
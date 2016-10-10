# SKU-Clustering

In this notebook I will attempt to cluster eCommerce item data by their names. The data is from an outdoor apparel brand's catalog. I want to use the item names to find similar items and group them together. For example, if it's a t-shirt it should belong in the t-shirt group.

The steps to accomplish this goal will be:

1. Cleaning the data to just include the name (pandas)
2. Transform the corpus into vector space using tf-idf (Sci Kit)
3. Calculating cosine distance between each document as a measure of similarity (Sci Kit)
4. Hierarchical Clustering and Dendrogram (Scipy)
5. Cluster the documents with k-means (Sci Kit)
6. Use MDS to reduce the dimension
7. Plot the clusters (matplotlib)


The dataset consists of 500 actual SKUs from an outdoor apparel brand's product catalog downloaded from Kaggle (https://www.kaggle.com/cclark/product-item-data). 


I used http://brandonrose.org/clustering as a reference for this project. He has a lot of interesting projects with great explanations in his blog.

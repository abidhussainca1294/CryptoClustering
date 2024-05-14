# CryptoClustering

This project uses the knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

K-means clustering is used. The following works are done.

*  Normalization of the data using StandardScaler() from scikit-learn.

*  The elbow method is used to find the best value for k.

*  The data  is fit with a k-means model to cluster the different crypto currencies into 4 groups then a scatter plot is created with clusters predicted by K-means as labels.

*  Principal Component Analysis (PCA) is used to reduce the features down to 3.

*  The explained variance of these three features was 89%.

*  The elbow method and fitting the data with a k-means model is performed on PCA data.

*  Finally, a comparison is made on the elbow curves and the scatter plots before and after PCA.
   
   
    

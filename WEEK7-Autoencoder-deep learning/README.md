
# Neural network - autoencoder

**Autoencoder**

Autoencoder is a special type of neural network that uses the same data as both the input values and output values. The goal is to get the middle layer which reduces noises, it can also be considered as a method of dimension reduction. 

Autoencoder uses non-linear transformation, if there are too many hidden layers or too many neutrons, the model tends to overfit; otherwise the model tends to underfit.

Applications of autoencoder include image noise reduction and image coloring. 

**Business insights** 

From the graph, we can see most observations are on the left of 0. The observations above 0.2 are extreme cases, we will set the boundary to be 0.2 Observations on the right of 0.2 are in cluster 1, they accounts for 1.1% of total transactions. They have more spending on cardholder level, however, it takes more time for this transaction to happen. It is possible that the card is stolen or lost, then being used again. 

<img src="Clf1_Anomaly_Scores.png" alt="album cover" width="500"/>


# Neural network - Isolated Forest
Isolated Forest is a method to separate trees till all are isolated, and find which tree is the easiest to be seperated. An outlier is the easiest to be isolated. 

iTree algorithm is different from the decision tree algorithm because iTree does not use a target variable to train the tree. It is an unsupervised learning method.

If there are 1,000 subsets, there will be 1,000 iTrees. Each data point in an iTree will have an anomaly score. Because there are 1,000 iTrees, each data point will have multiple anomaly scores. The average (arithmetic mean) score for a data point across all the iTrees becomes the anomaly score for that data point.

Compared with KNN and Autoencoder, Isolate forest discovered similar patterns for outliers on cardholder level, while KNN and Autoencoder identifies outliers in both agency and cardholder level.

Cluster 1 has more spending on cardholder level and takes more time for this transaction to happen. It is possible that the card is stolen or lost, then being used again. 



<img src="iforest.png" alt="album cover" width="500"/>



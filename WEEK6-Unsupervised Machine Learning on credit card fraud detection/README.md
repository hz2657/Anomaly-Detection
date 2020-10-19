# unsupervised learning and credit card fraud detection

**project structure**


**key steps**

1. construct features

2. build model

3. select threshold

4. show summary statistics + implementation



**Section 1 PCA**


**Section 2 Unsupervised KNN**

1. KNN has both supervised and unsupervised algorithm, distance is to the neighbors. K Nearest Neighbour is a simple algorithm that stores all the available cases and classifies the new data or case based on a similarity measure. It is mostly used to classifies a data point based on how its neighbours are classified.

2. test hyper-parameters, k_list = [20, 30, 40, 50], take average of the anomaly scores calculated from each model. Choose a boundary to distinguish outliers. 

3. summary statistics for the variables by cluster, identify outliers & business insight


Pros of KNN
- Simple to implement, Flexible to feature/distance choices
- Naturally handles multi-class cases, Can do well in practice with enough representative data

Cons of KNN
- Need to determine the value of parameter K (number of nearest neighbors)
- Computation cost is quite high because we need to compute the distance of each query instance to all training samples.





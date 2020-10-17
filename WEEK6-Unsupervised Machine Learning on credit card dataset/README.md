# Identify outliers in the credit card dataset by unsupervised learning

**project structure**

1. construct features

2. implement unsupervised learning models, to find isolated observations - anomalies 

- clustering methods: Knns, Kmeans

- Use two PyOD methods - KNNs, PCA 

- test different hyper-parameters 

3. identify a small cluster to be labeled as suspicious

- explanations why the particular cluster(s) are anomalous

- average statistics of the variables of that cluster


**key steps**

1. build model

2. select threshold

3. show summary statistics + implementation



**Section 1 PCA**

1. method description: distance is to the center
2. test hyper-parameters. 
3. summary statistics for the variables by cluster
4. identify outliers
5. identify business insight


**Section 2 Unsupervised KNN**

1. method description: both supervised and unsupervised algorithm, distance is to the neighbors

- we compute data points that are far from others
- K: number of data points in that circle
- anomaly score: shortest distance

2. test hyper-parameters

3. summary statistics for the variables by cluster

4. identify outliers

5. identify business insight









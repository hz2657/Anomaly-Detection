## Mortgage default detection with random forest & sampling methods 

**Background**

The goal of this project is to identify candidates that are most likely to default, by building bagging/random forest model from H2O open source. Our dataset is the 'loan default' dataset which contains 80000 applicants' information and whether they default or not. Only 19% cases are default cases, thus the dataset is imbalanced.

H2O supports the most widely used statistical & machine learning algorithms including gradient boosted machines, generalized linear models, deep learning and more. H2O also has an industry leading AutoML functionality that automatically runs through all the algorithms and their hyperparameters to produce a leaderboard of the best models. The H2O platform is used by over 18,000 organizations globally and is extremely popular in both the R & Python communities.

**Notebook structure**

1. Load and explore data

2. Feature selection

3. EDA on selected features

4. Data sampling

5. Fit model, prediction, and model evaluation: ROC, precision recall curve, gains table, the cumulative Lift

6. Summary and busienss insights

**Result**

ADASYN over sampling method has the best performance
- roc, auc curve: 0.8285 
- area under precision recall curve: 0.7792 
- lift in first decile: 3.14 
- max K-S equals 50. 
<img src="graph/roc auc.png" alt="album cover" width="500"/>


**Summary and busienss insights**

1. More training data leads to better model performance, oversampling tends to have better performance than under-sampling given the same complexity level

2. More complicated sampling methods tend to have better performance, for example, Neighborhood Cleaning Rule under-sampling over perform random under-sampling, and ADASYN over sampling over perform random over-sampling

3. Business insights from variable importance: please see the analysis below


**The most important predictors are**

1. Top1: Education level
2. Top2: Monthly credit card spending upper limit
3. Top3: Average length of high risk calls
4. Top4: Number of queries from P2P in the past 6 months
5. Top5: Number of queries from P2P in the past 3 months


**What's next**
1. classify '-98', '-99' values and negative values. 
2. tune the model parameters by grid search. 
3. compare the oversampling method and the original dataset's model performance result
4. try Lasso for feature selection
5. use log transformation for skewed variables


**Project stucture**

1. Load and explore data

2. Feature selection

3. EDA on selected features

4. GLM without regularization and with regularization

5. autoML: Fit model + Model evaluation

6. Model evaluation: ROC AUC, the cumulative Lift

 

**GLM Definition**

Generalized Linear Models (GLM) estimate regression models for outcomes following exponential distributions

*Regularization*
Put penalty if there are too many coefficient in loss function 

*Hyper-parameters*

- lambda: Specify the regularization strength. Lambda: 0, no regularization; Lambda>0, have regularization 
- lambda_search: Specify whether to enable lambda search, starting with lambda max (the smallest λ that drives all coefficients to zero). 
- alpha: Specify the regularization distribution between L1 and L2. The default value of alpha is 0 when SOLVER = ‘L-BFGS’; otherwise it is 0.5.  when alpha = 0, ridge, L2, when alpha = 1, lasso, L1. 


**AutoML**
- Train all algorithms, rank by their performances, and then choose the best
- From Leader board, ensemble model has the best performance



**Model Performance Summary**
- GLM with regularization has higher lift, while GLM without regularization has higher AUC.
- GBM after tuning parameters from last week has the highest AUC. 

 
 

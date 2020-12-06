
# Summary 

Apply the SHAP Values to mortgage probability of default modeling data set (with variables/features).  
 
**SHAP Values**
1. help clients to understand why the observation is predicted in that result, it measures the contribution of a variable, calculate contribution towards target.
2. can show positive/negative relationship in variable importance plot for random forest
3. can show image for individual observation for reasons of prediction 
 
**Benefit**
 1. global interpretability: show how much each variable contribute, house analogy
 2. local interpretability: each observation get its own set of SHAP values
 
 
**To interpret the  SHAP Value Plot below:**

We predicted 0.1, whereas the base_value is 0.1947. Feature values causing increased predictions are in pink, and their visual size shows the magnitude of the feature's effect. Feature values decreasing the prediction are in blue. The biggest impact comes from CR015 being 6. Though the value has a meaningful effect decreasing the prediction.

AP003 has the biggest impact, which is the EDUCATION LEVEL, it decreased the possibility for the variable to be default.

CD152 has the 2nd biggest impact, which is the LEN_TOP3_FREQUENT_OUTBOUND_PHONE_NUMBERS_OUTBO, it increased the possibility for the variable to be default.

CD008 which is LEN_TOTAL_INBOUND_CALLS_LAST_1MON, it increased the likelihood to be default.
 
<img src="graph/Individual SHAP Value Plot.png" alt="album cover" width="500"/>

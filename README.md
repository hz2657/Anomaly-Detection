# week 1: feature engineering to detect credit card fraud transactions

data-visualization-in-python

**background**

Banks loan out money to earn interest as revenue, however, some borrowers may not be able to repay the loan. The probability of loan default is 5%. 

In this case, banks apply machine learning models to predict probability of default (PD), high prediction value means the person is more likely to default, vice versa. 

By ranking applicants' risk from high to low, grouping candidates from high-low risk groups, a good ML model can distinguish these candidate groups. The process is called the Gains Table. 


**data**
80,000 applicants 
target variable: "loan_default"


**goal**

1. build a simple decision tree/logistic regression model

2. conduct Exploratory Data Analysis on the provided dataset

3. produce the gains table.


**steps**

0. feature selection

1. deal with Na

2. split for train and test data. 

3. EDA on train data for the top 15 variables. Answer What is business insight? How does this feature help prediction?

4. Apply your model prediction to produce a gains table. 


**How Gains Table works**

The banks rank applicants by predicted probability of default (PD) from high to low and group them into 10 differnet buskets, called decile. It contains the predicted PD, and the actual number of default for each decile. 

Assume the PD for the population is 10%, we take into account the case without grouping applicants by predicted PD. 


**2 measurements**

- lift: which is also called cummulative lift, measures how likely the company will get the bad loans, if compared with the random results

- Kolmogorov-Smirnov (K-S): measures the degree of separation between the distributions of the good loans and the bad loands


 - we use and create the gains chart to measure model performance. The gains chart is an essential modeling measurement. 

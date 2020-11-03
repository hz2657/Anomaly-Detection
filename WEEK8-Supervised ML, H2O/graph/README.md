
**Deal with imbalanced data**

Data imbalance can reduce model performance and increase the number of false negatives. To make the dataset more balanced, We will use data sampling techniques such as under-sampling and over-sampling methods to handle this imbalanced dataset.

1) undersampling techniques: take samples from majority since they contain same info

2) Oversampling: bootstrap for miniority

To evaluete model performance for imbalanced data, we will use precision recall curve besides the traditional AUC/ROC method, since AUC does not place emphasis on imbalanced dataset. Precision-Recall (PR) curves is more informative, and the area under precision-recall curve is more sensitive than the area under ROC curve, because precision (TP/TP+FP) is directly influenced by imbalanced dataset.

# WEEK9-Deep learning, Keras, GBM

In this week we build (1) the GBM (Gradient Boosting Machine) model and (2) the Deep Learning with the mortgage probability of default data.

The criteria include ROC and the cumulative Lift.

# Keras

The typical Keras workflows looks like:

1. Define your training data: input tensor and target tensor
2. Define a network of layers(or model ) that maps input to our targets.
3. Configure the learning process by choosing a loss function, an optimizer, and some metrics to monitor.
4. Iterate your training data by calling the fit() method of your model.


# WEEK9-Deep learning, Keras, GBM

In this week we build (1) the GBM (Gradient Boosting Machine) model and (2) the Deep Learning with the mortgage probability of default data.

The criteria include ROC and the cumulative Lift.

# Keras

Keras is a high-level Neural network. It makes it possible to implement deep learning models in a fast and efficient way. The simplest model in Keras is known as the Sequential model, which we are using in this week. 

Keras makes use of either Tensor flow (by Google) or Theano backend (by Montreal’s Theano) to give it computational capabilities; this means that the Keras library can run on both Tensor flow and Theano frameworks

The typical Keras workflows looks like:

1. Define your training data: input tensor and target tensor
2. Define a network of layers(or model ) that maps input to our targets.
3. Configure the learning process by choosing a loss function, an optimizer, and some metrics to monitor.
4. Iterate your training data by calling the fit() method of your model.


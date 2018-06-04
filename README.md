# PyTorch for TimeSeries analysis

Simple examples for time series analysis. The SC is complete and was executed, e.g. on google colab.

* E1: TimeSeriesPrediction1.ipynb executed on google colab: Comparing the performance for the training on a 2nd order problem for two models, a) a linear regression model (one linear layer model) and b) a two dense layer model. The 2nd order decodes four different states at two time points. Using a linear regression, only two states could be solved but two states collapses. Adding the ability to train an addtional hyperplane in case b), the four different states could be distinguished.

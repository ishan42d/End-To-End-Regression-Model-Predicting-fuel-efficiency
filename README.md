# End-To-End-Regression-Model-Predicting-fuel-efficiency

This is my take on how to handle an end to end machine learning regression problem using the widely known data source: https://archive.ics.uci.edu/ml/datasets/auto+mpg

Data Set Information:

The data concerns city-cycle fuel consumption in miles per gallon, to be predicted in terms of 3 multivalued discrete and 5 continuous attributes.
**Attribute Information:

1. mpg: continuous
2. cylinders: multi-valued discrete
3. displacement: continuous
4. horsepower: continuous
5. weight: continuous
6. acceleration: continuous
7. model year: multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance)

I have used three models here that can help in predicting the target variable "MPG"
1. Multiple Linear Regression
2. Gradient Boost Regression
3. Catboost Regressor

Anyone who wishes to use this may do so. Hyperparameters tuning can be done easily on all these models and hence accuracy can be improved. Even feature selection is something which one can choose accordingly

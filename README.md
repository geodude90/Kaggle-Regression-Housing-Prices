# Kaggle-Regression-Housing-Prices
Housing Price Regression analysis. Implemented SKlearn Pipelines and cross-validated entire model building process including feature selection,  scaling, and tuning.
The goal of this project is to predict housing prices, minimizing MSE. This is a regresssion problem and my personal goal is to develop a cross validation pipelining that includes all elements of model creation (including feature selection and hyperparameter tuning).
In the process, I wrote my first Python classes that inherit from the SKlearn Transformer class. While SKlearn pipelines are difficult to inspect, the ability to cross-validate the entire model building process and to simply call the transform method on the test set is invaluable in a production setting and makes data leakage almost impossible. I intend to use these transformers and pipelines in my future projects.

Major credit for the SKlearn pipeline framework and grid iteration goes to: Kartikay Bagla: Random Forests and Gradient Boosting: https://www.kaggle.com/drvader/random-forests-and-gradient-boosting

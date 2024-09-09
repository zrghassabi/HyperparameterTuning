# HyperparameterTuning

Hyperparameter Tuning: 

Automated Hyperparameter Tuning: Use libraries like Optuna or Hyperopt to automate the search for optimal hyperparameters.
https://hyperopt.github.io/hyperopt-sklearn/#documentation
https://optuna.org/

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Grid Search for model tuning
https://towardsdatascience.com/grid-search-for-model-tuning-3319b259367e

A model hyperparameter is a characteristic of a model that is external to the model and whose value cannot be estimated from data. The value of the hyperparameter has to be set before the learning process begins. For example, c in Support Vector Machines, k in k-Nearest Neighbors, the number of hidden layers in Neural Networks.

In contrast, a parameter is an internal characteristic of the model and its value can be estimated from data. Example, beta coefficients of linear/logistic regression or support vectors in Support Vector Machines.

Grid-search is used to find the optimal hyperparameters of a model which results in the most ‘accurate’ predictions.

Let’s look at Grid-Search by building a classification model on the Breast Cancer dataset. See Uploaded file by Google Colab

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
How to Grid Search Hyperparameters for Deep Learning Models in Python with Keras
https://machinelearningmastery.com/grid-search-hyperparameters-deep-learning-models-python-keras/

How to use Keras models in scikit-learn
How to use grid search in scikit-learn
How to tune batch size and training epochs
How to tune optimization algorithms
How to tune learning rate and momentum
How to tune network weight initialization
How to tune activation functions
How to tune dropout regularization
How to tune the number of neurons in the hidden layer


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Comparing Randomized Search and Grid Search for Hyperparameter Estimation in Scikit Learn
https://www.geeksforgeeks.org/comparing-randomized-search-and-grid-search-for-hyperparameter-estimation-in-scikit-learn/

Why RandomizedSearchCV is better than GridSearchCV?
One advantage of RandomizedSearchCV over GridSearchCV is that RandomizedSearchCV can be more efficient if the search space is large since it only samples a subset of the possible combinations rather than evaluating them all. This can be especially useful if the model is computationally expensive to fit, or if the hyperparameters have continuous values rather than discrete ones. In these cases, it may not be feasible to explore the entire search space using GridSearchCV.

Another advantage of RandomizedSearchCV is that it can be more robust to the risk of overfitting since it does not exhaustively search the entire search space. If the hyperparameter search space is very large and the model is relatively simple, it is possible that GridSearchCV could overfit to the training data by finding a set of hyperparameters that works well on the training set but not as well on unseen data. RandomizedSearchCV can help mitigate this risk by sampling randomly from the search space rather than evaluating every combination.

It is worth noting that both RandomizedSearchCV and GridSearchCV can be computationally expensive, especially if the model is complex and the search space is large. In these cases, it may be necessary to use techniques such as parallelization or early stopping to speed up the search process.

Regularization by Early Stopping
https://www.geeksforgeeks.org/regularization-by-early-stopping/

8.3. Hyperparameter Tuning - GridSearchCV and RandomizedSearchCV
https://www.bing.com/videos/riverview/relatedvideo?q=grid+search&mid=9D249546B3077B85C83F9D249546B3077B85C83F&FORM=VIRE

GridSearchCV
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://scikit-learn.org/stable/modules/grid_search.html


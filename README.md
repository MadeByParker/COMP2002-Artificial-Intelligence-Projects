## This is the repository for the COMP2002 Artificial Intelligence Module

## Part 1

### Machine Learning

This part of the Assessment was to train a dataset about energy efficiency of buildings with 3 regression models:

* `sklearn.neural_network.MLPRegressor` (Neural Networks)
* `sklearn.ensemble.RandomForestRegressor` (Random Forest)
* `sklearn.svm.SVR` (Support Vector Regressor)

And we had to plot the cross validation scores of 10 Mean Squared Error Rates on each model on boxplots to see 

1. How much the trained data would decrease by, comparing it to the test data. 
2. Which model was the best in this scenario.

## Part 2

### Optimisation

This part of the assignment was to generate an optimiser to solve a timetabling problem for a university. There is a .txt file that describes modules, and lists modules against which they cannot be scheduled. A module consists of one lecture per week and one or more lab sessions. 

We had to design and implement a fitness function by taking the number of the concurrence constraints and multiplying them with the number of precedence constraints. This fitness function should be minimised – the ideal timetable is one with no constraint violations at all, in which case the function will return 0. 

#### Constraints:

*	A session cannot be scheduled for a time when any of its students or staff are in another session (concurrence constraints). The sessions for a module that clash are shown in the data file.
*	A lab session cannot occur in the week before its corresponding lecture has taken place (precedence constraints).

## Credits

* Visual Studio Code: https://code.visualstudio.com
* VS Code Extension for Juypter: https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
* Scikit-learn: https://scikit-learn.org/stable/
* Numpy: https://numpy.org
* Python 3.9.5: https://www.python.org

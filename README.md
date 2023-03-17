# Decision Tree 🌲🌳🌴
Decision tree classifier and regresso implementation from scratch

## Requirements
- NumPy
- Pandas
- scikit-learn

## How to run notebook?
 - Install requirements
 - Put `part2.csv` and `part3.csv` datasets next to the `decision_tree.ipynb`
 - Open notebook and simply **Run All** cells.

## How to use `DecisionTreeClassifier` or `DecisionTreeRegressor`?
- Import `DecisionTreeClassifier` or `DecisionTreeRegressor`
- Make your data categorical in all feature except for the labels in regression problem.
- Make an object of `DecisionTreeClassifier` of `DecisionTreeRegressor`.
- Call `fit()` method on your training data just like the sklearn models notation.
- Call `predict()` method for making predictions on your test data.
- When using `DecisionTreeClassifier`, you can use `predict_prob()` to make predictions in probability form.

# Description
This is a simulated dataset containing sales of child car seats at 400 different stores.
Using the given ChildSeatSales dataset fit Logistic regression model to predict the class to which the given Sales in a location belong to. Before you train the model you need to create the traget variable "Category". Guidelines are given in the Pre-processing section

# Preprocessing
Sales is a continuous valued variable. Use Sales value to add a new field by name "Category". This newly created attribute "Category" is the target variable.

Assign Category = 1 if Sales<=5
Category = 2 if 5 < Sales <= 10, and
Category = 3 if Sales>10.

Use any applicable and required pre-processing techniques.
Analyze the problem by varying all the hyper parameters to get better performance.

# Acknowledgements
Our sincere thanks to James, G., Witten, D., Hastie, T., and Tibshirani, R. for providing this dataset.

# Evaluation
Classification accuracy is used as the performance metric.

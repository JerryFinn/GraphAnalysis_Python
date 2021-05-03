# GraphAnalysis_Python
Graph Analysis with networkx

## Node and Edge Predictions

This was an interesting assignment that was based on a company's email network where each node corresponds to a person at the company, and each edge indicates that at least one email has been sent between two people.

The network also contains the node attributes `Department` and `ManagementSalary`. `ManagementSalary` indicates whether that person is receiving a management position salary.

The interesting thing about predication on networks is in this class was that you did not get a dataset of features as usual, but made your own features from network metrics, whose choice all depends on what you want to predict. I tried a number of classifiers, such as random forest, gradient boosting but all gave similiar scorings, so all things being close I decided to go with a simple algorithm, logistic regression.  
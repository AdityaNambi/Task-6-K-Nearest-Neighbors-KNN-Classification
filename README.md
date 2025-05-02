# Task-6-K-Nearest-Neighbors-KNN-Classification
Implement KNN for classification problems.

1>Load Dataset
The Iris dataset is loaded from a CSV file (Iris.csv). The Id column is dropped to avoid affecting the model.

2>Select Features
Only the first two features (sepal length and sepal width) are used to allow 2D decision boundary visualization.

3>Normalize Features
Feature values are scaled using StandardScaler to ensure uniform contribution to distance calculations.

4>Encode Target Labels
The species names are converted into numeric labels using pandas.factorize().

5>Split Data
The dataset is split into training and test sets with a 70:30 ratio using train_test_split().

6>Train KNN Models
KNeighborsClassifier is used to train models for different K values (1, 3, 5, 7, 9).

7>Evaluate Models
Each model's performance is measured using accuracy and a confusion matrix on the test data.

8>Visualize Decision Boundaries
For each K, a 2D plot shows how the model classifies different regions of the feature space.

# Decision-Trees-Random-Forests
This project demonstrates the use of tree-based models for classification using the Heart Disease Dataset. We train and evaluate two models:  Decision Tree Classifier (single interpretable tree)  Random Forest Classifier (ensemble of decision trees using bagging)

Key steps in the workflow:

Data Loading & Preprocessing

Load dataset from a CSV file.

Separate features (X) and target (y).

Split into training and testing sets.

Decision Tree Model

Train a DecisionTreeClassifier with controlled depth to prevent overfitting.

Visualize the decision tree using Graphviz for interpretability.

Evaluate accuracy and analyze overfitting.

Random Forest Model

Train a RandomForestClassifier with multiple trees and bootstrap sampling.

Compare accuracy with the single Decision Tree.

Extract and visualize feature importances.

Model Evaluation

Use accuracy score, classification report, and confusion matrix on the test set.

Perform cross-validation to check model stability.

Learning Outcomes:

Understand how decision trees split data using impurity measures (Gini/Entropy).

Identify overfitting in decision trees and methods to control it (e.g., limiting depth, pruning).

Understand how Random Forest reduces variance and improves generalization through bagging.

Interpret feature importance for model explainability.

Gain experience with model visualization tools like Graphviz and plot_tree().


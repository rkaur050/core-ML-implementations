# Pre-Pruning Decision Tree Classifier with GridSearchCV

## Overview

This project demonstrates the use of **Pre-Pruning** in a Decision Tree Classifier on the Iris dataset using **GridSearchCV** for hyperparameter tuning. Pre-pruning prevents the tree from growing too large by restricting its size through parameters like `max_depth`, `min_samples_split`, and `min_samples_leaf`, which can help avoid overfitting.

### Key Concepts:
- **Pre-Pruning**: Limits the growth of the decision tree by setting constraints before the tree is fully grown.
- **GridSearchCV**: A method to automate the search for the best hyperparameters using cross-validation.

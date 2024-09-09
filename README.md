# logistic-regression

This project demonstrates how logistic regression works by building the model from scratch using basic mathematical concepts without using any high-level machine learning libraries (like scikit-learn). It is a simple implementation of binary classification where we predict whether a student passes or fails based on the number of hours they studied and slept.

## How It Works

1. **Sigmoid Function**: Converts raw scores (linear combination of input features) into probabilities.
   
2. **Prediction**: Using the sigmoid output, the model predicts the class (`Passed` if probability >= 0.5, otherwise `Failed`).

3. **Cost Function**: Measures the error of the model.

4. **Gradient Descent**: Optimizes the weights and bias by minimizing the cost function.

5. **Decision Boundary**: Plots a line that separates the 'Passed' and 'Failed' students based on their study and sleep hours.

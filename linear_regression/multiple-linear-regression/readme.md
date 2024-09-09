## Overview
This project implements a multiple linear regression model to predict house prices based on features such as house size, number of bedrooms, number of floors, and age of the home. The primary goal is to provide a foundational approach to understanding how features affect home prices using statistical modeling techniques.

## Dataset Description
The training dataset includes three examples with the following features:
- **Size (in sqft):** The total square footage of the home.
- **Number of Bedrooms:** The total number of bedrooms in the home.
- **Number of Floors:** The total number of floors in the home.
- **Age of Home (in years):** The age of the home.
  
The target variable is the **Price of the House in $1,000s**.

## Features and Model Implementation

### Feature Scaling
Normalization is applied to the features to ensure that our model isn't biased towards variables with larger magnitudes.

### Parameter Initialization
Initial parameters for the linear regression model are set to zeros for simplicity and to maintain a consistent starting point for the gradient descent optimization.

### Model Output Function
The model predicts the house price using a linear combination of the input features weighted by the learned parameters.

### Cost Function
We utilize the Mean Squared Error (MSE) cost function to evaluate the accuracy of our model. This function measures the average of the squares of the errors—that is, the average squared difference between the estimated values and the actual value.

### Gradient Descent
The parameters of the model are optimized using the gradient descent algorithm, which iteratively adjusts the parameters to minimize the cost function.


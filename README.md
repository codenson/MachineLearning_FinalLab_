# Logistic Regression with Regularization

This script, `main.py`, implements logistic regression for binary classification tasks, with support for regularization to prevent overfitting. It includes functions for cost computation, gradient computation, gradient descent optimization, and prediction. The script also visualizes decision boundaries and evaluates model accuracy on training data.

## Features

1. **Data Loading and Visualization**:
   - Loads datasets from `data/ex2data1.txt` and `data/ex2data2.txt`.
   - Visualizes the data points with labels using scatter plots.

2. **Logistic Regression**:
   - Implements the sigmoid function for logistic regression.
   - Computes the cost function (`compute_cost`) and its gradient (`compute_gradient`).
   - Optimizes parameters using batch gradient descent (`gradient_descent`).

3. **Regularization**:
   - Adds regularization to the cost function (`compute_cost_reg`) and gradient computation (`compute_gradient_reg`) to prevent overfitting.

4. **Feature Mapping**:
   - Maps input features to polynomial features for non-linear decision boundaries using `map_feature`.

5. **Model Evaluation**:
   - Predicts labels using the learned parameters (`predict`).
   - Computes training accuracy.

6. **Visualization**:
   - Plots decision boundaries for both linear and non-linear logistic regression.

7. **Unit Tests**:
   - Includes unit tests for key functions to ensure correctness.

## How to Run

1. Place the datasets (`ex2data1.txt` and `ex2data2.txt`) in the `data` directory.
2. Run the script using Python:
   ```bash
   python main.py
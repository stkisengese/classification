# classification
A hands-on exploration of binary and multi-class classification using logistic regression in Scikit-learn, applied to real-world medical datasets—featuring breast cancer diagnosis (Wisconsin dataset) and iris species prediction. Includes sigmoid functions, decision boundaries, train-test splitting with stratification, model evaluation, etc..

## Notebooks

This repository contains a series of Jupyter notebooks that walk through the fundamentals of logistic regression for classification tasks.

- **`sigmoid.ipynb`**: Introduces the sigmoid function, the core of logistic regression. It visualizes how different parameters affect the shape and position of the sigmoid curve.

- **`logistic_regression.ipynb`**: A basic introduction to using `LogisticRegression` from Scikit-learn. It covers training a simple model, making predictions (both class and probability), and inspecting the model's learned coefficients and intercept.

- **`decision_boundary.ipynb`**: Visualizes the decision boundary for a logistic regression model in both 1D and 2D. This notebook helps to understand how the sigmoid function's output is used to classify data points and what the decision boundary represents.

- **`train_test_split.ipynb`**: Explains the importance of splitting data into training and testing sets. It demonstrates the difference between a simple split and a stratified split, highlighting the importance of stratification for imbalanced datasets.

- **`ex05_prediction.ipynb`**: A practical example of building a logistic regression model to predict breast cancer using the Wisconsin dataset. This notebook covers:
  - Data loading and preprocessing (handling missing values).
  - The concept of a baseline model.
  - Train-test splitting with stratification.
  - Model training and evaluation using accuracy and a confusion matrix.

- **`multi_class.ipynb`**: Demonstrates how to extend logistic regression to handle multi-class problems using the Iris dataset. It implements the One-vs-Rest (OvR) strategy from scratch and compares the results to Scikit-learn's built-in multi-class support.

## Usage

To use this repository, clone it to your local machine and run the Jupyter notebooks. You will need to have Python and Jupyter Notebook installed.

First, install the required dependencies:

```bash
pip install -r requirements.txt
```

Then, clone the repository and launch Jupyter Notebook:

```bash
git clone https://github.com/stkisengese/classification.git
cd classification
jupyter notebook
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

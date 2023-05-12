# Regression Model Development
This project contains a Python implementation of a logistic regression model developed from scratch, using mathematical formulas and optimized with a custom implementation of the gradient descent algorithm.

The model was developed for the [Breast Cancer Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) from scikit-learn (sklearn).

For the sake of data visualization, only the features "Mean Radius" and "Mean Texture" of the dataset were used. Further more, only 1/6 of the dataset was used to induce a model's overfitting. This was done so that there could be an accuracy comparison between the regularized model and the unregularized model.

No Machine Learning Framework was used in the making of this project as Scikit-learn was only used to load the dataset into NumPy arrays.

## Requirements
To run the project, you will need the following Python packages:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn (only to load the Boston Housing Dataset)

You can install these packages using pip, conda, or any other package manager.

## Files
The project contains the following file:

- solution.ipynb: a Jupyter Notebook with the code and documentation for the project.

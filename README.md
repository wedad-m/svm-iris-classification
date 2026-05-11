# SVM Iris Classification

This project applies a Support Vector Machine (SVM) classifier to the Iris dataset. The goal is to classify iris flower species based on their sepal and petal measurements, evaluate the model performance, and improve the model using GridSearchCV.

## Project Overview

The Iris dataset is a classic machine learning dataset used for classification tasks. It contains measurements of iris flowers from three different species:

- Setosa
- Versicolor
- Virginica

The model uses the flower measurements to predict the correct species.

## Dataset Features

The dataset includes four input features:

- Sepal length
- Sepal width
- Petal length
- Petal width

The target variable is:

- Species

## Project Workflow

The project follows these main steps:

1. Load the Iris dataset
2. Explore the data using visualizations
3. Identify the most separable flower species
4. Split the data into training and testing sets
5. Train a Support Vector Machine classifier
6. Evaluate the model using a confusion matrix and classification report
7. Tune the model using GridSearchCV
8. Compare the original SVM model with the tuned model

## Exploratory Data Analysis

A pairplot was used to visualize the relationship between the dataset features and the flower species. Based on the visualization, the Setosa species appeared to be the most separable class because its data points were clearly separated from Versicolor and Virginica.

A KDE plot was also created to show the distribution of sepal length and sepal width for the Setosa species.

## Model

The main model used in this project is:

- Support Vector Classifier (SVC)

GridSearchCV was used to tune the following hyperparameters:

- C
- gamma
- kernel

## Results

The original SVM model achieved an accuracy of 0.98 on the test data.

After applying GridSearchCV, the best parameters were:

```python
{'C': 1, 'gamma': 0.1, 'kernel': 'rbf'}
The tuned model also achieved an accuracy of 0.98. This means that GridSearchCV did not significantly improve the result because the original SVM model was already performing very well.

Conclusion

The SVM classifier performed very well on the Iris dataset. The Setosa class was the easiest species to separate based on the visualizations. Although GridSearchCV did not significantly improve the accuracy, it was still useful for selecting the best hyperparameters for the model.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
How to Run

Open the notebook in Jupyter Notebook, JupyterLab, VS Code, or Google Colab, then run all cells from top to bottom.

Author

Wedad Mohammed

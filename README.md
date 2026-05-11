# SVM Iris Classification

This project uses a Support Vector Machine (SVM) model to classify iris flowers into three species: Setosa, Versicolor, and Virginica.

The dataset used is the Iris dataset from Seaborn. It contains flower measurements such as sepal length, sepal width, petal length, and petal width.

## Project Goal

The goal of this project is to build a simple machine learning classification model using SVM and evaluate its performance on the Iris dataset.

## Steps

- Loaded the Iris dataset
- Explored the data using visualizations
- Split the data into training and testing sets
- Trained an SVM classifier
- Evaluated the model using a confusion matrix and classification report
- Used GridSearchCV to tune the SVM parameters

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results

The SVM model achieved high accuracy on the test data. GridSearchCV was used to find the best parameters for the model.

Best parameters:

- C: 1
- gamma: 0.1
- kernel: rbf

The final model performed well, with only a small number of misclassified samples.

## Conclusion

This project shows how SVM can be used for a simple classification task. The Iris dataset is well-structured and suitable for practicing machine learning classification, model evaluation, and hyperparameter tuning.

## File

- SVM_Iris_Classification.ipynb

## Author

Wedad Mohammed Alhussaini

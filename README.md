# Heart Disease Prediction using SVM and PCA

This repository contains Python code for predicting heart disease using Support Vector Machines (SVM) and Principal Component Analysis (PCA).

## Dataset

The dataset used in this project is the **Heart Disease Dataset** from the **UCI Machine Learning Repository**. This dataset enables us to predict heart disease in an individual, taking into account features such as gender, age, blood pressure, and other various measurements.

## Code Overview

The code in this repository performs the following steps:

1. **SVM Model Training**: The SVM model is trained using different kernels ('linear', 'poly', 'rbf', 'sigmoid') and the accuracy of each model is printed.

2. **Confusion Matrix**: Predictions are made on the test data and a confusion matrix is generated. The confusion matrix is visualized using `ConfusionMatrixDisplay`.

3. **Hyperparameter Tuning**: GridSearchCV is used to find the optimal parameters for the SVM model.

4. **Precision, Recall, and F1 Score Calculation**: Precision, recall, and F1 score are calculated using the values from the confusion matrix.

5. **PCA**: PCA is performed on the scaled training data and a scree plot is generated to visualize the explained variance ratio.

6. **Decision Boundary Visualization**: The SVM is fit to the x and y-axis coordinates of the data after PCA dimension reduction. A filled contour plot is generated to visualize the decision regions.

## Libraries Used



## Output

The output of the code includes accuracy scores for different SVM kernels, a confusion matrix, optimal SVM parameters, precision, recall, F1 score, a PCA scree plot, and a decision boundary visualization.



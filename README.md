# Logistic Regression from Scratch

## Overview

This repository contains the implementation of Logistic Regression from scratch. The logistic regression algorithm is applied to a dataset, and the impact of removing specific data points is demonstrated. The implementation includes various visualizations to help understand the decision boundaries and the effect of outliers on the model.

## Logistic Regression Algorithm

The Logistic Regression algorithm is implemented from scratch, providing a detailed insight into the underlying principles and mathematics involved in logistic regression modeling. The algorithm is capable of handling binary classification problems.

## Dataset

The dataset used for training and testing is loaded from an Excel file ('Lab3_data.xls'), specifically from the sheets '2004--2005 Data' and '2004--2007 Data'. The dataset is preprocessed, and a column of ones is added to account for the intercept term.

## Model Training and Evaluation

The model is trained using gradient descent to optimize the weights. After training, the precision, recall, and F1 score of the model are calculated to evaluate its performance.

### Results

#### Full Dataset
- Precision: 0.944
- Recall: 0.944
- F1 Score: 0.944
- Weights: [ 9.8095376, -0.70352913, 0.27019655]

#### Removing Point 1 and 39
- Precision: 1.0
- Recall: 0.971
- F1 Score: 0.986
- Weights: [-0.02064271, -0.61553075, 0.2972152]

#### Removing Point 43
- Precision: 0.972
- Recall: 0.972
- F1 Score: 0.972
- Weights: [-0.01574701, -0.45174475, 0.21924883]

## Visualizations

Several visualizations are provided to enhance understanding:

1. **Cost vs. Iterations Plot**: A plot showing how the cost changes over the course of training.

2. **Scatter Plot with Decision Boundary**: A 2D scatter plot with the decision boundary surface.

3. **3D Plot of Decision Boundary**: A 3D plot illustrating the decision boundary and probabilities.

## How to Run

1. Clone the repository to your local machine.
2. Ensure that the required dependencies (NumPy, Pandas, Matplotlib, tqdm) are installed.
3. Run the provided Python script.

Feel free to experiment with the code, modify hyperparameters, or apply the algorithm to your datasets. Explore the impact of removing specific data points on the model's performance.

Happy Coding!

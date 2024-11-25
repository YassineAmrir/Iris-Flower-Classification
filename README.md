# Iris Flower Classification

## Project Overview

The Iris Flower Classification project aims to classify iris flowers into three species: Setosa, Versicolour, and Virginica, based on the famous Iris dataset introduced by Ronald A. Fisher in 1936. This project leverages machine learning techniques to build a predictive model that accurately classifies the species of an iris flower given its sepal length, sepal width, petal length, and petal width.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Solution Approach](#solution-approach)
- [License](#license)

## Dataset

The Iris dataset contains 150 samples, each with four features: sepal length, sepal width, petal length, and petal width. Each sample is labeled with one of the three species: Setosa, Versicolour, or Virginica. The dataset is available in the `data` directory as `iris.csv`.

## Solution Approach

To achieve high classification accuracy, a machine learning pipeline was utilized. The approach included the following steps:

1. **Data Preprocessing**  
   - Standardized the features to ensure they were on a similar scale, improving model performance.

2. **Model Selection and Optimization**  
   - Used a Random Forest Classifier for its robustness and effectiveness in multi-class classification tasks.  
   - Performed hyperparameter tuning using grid search to optimize the model for accuracy.

3. **Evaluation**  
   - Validated the model using cross-validation to ensure generalizability.  
   - Tested the final model on a hold-out test set, achieving excellent accuracy and reliable predictions.

4. **Results**  
   - Best hyperparameters identified through grid search significantly enhanced model performance.  
   - The model achieved near-perfect accuracy, effectively classifying all three flower species.  
   - Cross-validation accuracy averaged **96.67%**, demonstrating high generalizability.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

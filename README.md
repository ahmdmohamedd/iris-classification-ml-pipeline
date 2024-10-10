# Iris Classification ML Pipeline

## Overview
This project implements a machine learning pipeline using Scikit-learn to classify the Iris dataset, which consists of three species of iris flowers based on four features: sepal length, sepal width, petal length, and petal width. The pipeline includes data loading, preprocessing, model training, and evaluation.

## Dataset
The dataset used is the Iris dataset, which is included in the Scikit-learn library. It contains 150 samples with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Target Species (0: Setosa, 1: Versicolor, 2: Virginica)

## Pipeline Steps
1. **Import Libraries**: Load necessary libraries such as NumPy, Pandas, and Scikit-learn.
2. **Load Dataset**: Import the Iris dataset and convert it to a DataFrame for easier manipulation.
3. **Split Data**: Divide the dataset into training and testing sets.
4. **Preprocess Data**: Standardize the feature values to improve model performance.
5. **Train Model**: Fit a Random Forest Classifier to the training data.
6. **Make Predictions**: Use the trained model to predict species on the test set.
7. **Evaluate Model**: Generate a classification report and confusion matrix to assess model performance.

## Results
The model achieved 100% accuracy on the test set, indicating excellent performance in classifying the Iris species.

## Requirements
- Python 3.x
- Jupyter Notebook
- Scikit-learn
- Pandas
- NumPy

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   ```
   git clone https://github.com/ahmdmohamedd/iris-classification-ml-pipeline.git
   ```
2. Navigate to the project directory:
   ```
   cd iris-classification-ml-pipeline
   ```
3. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```
   jupyter notebook iris_classification_pipeline.ipynb
   ```

## Acknowledgements
- The Iris dataset is provided by the UCI Machine Learning Repository and included in the Scikit-learn library.
```

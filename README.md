# Smart Loan Prediction Project

## Overview

This project focuses on predicting loan repayment outcomes using a variety of machine learning techniques. It uses data from Lending Club to classify loans as either "Fully Paid" or "Charged Off." The project covers data preprocessing, handling imbalanced datasets, and training models with hyperparameter tuning.

## Features

- **Data Preprocessing**: Cleaning and selecting relevant features from the dataset.
- **Handling Imbalanced Data**: Techniques like undersampling and oversampling are used to balance the dataset.
- **Model Training**: Multiple models are trained, including a RandomForestClassifier and a neural network model with hyperparameter tuning using Keras Tuner.
- **Visualization**: Various visualizations are provided to understand the data distribution and the impact of different features on the target variable.

## Project Structure

- **Importing Libraries**: Necessary libraries for data manipulation, visualization, and model training.
- **Feature Selection**: Selecting important features from the dataset, reducing the original 74 features to the most impactful 20.
- **Exploratory Data Analysis (EDA)**:
  - Handling null values in the dataset.
  - Visualization of key features and their relationships.
- **Handling Imbalanced Dataset**:
  - **Undersampling**: Reducing the number of majority class samples to match the minority class.
  - **Oversampling**: Increasing the number of minority class samples to match the majority class.
- **Model Training**:
  - **RandomForestClassifier**: Trained with both undersampled and oversampled data.
  - **Neural Network with Keras**: Model training with hyperparameter tuning using Keras Tuner.
- **Result Evaluation**: Confusion matrix, accuracy, and classification report for model evaluation.

## Installation

To run this project, you need to install the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras imblearn keras-tuner
```

## Dataset

The dataset used in this project is the Lending Club loan data, which includes various features such as loan amount, interest rate, and borrower information.


## Model Performance

- **RandomForestClassifier**: Achieved a good accuracy score, especially when oversampling was applied to handle imbalanced data.
- **Neural Network**: Further refined with hyperparameter tuning, providing a robust model for predicting loan repayment outcomes.

## Visualization

The project includes multiple visualizations such as count plots, bar plots, and heatmaps to provide insights into the dataset and the performance of the models.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- **Lending Club**: For providing the dataset used in this project.
- **Open Source Libraries**: Thanks to the developers of the Python libraries used in this project.


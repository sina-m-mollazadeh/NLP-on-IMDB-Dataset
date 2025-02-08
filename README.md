# Sentiment Analysis Project

## Overview
This project involves data preprocessing and machine learning for sentiment analysis on the IMDB dataset, which contains 50,000 movie reviews. The focus is on cleaning data, feature engineering, and applying machine learning models. Model performance is evaluated using metrics like F1-score, precision, recall, accuracy, and confusion matrices.

## Dataset Handling
1. **Setup and File Upload**: Kaggle API credentials are used to authenticate and download the dataset.
2. **Loading and Exploration**: Data is loaded into a Pandas DataFrame for exploration.
3. **Visualization**: Sentiment distribution and word count statistics are visualized.
4. **Preprocessing**: Stop words and symbols are removed, and word frequency analysis is conducted.

## Feature Engineering
- Words are categorized by rarity.
- Positive-to-negative word ratios are calculated.
- Quartile-based sampling is used to balance datasets.
- Features are scaled using MinMaxScaler.

## Machine Learning Models
1. **Naive Bayes**:
   - Suitable for text classification.
   - Utilizes word counts and frequency ratios.
2. **Logistic Regression**:
   - A linear model for binary classification.
   - Regularization and solver parameters are configurable.
3. **Neural Networks (MLP)**:
   - Multilayer perceptron with customizable hidden layers and activation functions.

## Evaluation
- Confusion matrices are generated for each model.
- Performance metrics (F1-score, precision, recall, accuracy) are compared across models.

## Results
1. Highest feature correlation with sentiment: **Mean Positive-Negative Ratio (0.61)**.
2. Performance comparison of models highlights strengths and weaknesses for Naive Bayes, Logistic Regression, and Neural Networks.

## Project Files
- **main.py**: Executes data preprocessing, feature extraction, and modeling.
- **visualizations.py**: Generates visualizations for distributions and performance metrics.
- **model.py**: Implements machine learning models and evaluation methods.
- **data_utils.py**: Handles data loading, cleaning, and preprocessing.

## Key Figures
- Sentiment distribution and word count statistics (Figures 1-3).
- Feature correlation analysis (Figure 4).
- Neural network performance improvement (Figures 5-6).

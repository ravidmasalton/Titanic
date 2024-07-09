# Titanic
Titanic Survival Prediction


# Titanic
Titanic Survival Prediction


## Project Overview
This project aims to analyze and predict the survival of passengers on the Titanic using machine learning models. The project involves preprocessing the data, feature engineering, model selection, and hyperparameter tuning to achieve the best prediction accuracy.

  **Kaggle Notebook**: [Ravid's Notebook](https://www.kaggle.com/code/ravidmasalton/assignment1)

## Introduction
The sinking of the Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren't enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew. This project builds a predictive model to answer the question: “What sorts of people were more likely to survive?”

## Data Preprocessing
To improve the quality of the data, several preprocessing steps were performed:
- Removal of irrelevant features
- Filling missing values in the `Cabin` column based on the deck information



## Exploratory Data Analysis
Various visualizations and analyses were performed to understand the distribution of features and their correlation with the survival rate.

## Model Selection
We evaluated several models to find the best one for predicting survival:
1. **SGD Classifier**
2. **MLP (Multi-layer Perceptron)**
3. **KNN (K-Nearest Neighbors)**
4. **LDA (Linear Discriminant Analysis)**
5. **MNB (Multinomial Naive Bayes)**

## Optimal Model and Hyperparameters
### KNN
- **Best K**

### Ensemble Methods
- **BaggingClassifier**

## Feature Selection
- **Backward Selection**
- **Forward Selection**

## Hyperparameter Tuning
- **Grid Search vs Random Search**


## Summary
1. **Initial Model Selection**: Compared KNN, LDA, and MNB, selecting KNN for its accuracy.
2. **Optimal K Selection**: Determined the best `K` for KNN.
3. **Ensemble Methods**: Chose BaggingClassifier for better accuracy.
4. **Feature Selection**: Used backward selection to determine the optimal features.
5. **Hyperparameter Tuning**: Performed Grid Search and Random Search, with Grid Search yielding better results.

## Results
- **Best Accuracy Score**: 0.77511






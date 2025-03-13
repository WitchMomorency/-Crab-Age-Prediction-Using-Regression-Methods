# -Crab-Age-Prediction-Using-Regression-Methods
# Crab Farming: A Promising Business Opportunity

**Crabs** are one of the most popular seafood commodities enjoyed in various countries worldwide. The high demand for crabs makes it a promising business opportunity, especially for coastal communities. **Crab farming businesses** have several advantages, such as:
- **Low labor costs**
- **Relatively affordable production costs**
- **Fast growth rates of crabs**

With proper management and care, **crab farming** can generate greater profits compared to shrimp farming. Crab farming can be conducted using two main methods:
1. **Grow-out farming**
2. **Fattening system**

## The Importance of Determining Crab Age

Determining the precise age of crabs is crucial for commercial farmers to decide the optimal harvest time. Once a certain age is reached, **crab physical growth** tends to plateau. Thus, deciding the right harvest time can:
- Reduce costs
- Increase profits

**Data analysis** related to the age and physical characteristics of crabs is a critical step to support this process.

## Data Overview

The dataset used in this analysis aims to **estimate crab age** based on its physical attributes. This dataset serves as a foundation for:
1. **Exploratory Data Analysis**  
   Understanding how various physical characteristics of crabs change with age.
2. **Feature Engineering**  
   Defining new features by combining existing data to improve model accuracy.
3. **Regression Models**  
   Building regression models to predict crab age based on physical attributes.

**This dataset offers significant opportunities** to explore the application of regression analysis and feature engineering, especially to improve efficiency and productivity in commercial crab farming.

[Dataset Source on Kaggle](https://www.kaggle.com/datasets/sidhus/crab-age-prediction)

## Experimental Findings

- The most suitable algorithm for this model is **Linear Regression**.  
  Although its performance during testing was relatively poor compared to other algorithms, it delivered the best results during testing.
- **Random Forest Regression** showed the best performance during training. However, during testing, its performance decreased, indicating a potential overfitting issue.

## Model Evaluation and Improvement

- **MAE** and **MSE** cannot be considered concrete evaluation metrics because the model outputs normalized results instead of the desired integer age type.
- **R² Score** is used as the evaluation benchmark for model performance.
- The model can be further enhanced by applying **Feature Engineering** and **Hyperparameter Tuning** for more accurate predictions.  
  However, fundamentally, this model is already reliable in predicting crab age.

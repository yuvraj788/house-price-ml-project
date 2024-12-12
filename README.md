# House Price Prediction & Classification

This project aims to predict and classify house prices using machine learning algorithms. The dataset used is a CSV file containing housing data, and various models are applied to classify whether the price of a house is above or below the median value. The project includes data cleaning, visualization, feature engineering, and model training.

## Project Overview

The main steps of the project include:

1. **Data Loading and Cleaning**:  
   The raw housing price data is preprocessed by handling missing values, encoding categorical variables, and preparing the dataset for analysis.

2. **Data Visualization**:  
   Visualizations are created to better understand the data and its relationships:
   - **Heatmap**: Displays the correlation between features.
   - **Scatter Plots**: Shows the relationships between numerical features and the target variable (price).
   - **Count Plot**: Analyzes the distribution of categorical features.

3. **Feature Engineering**:  
   The `price` column is categorized into two groups:
   - `1` (expensive) if the house price is above the median.
   - `0` (affordable) if the house price is below or equal to the median.

4. **Data Splitting**:  
   The dataset is divided into training and testing sets for model training and evaluation.

5. **Modeling**:  
   Several machine learning classification models are applied to predict whether a house's price is above or below the median:
   - **Logistic Regression**
   - **Random Forest Classifier**
   - **Support Vector Classifier**
   - **XGBoost Classifier**

6. **Model Evaluation**:  
    Each model is trained on the training data and evaluated on the testing data. The performance of each model is compared to determine which provides the best classification results for the house price 
    categorization task.


   

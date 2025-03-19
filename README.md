# Real_Estate_Predictions_using_ML
Estate Estimator: Machine Learning for Competitive Property Pricing

# Project Overview

This project applies machine learning techniques to predict house prices using a dataset from King County, Washington. We explored multiple regression and classification models, conducted extensive feature engineering, and optimized model performance using dimensionality reduction techniques like PCA and backward elimination.


# Objectives

Build a predictive model for house prices based on property attributes.

Apply feature selection and dimensionality reduction techniques.

Compare the performance of different machine learning models.

Provide insights into the key factors influencing house prices.

# Dataset

Source: King County, Washington housing dataset.

Size: 21,613 records, 21 attributes.

Key Features: Bedrooms, bathrooms, square footage, location, grade, year built, view, etc.

Target Variable: Sale price of the property.

# Data Preprocessing

Converted date format and standardized numeric fields.

Handled missing values by imputing with the median.

Removed outliers (houses priced above $2.5M).

Dropped unnecessary columns ('id', 'date', 'zipcode').

# Exploratory Data Analysis (EDA)

Analyzed price distribution and feature relationships.

Identified strong correlations with price: sqft_living, grade, sqft_above, sqft_living15, bathrooms, and view.

Visualized data trends using histograms, boxplots, and heatmaps.

# Feature Engineering

Principal Component Analysis (PCA): Reduced dimensionality while retaining 72% variance.

Backward Elimination: Identified top 6 significant features for model training.


# Key Findings

Best Model: Random Forest with all features performed the best.

Most Influential Features: Square footage, grade, sqft_above, view, and latitude.

Impact of Feature Selection: While PCA and backward elimination reduced dimensionality, they slightly reduced accuracy compared to using all features.

Classification Accuracy: KNN performed well in categorizing houses into price ranges.

# Limitations & Future Work

The dataset is limited to King County, Washington; generalization to other regions requires additional data.

The model does not incorporate economic factors like interest rates or inflation.

Future work can include hyperparameter tuning, ensemble learning, and incorporating geospatial data for improved predictions.

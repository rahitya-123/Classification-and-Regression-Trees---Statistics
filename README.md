# Auto-MPG Dataset Analysis: Multiple Machine Learning Approaches

## Project Overview

This repository contains a comprehensive analysis of the Auto-MPG dataset using various machine learning techniques. The project demonstrates how different analytical approaches can extract valuable insights from automotive data, focusing on predicting and understanding factors that influence fuel efficiency and car origins.

## Dataset

The Auto-MPG dataset contains fuel consumption data for various automobile models from the late 1970s and early 1980s, along with several attributes:

- **mpg**: Fuel efficiency in miles per gallon
- **cylinders**: Number of cylinders in the engine
- **displacement**: Engine displacement in cubic inches
- **horsepower**: Engine horsepower
- **weight**: Vehicle weight in pounds
- **acceleration**: Time to accelerate from 0 to 60 mph
- **model_year**: Year of manufacture
- **origin**: Region of origin (1=American, 2=European, 3=Japanese)
- **car_name**: Vehicle model name

## Analysis & Models

### 1. Classification and Regression Trees & Clustering

- Implemented both classification and regression trees to predict car origin and MPG
- Compared model performance with different tree depths
- Analyzed feature importance to understand key predictors
- Created visualizations of decision boundaries
- **K-Means Clustering**:
  - Explored natural groupings in the auto data
  - Determined optimal number of clusters using elbow method
  - Characterized cluster profiles by key features
  - Analyzed relationship between clusters and car origins
  - Visualized clusters in feature space
- [View Code](https://github.com/rahitya-123/Machine-Learning-Models/blob/main/Classification_and_Regression_Trees.ipynb)

### 2. Association Rule Mining

- Transformed continuous data into meaningful categories for analysis
- Used Apriori algorithm to discover frequent itemsets
- Generated association rules with support, confidence, and lift metrics
- Identified relationships between car features, MPG, and origins
- Visualized rule metrics and relationships
- [View Code](https://github.com/rahitya-123/Machine-Learning-Models/blob/main/Association_Rule_Mining.ipynb)

### 3. Linear Discriminant Analysis (LDA)

- Applied LDA to classify cars by region of origin
- Projected data onto discriminant functions for visualization
- Analyzed coefficients to understand feature importance
- Evaluated classification performance with accuracy and cross-validation
- Visualized class separations in LDA space
- [View Code](https://github.com/rahitya-123/Machine-Learning-Models/blob/main/Linear_Discriminant_Analysis.ipynb)

### 4. Support Vector Machines (SVM)

- Implemented SVMs for both classification (car origin) and regression (MPG)
- Performed hyperparameter tuning using grid search
- Visualized decision boundaries using PCA projection
- Analyzed residuals and feature importance
- Compared performance across different car origins
- [View Code](https://github.com/rahitya-123/Machine-Learning-Models/blob/main/Support_Vector_Machines.ipynb)

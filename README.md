# Crop Recommendation System Using Machine Learning Algorithms

## Overview
This project utilizes machine learning algorithms to recommend suitable crops based on various environmental factors such as temperature, humidity, rainfall, etc. The algorithms used include Linear Regression, Logistic Regression, Decision Tree Classifier, and XGBoost.

## Features

- **Data Preprocessing:** Includes handling missing values, encoding categorical data using LabelEncoder, and scaling features using StandardScaler.

- **Model Training and Evaluation:** Trains multiple models (Linear Regression, Logistic Regression, Decision Tree Classifier, and XGBoost) to predict the crop type based on input features.

- **Model Comparison:** Evaluate and compares the performance of each model using accuracy scores.

 - **Visualization:** Utilizes graphs (like bar plots, and scatter plots) to visualize data distributions and model performance.

# Technologies Used
- Python
- Pandas
- Scikit-learn
- XGBoost
- Matplotlib and Seaborn for data visualization

# Dataset
[Crop_Recommendation.csv: Dataset used for training and testing.](https://www.kaggle.com/datasets/varshitanalluri/crop-recommendation-dataset/data)

# Conclusion
- **XGBoost** and **Decision Tree Classifier** are recommended as the best models for the crop recommendation system, both achieving high accuracies above 97%. XGBoost, in particular, excels due to its ability to handle complex datasets and optimize predictive performance.

- **Logistic Regression** also performed well and is suitable for applications where binary classification of crops based on environmental data is required.

- **Linear Regression** showed significantly lower accuracy and is not recommended for this task, as it struggled to capture the intricate relationships needed for accurate crop prediction.

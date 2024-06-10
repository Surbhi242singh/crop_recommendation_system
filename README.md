# crop_recommendation_system

This Crop Recommendation System is a machine learning project aimed at assisting farmers in making informed decisions about which crops to plant, By analyzing the soil and climate data. The system can recommend the most suitable crops for a given set of conditions, maximizing yield and productivity. The project leverages data preprocessing, outlier removal, normalization, and a Random Forest classifier, achieving a high accuracy of 99.71% through hyperparameter tuning using Grid Search Cross-Validation (CV).

## Data
The dataset used in this project consists of various features relevant to crop growth, including:

1. Soil composition (nitrogen, phosphorus, potassium levels)
2. Temperature
3. Humidity
4. pH value
5. Rainfall

## Data Preprocessing
1. Importing the Data: The data was imported using pandas.
2. Analysis: Basic exploratory data analysis (EDA) was conducted to understand the distribution and relationships within the data.
3. Outlier Removal: Outliers were identified and removed to improve model performance.
4. Normalization: The data was normalized to ensure that all features contribute equally to the model.

## Model Training
A Random Forest classifier was chosen for this project due to its robustness and ability to handle diverse datasets. The following steps were involved in model training:

- Hyperparameter Tuning: Grid Search Cross-Validation (Grid Search CV) was used to find the best hyperparameters for the Random Forest classifier.
- Model Training: The classifier was trained on the preprocessed data, achieving an accuracy of 99.71%.

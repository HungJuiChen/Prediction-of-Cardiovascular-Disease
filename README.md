# Cardiovascular Disease Prediction

## Overview
This project predicts cardiovascular disease based on various health indicators using machine learning techniques. The dataset used is the **Cardiovascular Disease Kaggle Dataset (2018)**. The analysis involves data preprocessing, exploratory data analysis, and classification models such as **Decision Trees** and **Random Forests**.

## Dataset
The dataset contains **70,000** records with the following features:
- **id**: Unique identifier
- **age**: Age in days
- **gender**: 1 = Female, 2 = Male
- **height**: Height in cm
- **weight**: Weight in kg
- **ap_hi**: Systolic blood pressure
- **ap_lo**: Diastolic blood pressure
- **cholesterol**: Cholesterol levels (1: normal, 2: above normal, 3: well above normal)
- **gluc**: Glucose levels (1: normal, 2: above normal, 3: well above normal)
- **smoke**: Whether the patient smokes (0: No, 1: Yes)
- **alco**: Alcohol consumption (0: No, 1: Yes)
- **active**: Physical activity level (0: No, 1: Yes)
- **cardio**: Presence of cardiovascular disease (0: No, 1: Yes)

## Project Structure
- **Mini-Project.ipynb**: Jupyter notebook containing the complete analysis and model implementation.
- **cardio_train.csv**: Dataset used for training and testing.

## Methodology
### 1. Data Preprocessing
- Handled missing values and outliers.
- Normalized and encoded categorical variables.
- Split the dataset into training and testing sets.

### 2. Exploratory Data Analysis
- Visualized distributions of key variables.
- Identified significant correlations, highlighting **systolic blood pressure** as a key predictor.

### 3. Machine Learning Models
#### **Decision Tree Classifier**
- Implemented a classification tree to predict cardiovascular disease.
- Analyzed feature importance.

#### **Random Forest Classifier**
- Utilized an ensemble of decision trees for better accuracy and robustness.
- Improved generalization performance.

## Results
- The **Random Forest model outperformed the Decision Tree classifier**, achieving higher accuracy.
- **Systolic blood pressure (ap_hi) was identified as a key predictor of cardiovascular disease.**

## Future Work
- Implement additional machine learning models (e.g., Support Vector Machines, Neural Networks).
- Improve feature engineering techniques.
- Deploy the model as a web application.


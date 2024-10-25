# Heart Disease Prediction Model using Machine Learning

## Description
- This project implements a heart disease prediction model using various machine learning techniques.
- The model analyzes a dataset of patients to predict the presence of heart disease based on features like age, BMI, Mean Arterial Pressure, cholesterol and blood sugar levels.

## Methodology
- Dataset used: **[Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)**

### Data Preprocessing
- Manual Feature Engineering:
	- Identification and removal of outliers based on specified thresholds for features like age, height, weight, and blood pressure.
	- Converts age from days to years, calculates BMI, systolic and diastolic blood pressure to MAP and categorizes features into discrete classes for analysis.

### Exploratory Data Analysis
- Visualizations are created using Seaborn and Matplotlib to explore relationships between variuous features and the target variable (heart disease).

The dataset is split into training and testing subsets to assess model performance.

### Machine Learning Models
- The following classifiers are implemented and evaluated with K-Modes Clustering applied to gender specific data for enhanced insights:
	- Decision Tree
	- Random Forest (with GridSearch CV)
	- K-Nearest Neighbors
 
 ### Program file(s):
 - The implementation files can be found here:
 	- [Heart Disease Prediction Jupyter Notebook](https://github.com/ksatrajit0/Heart-Disease-Prediction-ML/blob/main/heart_Disease_Prediction_Model.ipynb)   

### Basic Requirements:
To ensure consistent results ensure the following libraries are installed:

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=ffffff)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/Numpy-v1.21.0-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-v1.3.0-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-v3.4.2-003b57?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-v0.11.1-30a9e0?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-v0.24.2-f7931e?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

|Package Name | Version|
| --- | ---|
| numpy | 1.21.2 |
| pandas | 1.5.3|
|scikit-learn | 1.0.2|
|seaborn | 0.11.2|
|matplotlib | 3.5.1|
|opencv-python | 4.5.3.20210927|
|kmodes | 0.12.1|

## Credit(s):
- Collaborator: Shruthum Dutta

> Thank you very much and feel free to submit issues or pull requests to enhance this project!

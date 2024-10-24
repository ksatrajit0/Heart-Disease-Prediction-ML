# Heart Disease Prediction Model

This project implements a heart disease prediction model using various machine learning techniques.
The model analyzes a dataset of patients to predict the presence of heart disease based on features like age, BMI, Mean Arterial Pressure, cholesterol and blood sugar levels.

*Data Preprocessing*

    Outlier Detection: The model identifies and removes outliers based on specified thresholds for features like height, weight, and blood pressure.
    Feature Transformation: Converts age from days to years, calculates BMI, and categorizes features into classes.

*Exploratory Data Analysis*

	Visualizations are created using Seaborn and Matplotlib to explore relationships between features and the target variable (heart disease).

*Machine Learning Models*
	
 The following classifiers are implemented and evaluated:

    Decision Tree Classifier
    Random Forest Classifier
    K-Neighbors Classifier

The dataset is split into training and testing subsets to assess model performance.

*Visualization*

	Graphs are generated to display the accuracy of K-Neighbors classifiers on both training and testing datasets, along with count plots for categorical features.

*Contributing*

	Contributions are welcome! Feel free to open issues or submit pull requests.

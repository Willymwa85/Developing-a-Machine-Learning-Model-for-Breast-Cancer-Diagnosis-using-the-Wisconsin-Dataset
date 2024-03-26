# Developing-a-Machine-Learning-Model-for-Breast-Cancer-Diagnosis-using-the-Wisconsin-Dataset
#Introduction

Breast cancer is a widespread form of cancer affecting females worldwide
The Wisconsin Breast Cancer Dataset (WBCD) is used for developing and assessing breast cancer diagnosis models
Purpose is to evaluate the WBCD classifier and build a machine learning model to classify tumors as malignant or benign

#Research Questions
How do feature engineering methods improve classifiers' ability to predict breast cancer diagnosis?
What effect does the relationship between tumor size and perimeter have on clinical diagnosis and treatment?
How does ensemble modeling enhance machine learning algorithms' ability to generalize breast cancer assessment compared to single-model techniques?

#Results
#Data Preprocessing and Exploration
Dataset has 569 rows, 33 columns with category and numerical data
Strongly correlated features like perimeter_mean and radius_mean
Frequent cases have mean radius values of 12 and 13
Direct proportionality between radius_mean and perimeter_mean

#Model Development and Evaluation
Dataset split into training (455 samples) and testing (114 samples) sets
Model achieved 96.7% precision on training set, above 97% on test set
Outperformed baseline random and "always M" models

#Insights and Future Work
Direct correlation between tumor size and perimeter observed
Frequent tumor sizes of mean radius 12-13 can aid clinicians
Advanced feature engineering, ensemble methods, larger datasets recommended to improve generalization

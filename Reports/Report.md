# Mortality Prediction Project Report
## Introduction
The main objective of this project is to predict the mortality rate of patients, specifically whether a person will live or die, based on different ML techniques. The project focuses on building a machine learning model using various ML algorithms and analyzing different attributes that can help predict the outcome.

## Motivation
The predictors of in-hospital mortality for intensive care units (ICU)-admitted HF patients remain poorly characterized. This project aims to develop and validate a prediction model for all-cause in-hospital mortality among ICU-admitted HF patients. By building a machine learning model, we can leverage different ML techniques to predict the mortality rate and gain insights into the factors influencing the outcome.

- Project Timeline
1. Data Analysis
2. Data Preprocessing
    - Handling NAN values for float variables
    -   Visualizing the dependent variable
    - Exploring the correlation between variables
    - Analyzing the distribution of continuous variables 
3. Model Building and Prediction using ML models
    - Splitting the data into training and testing sets
	- Standardizing the data
	- Model Selection and Evaluation
	- Using the XG Boost Classifier model
	- Plotting the ROC and Accuracy curves
	- ![RocCurveDisplay](https://github.com/pras-ops/Hospital_Mortality_Prediction/assets/56476064/c4045153-c38c-4db7-8b2d-37fb0b5c0564)

## Data Description
The project utilizes a dataset with various attributes that can help in predicting the mortality rate. 
The dataset includes features such as:
### age ![Age](https://github.com/pras-ops/Hospital_Mortality_Prediction/assets/56476064/6951f68c-8166-4958-9bf8-016ffc6445f9)

### gender ![BMI](https://github.com/pras-ops/Hospital_Mortality_Prediction/assets/56476064/056823eb-e729-4b24-a7a7-c9a54e32c753)

### BMI![BMI](https://github.com/pras-ops/Hospital_Mortality_Prediction/assets/56476064/82e9cc42-684c-44c1-bb46-467aead50448)

presence of hypertension, atrial fibrillation, CHD with no MI, diabetes, and many more. The dependent variable is the outcome indicating whether a person survived or not.

## Results and Evaluation
The following evaluation metrics were obtained for the model:

|  Precision: 0.88 | Recall: 0.98  |
| :------------: | :------------: |
|  F1-score: 0.93 |  Accuracy: 0.87 |


The confusion matrix for the model is as follows:

|   |  Predicted Not Survived |Predicted Survived   |
| :------------: | :------------: | :------------: |
 |Actual Not Survived   | 296  |  5 |
 |Actual Survived   |41   | 12  |

## Conclusion
Based on the analysis and evaluation, we successfully built a machine learning model to predict the mortality rate of patients. The model showed promising results with high precision, recall, and accuracy. By leveraging different ML techniques and analyzing various attributes, we were able to gain insights into the factors influencing the outcome.

The project highlights the importance of machine learning in healthcare and its potential to assist in predicting patient outcomes. Further improvements and optimizations can be made to enhance the model's performance and applicability in real-world scenarios.

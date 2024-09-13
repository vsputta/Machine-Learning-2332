Predicting Cardiovascular Disease (CVD) Risk Using Machine Learning

Overview
This project aims to develop a machine learning model to predict cardiovascular disease (CVD) risk by incorporating both traditional medical factors (e.g., age, hypertension, smoking status) and socio-economic/environmental indicators (e.g., income, residence type). The goal is to improve predictive accuracy and provide deeper insights into CVD risk factors, especially those often overlooked in traditional models.

Problem Statement
Existing CVD risk prediction models often focus on medical factors, missing the influence of socio-economic and environmental conditions. We address this gap by building machine learning models that integrate both sets of factors to more accurately predict CVD risk.

Dataset
Source: Cardiovascular Disease Detection Dataset
Rows: 5,111 patients
Features: 12 columns including BMI, average glucose levels, hypertension, heart disease history, smoking status, and sociodemographic factors (age, gender, working type, residence type, marriage status).
Methods
We used the following machine learning models:

Logistic Regression: To predict binary outcomes for CVD risk based on key indicators.
K-Nearest Neighbors (KNN): To assess heart disease probability by considering the nearest neighbors in the dataset.
Decision Tree: To classify patients based on factors like age and glucose levels.
Random Forest: An ensemble method to improve accuracy by combining multiple decision trees.
Ensemble Model: Combined predictions from all models, though it showed limited effectiveness.
Model Evaluation
The models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Curve Analysis

Next Steps
Feature Engineering: Incorporate new variables such as interaction terms and domain-specific transformations to improve model accuracy.
Data Augmentation: Integrate additional socio-economic and environmental data to enrich the feature set.
Collaborative Ethical Framework: Collaborate with healthcare professionals to ensure models are clinically relevant and ethically sound, considering the biases in socio-economic variables.


Contributors
Varun Putta
Zhiyi Ying
Hang Lei


For more details and the code, refer to the project files in this repository.

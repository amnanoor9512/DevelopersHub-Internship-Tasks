# DevelopersHub-Internship-Tasks
Advanced Data Science &amp; AI/ML Internship Tasks (DevelopersHub Corporation)

🔹 Objective

The goal of this task is to predict whether a bank customer will subscribe to a term deposit as part of a marketing campaign.
We use the Bank Marketing Dataset and apply machine learning classification models.

🔹 Dataset

Name: Bank Marketing Dataset (bank.csv)

Source: UCI Machine Learning Repository

Target Variable: y (yes/no → whether the customer subscribed to a term deposit)

Key Features: age, job, marital, education, default, balance, housing loan, duration of call, campaign contact, etc.

🔹 Steps Followed

Data Loading & Exploration

Loaded dataset with pandas

Inspected structure using .info(), .head(), and value counts of the target variable

Data Preprocessing

Encoded categorical features using LabelEncoder

Split dataset into training (80%) and testing (20%) sets with stratified sampling

Model Training

Logistic Regression

Random Forest Classifier

Evaluation Metrics

Accuracy

Classification Report (Precision, Recall, F1-Score)

Confusion Matrix (visualized with heatmap)

ROC Curve and AUC Score

Explainability (XAI)

Used SHAP (SHapley Additive exPlanations) for feature importance

Generated a summary plot to show which features impact predictions

(Optional) Generated force plot for local interpretability of single predictions

🔹 Results

Random Forest performed better than Logistic Regression in terms of accuracy and F1-score.

The most important features influencing predictions were:

duration of the last call

poutcome (previous marketing campaign outcome)

contact method

balance (customer’s account balance)

age

SHAP Plots clearly explained how these features contribute to predictions.

🔹 Skills Gained

✔️ Data Preprocessing (Label Encoding, Stratified Split)
✔️ Classification Modeling (Logistic Regression, Random Forest)
✔️ Model Evaluation (Confusion Matrix, ROC Curve, AUC, F1-Score)
✔️ Explainable AI (XAI) with SHAP

🔹 How to Run the Notebook

Clone this repository

Install required libraries:

pip install pandas numpy scikit-learn shap matplotlib seaborn


Place bank.csv in the project folder

Open Jupyter Notebook / VSCode and run the cells

🔹 Conclusion

This project demonstrates how machine learning models can be applied to predict customer behavior in marketing campaigns. Using explainability techniques like SHAP, we can understand not just how accurate the model is, but also why it makes certain predictions, which is crucial for real-world business applications.

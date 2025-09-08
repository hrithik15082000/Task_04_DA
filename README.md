Customer Churn Prediction – Random Forest
📌 Overview

This project focuses on predicting customer churn for a telecom company using machine learning. The dataset contains customer demographic, account, and service usage information. A Random Forest Classifier is used to model churn behavior, evaluate performance, and save the trained model for deployment.

🎯 Objectives

Apply data preprocessing: binary encoding, one-hot encoding, and scaling

Split dataset into train and test sets

Train Random Forest Classifier for churn prediction

Evaluate model performance using accuracy, classification report, and confusion matrix

Visualize feature importance

Save trained model for deployment or future use

🛠 Tools & Technologies

Python (Pandas, NumPy, Scikit-learn)

Matplotlib & Seaborn for visualization

Joblib for model saving

📂 Dataset Description

Binary Categorical Columns: Gender, Senior Citizen, Partner, Dependents, Phone Service, Multiple Lines, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies, Paperless Billing

Numerical Columns: Tenure Months, Monthly Charges, Total Charges

Multi-class Categorical Columns (one-hot encoded): Contract, Payment Method, Internet Service

Target Column: Churn Value

Total Records: Depends on dataset size

🔑 Steps Performed

Data Preprocessing

Encode binary categorical columns using LabelEncoder

Use one-hot encoding for multi-class features (already encoded in this dataset)

Scale numerical features using StandardScaler

Train-Test Split

Split dataset into X (features) and y (target)

Train-test split: 80% training, 20% testing

Model Training

Random Forest Classifier (n_estimators=100, random_state=42)

Model trained on training set

Evaluation

Accuracy score

Classification report (precision, recall, F1-score)

Confusion matrix visualization

Feature Importance Visualization

Top features contributing to churn prediction visualized via bar chart

Model Saving

Save trained model using joblib for future deployment

Optional Steps

Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)

SHAP / LIME for feature explainability

ROC curve & AUC visualization

📊 Key Insights

Certain features like Contract type, Monthly Charges, and Tenure are strong predictors of churn.

Feature importance helps identify which customer behaviors influence churn the most.

Model achieves reliable accuracy on test data, suitable for business decision-making.

✅ Conclusion

This project demonstrates a complete workflow for customer churn prediction: preprocessing, training, evaluation, and model deployment. It highlights practical data analytics and machine learning skills for real-world business scenarios.

👨‍💻 Author: Hrithik Kumar
📌 Data Analyst

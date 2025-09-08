# 📊 Customer Churn Prediction – Random Forest

## 📌 Overview  
This project focuses on predicting **customer churn** for a telecom company using machine learning. The dataset contains customer demographic, account, and service usage information. A **Random Forest Classifier** is used to model churn behavior, evaluate performance, and save the trained model for deployment.

---

## 🎯 Objectives  
- Apply **data preprocessing**: binary encoding, one-hot encoding, and scaling  
- Split dataset into **train and test sets**  
- Train **Random Forest Classifier** for churn prediction  
- Evaluate model performance using **accuracy, classification report, and confusion matrix**  
- Visualize **feature importance**  
- Save trained model for **deployment or future use**  

---

## 🛠 Tools & Technologies  
- **Python (Pandas, NumPy, Scikit-learn)**  
- **Matplotlib & Seaborn** for visualization  
- **Joblib** for model saving  

---

## 📂 Dataset Description  
- **Binary Categorical Columns:** Gender, Senior Citizen, Partner, Dependents, Phone Service, Multiple Lines, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies, Paperless Billing  
- **Numerical Columns:** Tenure Months, Monthly Charges, Total Charges  
- **Multi-class Categorical Columns (one-hot encoded):** Contract, Payment Method, Internet Service  
- **Target Column:** Churn Value  
- **Total Records:** Depends on dataset size  

---

## 🔑 Steps Performed  
1. **Data Preprocessing**  
   - Encode binary categorical columns using LabelEncoder  
   - One-hot encode multi-class features (already done)  
   - Scale numerical features using StandardScaler  

2. **Train-Test Split**  
   - Split dataset into X (features) and y (target)  
   - Train-test split: 80% training, 20% testing  

3. **Model Training**  
   - Random Forest Classifier (n_estimators=100, random_state=42)  
   - Model trained on training set  

4. **Evaluation**  
   - Accuracy score  
   - Classification report (precision, recall, F1-score)  
   - Confusion matrix visualization  

5. **Feature Importance Visualization**  
   - Top features visualized via bar chart  

6. **Model Saving**  
   - Save trained model using joblib  

7. **Optional Steps**  
   - Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)  
   - SHAP / LIME for feature explainability  
   - ROC curve & AUC visualization  

---

## 📊 Key Insights  
- Features like Contract type, Monthly Charges, and Tenure are strong predictors  
- Feature importance helps understand customer behavior influence  
- Model achieves reliable accuracy on test data  

---

## ✅ Conclusion  
Complete workflow for customer churn prediction: preprocessing, training, evaluation, and deployment. Highlights practical data analytics and ML skills.

👨‍💻 **Author:** Hrithik Kumar  
📌 *Data Analyst*


👨‍💻 **Author:** Hrithik Kumar  
📌 *Data Analyst*

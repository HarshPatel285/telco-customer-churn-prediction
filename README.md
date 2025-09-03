# 📞 Telco Customer Churn Prediction

This project focuses on predicting **customer churn in the telecom sector** using machine learning.  
It applies **predictive modeling, feature engineering, and model tuning** to help businesses identify customers at high risk of leaving.

---

## 🚀 Project Overview
- Dataset: **Telco Customer Churn Dataset (7,000+ records)**
- Objective: Predict whether a customer will churn (binary classification)
- Models compared: **Logistic Regression, Random Forest, XGBoost**
- Best Model: **XGBoost** with **83.5% AUC**
- Deliverables: End-to-end Python pipeline with exportable churn risk scores

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling & transformation
2. **Model Building**
   - Logistic Regression (baseline)
   - Random Forest
   - XGBoost (best performing)
3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1, AUC
   - ROC curves & feature importance
4. **Deployment**
   - Exported trained model using **Pickle (.pkl)**
   - Created **batch prediction script** to process new data and output Excel reports with churn risk scores

---

## 📊 Results
- Best Model: **XGBoost**
- Achieved **83.5% AUC**
- Generated **Excel reports with churn probabilities** for business use
- Feature importance analysis shows contract type & tenure are strong churn predictors

---

## 📦 Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn, openpyxl  
- **Environment:** Jupyter Notebook  

---

## 🖼️ Screenshots
(Add ROC curve, confusion matrix, and churn risk score sample Excel output here)

---

## 🔮 Future Improvements
- Deploy as a **Streamlit/Flask web app** for interactive churn risk scoring  
- Add **SHAP explainability** for better model interpretation  
- Explore **deep learning models** (LSTM, ANN) for sequential telco data  

---

## ✨ Author
👨‍💻 Harsh Patel  
Master’s in Data Analytics | Data Engineering & ML Enthusiast  
🔗 [LinkedIn](https://www.linkedin.com/in/harshpatel285) | 📧 [Email](mailto:hsp498.ca@gmail.com)

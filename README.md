# Predicting-Titanic-Survival-with-Machine-Learning-A-Historical-Data-Case-Study
A machine learning project that predicts Titanic passenger survival using Logistic Regression. Includes data cleaning, feature engineering, model training, and evaluation using Python and Scikit-learn. A clean, end-to-end workflow built in Jupyter Notebook.

# 🚢 Predicting Titanic Survival Using Logistic Regression: A Complete ML Pipeline

This project demonstrates a complete Machine Learning pipeline for predicting the survival of passengers aboard the Titanic using *Logistic Regression. It highlights how **data preprocessing, **feature engineering, and **classical ML models* can extract meaningful insights from real-world historical data.

---

## 📌 Project Overview

The objective of this project is to analyze key passenger attributes — such as *Age, **Gender, **Ticket Class, and **Embarkation Point* — to predict whether a passenger survived the Titanic disaster.  
The dataset was thoroughly cleaned, transformed, and modeled using industry-standard machine learning practices.

---

## 🔍 Key Steps in the Analysis

### 1️⃣ Data Cleaning & Preprocessing
- Loaded the Titanic dataset and assessed data quality.
- Removed non-contributing columns: *PassengerId, **Name, **Ticket, and **Cabin*.
- Handled missing values:
  - *Age* → filled using median  
  - *Embarked* → filled using mode  
- Converted categorical features (*Sex, **Embarked) into numerical format using **one-hot encoding*.
- Ensured a clean, structured dataset for model training.

---

## 📊 Exploratory Data Insights
- Analyzed distributions of key features such as *Age, **Fare, **Gender, and **Survival*.
- Observed strong survival correlations with:
  - Passenger Class (1st Class more likely to survive)
  - Gender (Females had higher survival rate)
- Identified useful patterns that guided feature selection and modeling assumptions.

---

## 🤖 Model Building with Logistic Regression
- Split the dataset into training and testing sets for unbiased evaluation.
- Applied *Logistic Regression*, ideal for binary classification problems.
- Trained the model to learn survival patterns based on engineered features.
- Generated predictions on unseen test data.

---

## 📈 Model Evaluation
Evaluated model performance using:
- *Accuracy Score*
- *Classification Report* (Precision, Recall, F1-Score)

The results demonstrated strong predictive capability, especially for identifying survival patterns linked to *gender* and *passenger class*.

---

## 🛠 Tools & Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Modeling | Scikit-learn |
| Development | Jupyter Notebook |

---

## 🧭 Conclusion
This project showcases how effective *data preprocessing, **feature engineering, and **classical machine learning models* can deliver reliable results, even with a relatively small dataset.  
*Logistic Regression* provided solid predictive accuracy and interpretability, making it an excellent choice for historical and binary classification problems.

---

## 📌 Future Enhancements
- Try advanced models (Random Forest, XGBoost, SVM)
- Deploy as a web app using Flask or Streamlit
- Perform hyperparameter tuning
- Use SHAP for model explainability

---

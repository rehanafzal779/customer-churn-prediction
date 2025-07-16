# 🔁 Customer Churn Prediction – Internship Task 3

## 📌 Objective

Predict whether a customer is likely to leave the bank (churn) using classification models, and understand which features most influence this behavior.

---

## 📊 Dataset

- **Dataset**: Churn Modelling Dataset (from Kaggle)
- **Target Variable**: `Exited`
- **Features**: CreditScore, Geography, Gender, Age, Balance, etc.

---

## 🛠️ Methodology

1. **Data Preprocessing**:
   - Dropped irrelevant columns (`CustomerId`, `RowNumber`, `Surname`)
   - Label encoded `Gender`
   - One-hot encoded `Geography`
   - Standardized numeric features
2. **Modeling**:
   - Used Random Forest Classifier
   - Evaluated using accuracy and confusion matrix
3. **Feature Importance**:
   - Identified top features influencing churn using model importance

---

## 📈 Results

- **Model Accuracy**: ~86%
- **Top Features**: Age, Balance, and Geography were key influencers

---

## 📁 Files

- `churn_prediction.ipynb`: Full Jupyter notebook
- `Churn_Modelling.csv`: Dataset
- `README.md`: Project summary

---

## 📬 Author

Ahmad Afzal  

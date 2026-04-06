# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Problem Statement
Credit card fraud is a major issue in the financial sector, leading to significant monetary losses every year. The goal of this project is to build a machine learning model that can accurately detect fraudulent transactions and distinguish them from legitimate ones.

## 📊 Dataset
The dataset used in this project contains anonymized credit card transaction data.  

- Features: Numerical variables (V1, V2, ..., V28) obtained via PCA transformation  
- Additional Features:
  - `Time`: Time elapsed between transactions  
  - `Amount`: Transaction amount  
- Target Variable:
  - `Class`:  
    - 0 → Legitimate transaction  
    - 1 → Fraudulent transaction  

> Note: The dataset is highly imbalanced, with very few fraud cases compared to normal transactions.

## ⚙️ Methodology
The following steps were followed to build the fraud detection system:

1. **Data Preprocessing**
   - Handling missing values (if any)
   - Feature scaling (especially for `Amount`)
   - Addressing class imbalance (e.g., undersampling/oversampling)

2. **Exploratory Data Analysis (EDA)**
   - Understanding distribution of features
   - Visualizing fraud vs non-fraud cases

3. **Model Building**
   - Applied classification algorithms such as:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - (Optional) XGBoost / SVM

4. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

## 📈 Results
- The model successfully identifies fraudulent transactions with high accuracy.
- Special focus was given to **Recall**, as detecting fraud cases is more important than overall accuracy.
- Performance improved after handling class imbalance.

## 💼 Business Impact
- Helps financial institutions detect fraud in real-time
- Reduces financial losses due to unauthorized transactions
- Improves customer trust and security
- Enables faster and more efficient fraud investigation

## 🚀 Future Improvements
- Implement deep learning models
- Use real-time streaming data
- Deploy as a web application or API
- Improve handling of imbalanced data using advanced techniques (SMOTE, Ensemble methods)

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

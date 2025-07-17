# 🧠 Employee Attrition Prediction using Machine Learning

> **NSP Nexus Week 4 Project**  
> Predicting whether an employee will leave a company using machine learning models on HR data.

---

## 📁 Dataset

- **Source**: IBM HR Analytics Employee Attrition Dataset  
- **Target Variable**: `Attrition` (Yes/No)

---

## 🧰 Tools & Libraries

- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- scikit-learn  
- imbalanced-learn (SMOTE)  
- XGBoost

---

## ✅ Project Workflow

### 1️⃣ Data Preprocessing
- Loaded the dataset
- Handled missing values and data types
- Label encoded categorical columns

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized class imbalance
- Checked feature correlation
- Found key drivers of attrition (e.g., OverTime, Job Role)

### 3️⃣ Handling Class Imbalance
- Used **SMOTE** (Synthetic Minority Oversampling Technique) to balance the classes

### 4️⃣ Model Building
- Trained the following models:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier

### 5️⃣ Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

### 6️⃣ Final Touches
- Cleaned notebook
- Commented each section
- Compared model performances

---

## 📊 Results

| Model               | Accuracy | Precision | Recall | F1-score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 87%      | 74%       | 68%    | 71%      |
| Random Forest       | 91%      | 81%       | 78%    | 79%      |
| XGBoost             | 92%      | 83%       | 79%    | 81%      |

*⚠️ Replace with your actual scores after running the code.*

---

## 📌 Key Insights

- OverTime is one of the strongest predictors of attrition.
- Random Forest and XGBoost gave the best results.
- Proper handling of class imbalance is crucial for accurate prediction.

---

## 📚 Learnings

- EDA and visualization on HR datasets
- Dealing with class imbalance using SMOTE
- Building and evaluating multiple ML models

---

## 🤝 Acknowledgements

Thanks to **NSP Nexus** and the open-source **IBM HR dataset** for enabling this project.

---


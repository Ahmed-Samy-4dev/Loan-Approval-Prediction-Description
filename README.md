# 📊 Loan Approval Prediction

This project predicts whether a loan application will be approved based on applicant details.  
It applies **Machine Learning models** such as **Logistic Regression** and **Decision Trees**, with techniques like **SMOTE oversampling** to handle imbalanced data.

---

## 🚀 Project Workflow
1. **Data Exploration & Cleaning**  
   - Checked data types, missing values, and unique values.  
   - Handled categorical and numerical features separately.  

2. **Feature Preparation**  
   - Encoded categorical variables (`education`, `self_employed`).  
   - Scaled numerical variables.  

3. **Model Training**  
   - **Logistic Regression** (baseline model).  
   - **Logistic Regression with SMOTE** (oversampling).  
   - **Decision Tree Classifier** (tuned hyperparameters).  

4. **Evaluation Metrics**  
   - Precision, Recall, and F1-Score.  
   - Cross-validation for consistency.  
   - Compared models based on business context (false positives matter more).  

---

## 📈 Results
- Logistic Regression: ✅ good precision, consistent performance.  
- SMOTE: ⚠️ improved recall but introduced false positives.  
- Decision Tree: ⭐ best trade-off with higher F1-Score and precision.  

**Final Choice:** Decision Tree Classifier performed best for this dataset.

---

## 📦 Dataset
- Loan-Approval-Prediction-Dataset (Kaggle)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Matplotlib  
- scikit-learn  
- imbalanced-learn (SMOTE)

---

## 📂 Project Structure
loan-approval-prediction/

│── data/

│     └── loan_approval_dataset.csv       # Original dataset

│

│── notebooks/

│     └── loan_approval.ipynb  # Jupyter Notebook with full workflow

│

│── README.md                           # Project documentation

│── requirements.txt                    # Python dependencies

│── .gitignore                          # Ignore unnecessary files

│── LICENSE                             # License file

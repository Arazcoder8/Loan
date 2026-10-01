# Machine Learning Project for Loan Prediction data

---

## 📌 Overview

Loan prediction using machine learning classification models, preprocessing, model tuning, and evaluation.

---

## 📊 about Dataset 

- **Number of Columns:** 7
- **Number of Rows :** 2000
- **Number of Duplicates :** 0
- **Number of Nan Values :** 0
* Columns : `Age`, `Income`, `Credit_Score`, `Loan_Amount`, `Loan_Term`, `Employment_Status`, `Loan_Approved`
* Columns That Don`t Matter : None
* Target : Loan_Approved
* Classification Problem

---

## 🧠 Models

Models Used :

* XGBoost 
* LightGBM
* Gradient Boosting
* CatBoost

---

## ⚙️  Preprocessing

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Hyperparameter Tuning
* Model Evaluation
* Evaluation Metrics

---

## 🛠️ Technologies

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* LightGBM
* CatBoost
* Joblib

---

## 📊 Model Evaluation

- The model Evaluated by accuracy,precision,recall,f1,roc-auc

---

## 📈 Results


| Model | Accuracy | Precision | Recall | F1 | ROC-AUC | 
| :--- | ---: | ---: | ---: | ---: | ---: |
| XGBoost | 100 | 100 | 100 | 100 | 100 |
| LightGBM | 100 | 100 | 100 | 100 | 100 |
| GradientBoosting | 100 | 100 | 100 | 100 | 100 |
| CatBoost | 100 | 100 | 100 | 100 | 100 |

---

### Results Note

All evaluated models achieved 100% on Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

Additional experiments and checks were performed to investigate potential data leakage, but no direct data leakage was identified.

The consistently perfect performance appears to be related to the strong predictive relationship between the available features and the target variable. The features in this dataset make the target classes highly separable, resulting in perfect classification performance across all evaluated models.

---

## 📂 Project Structure

```text
.
├── data/
├── images/
├── models/
├── catboost_info/
├── .gitignore
├── Loan.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

Install the required dependencies:

```text

pip install -r requirements.txt

```

Then open and run the Jupyter Notebook:

Loan.ipynb

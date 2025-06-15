# Credit Risk Analysis Using Machine Learning

##  Project Overview
This project performs **Credit Risk Analysis** by leveraging machine learning to predict whether a loan will be **fully paid** or **charged off** (i.e., defaulted). The goal is to assist financial institutions in assessing borrower risk using historical loan and customer financial data.

The analysis includes **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, and **model development** using multiple classifiers. The final model aims to identify key features that influence creditworthiness and assist in automated loan decision-making.

---

##  Objectives
- Load and preprocess loan application data
- Perform EDA to discover trends and risk patterns
- Engineer meaningful features to improve model learning
- Train and compare various ML models
- Evaluate models using appropriate classification metrics
- Identify top predictive features

---

##  Dataset
The dataset includes anonymized financial details of borrowers and their loan status. Key features include:

- `loan_amnt` – Total amount funded
- `term` – Length of the loan
- `purpose` – Reason for the loan
- `emp_length` – Employment length
- `annual_inc` – Annual income
- `loan_status` – Target variable (`Fully Paid` or `Charged Off`)
- `dti` – Debt-to-income ratio
- `credit_score` – Credit score of applicant

>  **Note:** The dataset was preprocessed to remove irrelevant or missing values, and categorical variables were encoded.

---

##  Technologies Used
- **Python**
- **Jupyter Notebook**
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost

---

##  Machine Learning Models
The following classification algorithms were applied:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

**Evaluation Metrics:**
- Accuracy
- Precision, Recall, F1-Score
- ROC-AUC Score
- Confusion Matrix

---

##  Exploratory Data Analysis (EDA)
- Distribution of `loan_status`
- Loan purpose vs default rate
- Credit score and DTI distributions
- Annual income trends and correlation with loan status
- Visualizations: bar plots, histograms, correlation heatmaps

---

##  Feature Engineering
- Label encoding of categorical features
- Credit score binning for risk segmentation
- Ratio features: `income_to_loan`
- Feature selection based on correlation and model importance

---

##  Results & Findings
- **Random Forest** and **XGBoost** outperformed Logistic Regression, with XGBoost yielding the best ROC-AUC score.
- Key predictive features:
  - `credit_score`
  - `dti`
  - `annual_inc`
  - `purpose`
- The models successfully distinguish high-risk (charged off) vs low-risk (fully paid) applicants.

---

##  How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis

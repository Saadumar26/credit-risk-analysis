#  Credit Risk Analysis Using Machine Learning

##  Project Overview

This project focuses on **Credit Risk Analysis** using machine learning techniques to predict the likelihood of a loan applicant defaulting. Accurate credit risk prediction is vital for financial institutions to make informed lending decisions and minimize financial losses.

The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and training classification models to assess credit risk. The final model helps classify applicants as **low-risk** or **high-risk**.

---

##  Objectives

- Preprocess and clean the dataset.
- Perform Exploratory Data Analysis (EDA) to understand patterns.
- Build and evaluate machine learning models to predict credit risk.
- Identify key features influencing creditworthiness.

---

## 📂 Dataset

The dataset used for this project contains anonymized customer financial and loan details. It includes attributes such as:

- `Loan Amount`
- `Loan Purpose`
- `Annual Income`
- `Employment Length`
- `Credit Score`
- `Debt-to-Income Ratio`
- `Loan Status` (Target: Fully Paid / Charged Off)

> **Source:** [Insert dataset source – e.g., Kaggle, UCI, or in-house]

---

##  Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Jupyter Notebook** for development and visualization
- **Machine Learning Models**:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC Curve
  - Confusion Matrix

---

##  Project Workflow

1. **Data Loading & Cleaning**
   - Handle missing values
   - Encode categorical variables
   - Scale numerical features

2. **Exploratory Data Analysis (EDA)**
   - Visualize loan distributions
   - Correlation heatmaps
   - Risk-based feature analysis

3. **Feature Engineering**
   - Binning credit scores
   - Creating income-to-loan ratios
   - Selecting top features based on importance

4. **Model Training & Evaluation**
   - Train/test split
   - Hyperparameter tuning
   - Evaluate models using cross-validation

---

##  Results

- The **Random Forest** model achieved the highest accuracy and balanced performance.
- **Top contributing features** to loan default:
  - Credit Score
  - Debt-to-Income Ratio
  - Loan Purpose
  - Annual Income

> The model can serve as a risk assessment tool to support loan approval processes.

---

##  How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis

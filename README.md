# CreditWise: Machine Learning Loan Approval Predictor

## 📌 Project Overview
CreditWise is a machine learning project designed to automate the loan eligibility process. By analyzing customer details such as applicant income, credit score, existing loans, and DTI ratio, the model predicts whether a loan should be approved or rejected.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Model:** Gaussian Naive Bayes (and other classification algorithms)

## 📊 Key Features & Methodology
1. **Data Preprocessing:** Handled missing values using Mean and Most-Frequent imputation strategies. 
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlation matrices to identify key predictors like Credit Score and Debt-to-Income (DTI) Ratio.
3. **Feature Engineering:** Converted categorical variables into numerical formats using Label Encoding and One-Hot Encoding.
4. **Model Evaluation:** The Naive Bayes model achieved an **Accuracy of 86%**, with a Precision of 0.81 and an F1-Score of 0.75.

## 🚀 How to Run
1. Clone this repository or download the files.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Run the `creditwise_minor_project.ipynb` notebook to view the data pipeline and model training process.

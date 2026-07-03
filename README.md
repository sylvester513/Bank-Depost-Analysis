# 🏦 Bank Loan Status Prediction using Machine Learning

## 📌 Project Overview

This project analyzes historical bank loan application data to identify the key factors influencing loan approval. The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, and the development of machine learning models to predict whether a loan application will be approved.

The objective is to assist financial institutions in making faster, more consistent, and data-driven loan approval decisions.

---

## 🎯 Project Objectives

- Clean and preprocess the loan dataset.
- Handle missing values appropriately.
- Encode categorical variables for machine learning.
- Perform exploratory data analysis (EDA).
- Visualize relationships between variables.
- Train and evaluate multiple machine learning models.
- Compare model performance and identify the best-performing algorithm.

---

## 📂 Dataset Features

The dataset contains the following attributes:

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target Variable)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns (Loan_ID).
- Identified categorical variables.
- Filled missing values:
  - Mode for categorical variables.
  - Mean for numerical variables.
- Encoded categorical variables using Label Encoding.
- Checked feature correlations using a heatmap.

---

## 📈 Exploratory Data Analysis (EDA)

The project includes:

- Distribution of categorical variables
- Correlation heatmap
- Gender vs Loan Status analysis
- Feature relationship visualization

These visualizations provide insights into the factors affecting loan approval.

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and evaluated:

- Random Forest Classifier
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **78.46%** |
| Random Forest | **78.46%** |
| Support Vector Machine | 67.07% |
| K-Nearest Neighbors | 63.82% |

---

## 💡 Key Insights

- Credit history is one of the strongest indicators of loan approval.
- Applicant income and loan amount significantly influence loan decisions.
- Proper data preprocessing improves model performance.
- Logistic Regression and Random Forest achieved the highest prediction accuracy.

---

## 💼 Business Value

This project demonstrates how machine learning can support banks by:

- Improving loan approval consistency.
- Reducing manual decision-making.
- Minimizing lending risk.
- Speeding up loan processing.
- Supporting data-driven financial decisions.

---

## 🚀 Future Improvements

- Apply feature scaling to improve model convergence.
- Perform hyperparameter tuning.
- Use cross-validation for better evaluation.
- Test additional ensemble learning algorithms.
- Deploy the model using Flask, FastAPI, or Streamlit.

---

## 📁 Repository Structure

```
Bank-Loan-Status-Prediction/
│
├── Bank_Loan_Status_Prediction.ipynb
├── bankloan.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Bank-Loan-Status-Prediction.git
```

2. Navigate to the project folder.

```bash
cd Bank-Loan-Status-Prediction
```

3. Install the required packages.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open the notebook and run all cells.

---

## 📌 Conclusion

This project demonstrates the complete machine learning workflow, from data cleaning and visualization to predictive modeling. The developed models can assist banks in making more accurate loan approval decisions while improving operational efficiency.

---

## 👤 Author

**Sylvester Ojwang**

**Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer**

If you found this project useful, consider giving the repository a ⭐ on GitHub.

# Loan-Approval-prediction

This project predicts whether a loan should be approved or not using Support Vector Machine (SVM), a powerful supervised machine learning algorithm. It is based on a YouTube tutorial with step-by-step explanations and enhancements documented.

## 🧠 Project Overview

Financial institutions use loan eligibility systems to evaluate whether a customer is eligible for a loan based on their income, credit history, and other attributes. This project uses the Loan Prediction dataset to build a machine learning model that automates the loan approval process.

### 🔍 Problem Type

* **Binary Classification**
* **Target Variable**: `Loan_Status` (Y/N)

---

## 📁 Dataset

The dataset used includes features like:

| Feature            | Description                        |
| ------------------ | ---------------------------------- |
| Gender             | Male/Female                        |
| Married            | Applicant’s marital status         |
| Dependents         | Number of dependents               |
| Education          | Graduate/Not Graduate              |
| Self\_Employed     | Self-employed status               |
| ApplicantIncome    | Income of the applicant            |
| CoapplicantIncome  | Income of the co-applicant         |
| LoanAmount         | Loan amount applied (in thousands) |
| Loan\_Amount\_Term | Term of the loan (in months)       |
| Credit\_History    | Credit history (1 = yes, 0 = no)   |
| Property\_Area     | Urban/Rural/Semiurban              |
| Loan\_Status       | Approved (Y) or Not Approved (N)   |

---

## ⚙️ Workflow

1. **Import Libraries**: NumPy, Pandas, Matplotlib, Seaborn, and Scikit-learn
2. **Load Dataset**
3. **Data Cleaning**:

   * Fill missing values using `mean()` for numerical and `mode()` for categorical
   * Log transformation on skewed columns like `LoanAmount`
4. **Feature Engineering**:

   * Create new features like `TotalIncome` and `TotalIncome_log`
   * Drop irrelevant or redundant columns
5. **Data Visualization**:

   * Histograms, countplots, and heatmaps to understand distributions and correlations
6. **Encoding**:

   * Convert categorical variables using `LabelEncoder`
7. **Model Training**:

   * Split data into training and test sets
   * Train a **Support Vector Machine (SVM)** classifier
8. **Evaluation**:

   * Accuracy, confusion matrix, and classification report

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**, **NumPy**
* **Matplotlib**, **Seaborn**
* **Scikit-learn** for ML
* **Jupyter Notebook** or any IDE

---

## 📌 Results

* The model predicts loan approval status based on the input features.
* Evaluation metrics show the model's performance (accuracy, precision, recall, F1-score).

---

## 🚀 Getting Started

### Prerequisites

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run the Project

```bash
python loan_approval_prediction.py
```

Or open in Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🧾 Documentation

A full explanation of the project is available in the [Loan_Approval_Project_Documentation](https://docs.google.com/document/d/1mFMDEeFGhyfz3_64jedTtff-CkGGJ_5-4IecIPCZrCA/edit?tab=t.0) file, which includes step-by-step reasoning.

---

## 📚 Reference

* Based on a YouTube tutorial (link provided in the doc file)
* Dataset: provided with the code

---

## 🙋‍♀️ Author

**Faiza Nuha**


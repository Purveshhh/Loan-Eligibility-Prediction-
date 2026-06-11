# Loan Approval Prediction Using Machine Learning

## 📌 Project Overview

This project uses Machine Learning to predict whether a loan application will be approved or rejected based on applicant details such as gender, marital status, income, and loan amount.

The objective is to automate the loan approval process and assist financial institutions in making faster and more accurate lending decisions.

---

## 🚀 Features

- Data Loading and Exploration
- Data Cleaning and Preprocessing
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Data Visualization
- Categorical Data Encoding
- Feature Scaling
- Handling Class Imbalance
- Loan Approval Prediction using Support Vector Machine (SVM)
- Model Performance Evaluation

---

## 📂 Dataset Information

The dataset contains loan application records with the following features:

| Feature | Description |
|----------|-------------|
| Loan_ID | Unique Loan Identifier |
| Gender | Applicant Gender |
| Married | Marital Status |
| ApplicantIncome | Applicant's Income |
| LoanAmount | Requested Loan Amount |
| Loan_Status | Loan Approval Status (Y/N) |

### Target Variable

- **Y** → Loan Approved
- **N** → Loan Rejected

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn
- Jupyter Notebook

---

## 📊 Project Workflow

### 1. Import Libraries

The necessary Python libraries are imported for data analysis, visualization, preprocessing, and machine learning.

### 2. Load Dataset

The loan dataset is loaded using Pandas.

### 3. Data Exploration

- View dataset structure
- Check dimensions
- Analyze data types
- Generate statistical summaries

### 4. Data Cleaning

- Detect missing values
- Handle null values
- Prepare data for modeling

### 5. Exploratory Data Analysis (EDA)

Visualizations are used to understand:

- Loan approval distribution
- Income distribution
- Loan amount distribution
- Relationships between features and loan approval status

### 6. Data Preprocessing

- Label Encoding of categorical variables
- Feature Scaling using StandardScaler
- Handling class imbalance using RandomOverSampler

### 7. Model Training

A Support Vector Machine (SVM) classifier is trained on the processed dataset.

### 8. Model Evaluation

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision and Recall Metrics

---

## 📈 Sample Output

The model predicts whether a loan application will be:

### Approved

```text
Loan Approved (Y)
```

### Rejected

```text
Loan Rejected (N)
```

---

## 📋 Requirements

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn imbalanced-learn
```

Or install directly from:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/Loan-Approval-Prediction.git
```

Navigate to the project directory:

```bash
cd Loan-Approval-Prediction
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Loan_Approval_Prediction.ipynb
```

and run all cells.

---

## 📁 Project Structure

```text
Loan-Approval-Prediction/
│
├── Loan_Approval_Prediction.ipynb
├── loan_data.csv
├── README.md
├── requirements.txt
└── images/
```

---

## 🎯 Future Improvements

- Hyperparameter Tuning
- Feature Engineering
- Comparison with Random Forest and XGBoost
- Model Deployment using Flask or Streamlit
- Real-Time Loan Approval Prediction System

---

## 📌 Results

The Support Vector Machine (SVM) model successfully classifies loan applications based on applicant information. The project demonstrates the use of machine learning techniques for automating loan approval decisions and improving efficiency in the banking sector.

---

## 👨‍💻 Author

**Purvesh Gaikwad**

Machine Learning Project  
Domain: Banking & Finance  
Algorithm Used: Support Vector Machine (SVM)

---

## ⭐ Acknowledgements

This project was developed for learning and demonstrating Machine Learning concepts including data preprocessing, visualization, classification, and model evaluation using Python and Scikit-Learn.
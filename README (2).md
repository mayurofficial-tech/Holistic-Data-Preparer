# 🚀 Holistic Data Preparer

<p align="center">

### 🧹 From Raw Data to Machine Learning Ready Data

**An end-to-end Data Preprocessing & Feature Engineering project**

<br>

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--learn-ML%20Preprocessing-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-Statistics-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</p>

---

# 🎥 Project Demo Video

> **Complete 5–10 minute project demonstration**

### ▶️ [Watch Project Demonstration on Google Drive](https://drive.google.com/file/d/1cawtx4ByRRAdHiOKJk1zNkYevaRxrgV-/view?usp=drive_link)

The video covers the complete project workflow:

- 📥 Data Acquisition
- 🔗 Data Integration
- 🔍 Data Understanding
- 🧹 Data Quality Analysis
- 🕳️ Missing Value Handling
- 🚨 Outlier Detection & Treatment
- 🛠️ Feature Engineering
- 🔤 Encoding
- 🔄 Feature Transformation
- ⚖️ Feature Scaling
- 💾 Final Dataset Preparation

---

# 📌 Project Overview

**Holistic Data Preparer** is an end-to-end Data Science project focused on transforming raw, multi-source data into a clean, structured, and machine-learning-ready dataset.

In real-world Data Science projects, data is often collected from different sources and contains issues such as:

- Missing values
- Duplicate records
- Incorrect data types
- Outliers
- Different feature scales
- Categorical variables
- Skewed numerical distributions

This project demonstrates how these challenges can be handled systematically using Python and popular Data Science libraries.

The complete workflow starts from **Data Acquisition** and ends with a **cleaned and feature-engineered dataset** ready for further Machine Learning applications.

---

# 🎯 Project Objectives

- 📥 Collect data from multiple sources
- 🔗 Integrate data using common identifiers
- 🔍 Understand the structure of the dataset
- 🧹 Perform data quality checks
- 🕳️ Identify and handle missing values
- 📊 Generate a Data Quality Report
- 🚨 Detect and treat outliers
- 🛠️ Create meaningful features
- 🔤 Encode categorical variables
- 🔄 Apply feature transformations
- ⚖️ Scale numerical features
- 💾 Generate a final cleaned dataset
- 🤖 Prepare the dataset for Machine Learning

---

# 🔄 Complete Project Workflow

```text
                 ┌─────────────────────┐
                 │    DATA SOURCES     │
                 └──────────┬──────────┘
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
       CSV Data          JSON Data        SQLite DB
          │                 │                 │
          └─────────────────┼─────────────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Data Integration    │
                 │  Master Dataset     │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Data Understanding  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Data Quality Check  │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Missing Value       │
                 │ Handling            │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Outlier Detection   │
                 │ & Treatment         │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Feature Engineering │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Encoding &          │
                 │ Transformation      │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Feature Scaling     │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ Final Clean Dataset │
                 │    ML Ready Data    │
                 └─────────────────────┘
```

---

# 📂 Project Structure

```text
Holistic-Data-Preparer/
│
├── Dataset/
│   ├── customer_metadata.json
│   ├── Dataset_creation.ipynb
│   ├── final_cleaned_credit_risk_dataset.xlsx
│   ├── loan_data.db
│   └── main_transactions.xlsx
│
├── Data_quality_report.html
│
├── Holistic_Data_Preparer.ipynb
│
├── Holistic_Data_Preparer_Part_A.docx
│
└── README.md
```

---

# 🗂️ Data Sources

The project works with multiple data sources.

## 📄 Transaction Data

**File:** `main_transactions.xlsx`

Contains the main transaction-related data used in the project.

## 👤 Customer Metadata

**File:** `customer_metadata.json`

Contains customer-level metadata.

## 💳 Loan Data

**File:** `loan_data.db`

SQLite database containing loan-related information.

## 📓 Dataset Creation Notebook

**File:** `Dataset_creation.ipynb`

Notebook used during dataset preparation and creation.

---

# 🔍 Data Understanding

After collecting and integrating the data, the next step is to understand the dataset.

The project uses Pandas functions such as:

```python
df.info()
df.describe()
df.shape
df.isnull().sum()
df.duplicated().sum()
```

These checks help understand:

- Number of rows
- Number of columns
- Data types
- Missing values
- Statistical information
- Duplicate records
- Numerical features
- Categorical features

---

# 🧹 Data Quality Analysis

Data quality analysis is performed before applying advanced preprocessing techniques.

The project checks:

- Missing values
- Duplicate records
- Data types
- Numerical distributions
- Categorical variables
- Feature statistics

---

# 📊 Data Quality Report

A detailed HTML-based Data Quality Report is generated using **YData Profiling**.

**Output:** `Data_quality_report.html`

The report provides:

- Dataset overview
- Variable information
- Missing values
- Statistical summaries
- Distributions
- Data quality observations

---

# 🕳️ Missing Data Handling

Different missing-value techniques are demonstrated depending on the feature and situation.

### 🔹 Median Imputation

```python
SimpleImputer(strategy="median")
```

### 🔹 Most Frequent / Mode Imputation

```python
SimpleImputer(strategy="most_frequent")
```

### 🔹 Random Sample Imputation

Missing numerical values can be replaced using randomly selected observed values from the same feature.

### 🔹 Missing Indicator

A separate indicator can preserve information about whether a value was originally missing.

### 🔹 KNN Imputation

```python
KNNImputer(n_neighbors=5)
```

KNN-based imputation estimates missing values using similar observations.

### 🔹 MICE / Iterative Imputation

```python
IterativeImputer(
    max_iter=10,
    random_state=42
)
```

This approach iteratively estimates missing values using relationships between features.

### 🔹 Complete Case Analysis

Complete Case Analysis (CCA) removes rows containing remaining missing values.

---

# 🚨 Outlier Detection & Treatment

The project demonstrates multiple techniques for detecting and treating outliers.

### Detection Techniques

- Z-Score
- IQR Method
- Percentile Method
- Boxplot Visualization

### 📐 Z-Score

```python
stats.zscore()
```

A commonly used threshold for extreme observations is:

```text
|Z| > 3
```

### 📊 IQR Method

```text
IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR
```

### 📈 Percentile Method

Percentile-based detection can use lower and upper percentile boundaries such as:

```text
1st Percentile
99th Percentile
```

### ✂️ Winsorization

Winsorization limits extreme observations rather than directly deleting them.

### 📦 Boxplot Validation

Boxplots are used before and after treatment to visually inspect preprocessing effects.

---

# 🛠️ Feature Engineering

Feature Engineering is used to create additional meaningful information from existing variables.

## 📅 Date Feature Engineering

The `join_date` feature is converted into datetime format.

New features:

```text
join_year
join_month
```

## 📊 Binning

Examples:

```text
annual_income_binned
repayment_history_binned
```

## 🔘 Binary Feature Creation

```text
credit_score_gt_700
```

Represents whether the credit score is greater than 700.

## 📈 Quantile-Based Feature

```text
transaction_count_quantile
```

---

# 🔤 Categorical Encoding

The project demonstrates:

- Label Encoding
- Ordinal Encoding
- One-Hot Encoding
- Binarization

### One-Hot Encoding Examples

```text
loan_purpose_Car
loan_purpose_Education
loan_purpose_Home
loan_purpose_Other
```

---

# 🔄 Feature Transformation

The project demonstrates:

- Log Transformation
- Square Root Transformation
- Function Transformation
- Power Transformation
- Yeo-Johnson Transformation

---

# 🧮 Yeo-Johnson Transformation

The project uses:

```python
PowerTransformer()
```

Yeo-Johnson transformation is useful when numerical data requires a distributional transformation and may contain zero or negative values.

---

# 🧩 ColumnTransformer

`ColumnTransformer` is used to apply different preprocessing operations to different groups of columns.

```text
Numerical Features
        +
Categorical Features
        +
Transformed Features
        +
Scaled Features
```

This helps organize preprocessing systematically.

---

# ⚖️ Feature Scaling

The project demonstrates:

```text
StandardScaler
MinMaxScaler
MaxAbsScaler
RobustScaler
Normalizer
```

### 📏 StandardScaler

Standardizes numerical features around the mean.

```text
Mean ≈ 0
Standard Deviation ≈ 1
```

### 🔢 MinMaxScaler

Transforms values into a specified range, commonly:

```text
0 → 1
```

### 🛡️ RobustScaler

Uses median and interquartile-range based statistics and is useful when outliers are present.

### 📐 MaxAbsScaler

Scales features according to their maximum absolute value and can preserve the sign of the data.

---

# 🧰 Technologies Used

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Statistics | SciPy |
| ML / Preprocessing | Scikit-learn |
| Visualization | Matplotlib, Seaborn |
| Data Quality | YData Profiling |
| Database | SQLite |
| Environment | Jupyter Notebook |
| Version Control | Git, GitHub |

---

# 📋 Key Concepts Covered

```text
✓ Data Acquisition
✓ Data Integration
✓ Data Understanding
✓ Data Quality Analysis
✓ Data Type Validation
✓ Duplicate Data Analysis
✓ Missing Data Analysis
✓ Median Imputation
✓ Mode Imputation
✓ Random Sample Imputation
✓ Missing Indicators
✓ KNN Imputation
✓ MICE / Iterative Imputation
✓ Complete Case Analysis
✓ Outlier Detection
✓ Z-Score
✓ IQR Method
✓ Percentile Method
✓ Winsorization
✓ Outlier Capping
✓ Feature Engineering
✓ Date Feature Extraction
✓ Binning
✓ Quantile Features
✓ Binary Features
✓ Label Encoding
✓ Ordinal Encoding
✓ One-Hot Encoding
✓ Binarization
✓ Log Transformation
✓ Square Root Transformation
✓ Function Transformation
✓ Power Transformation
✓ Yeo-Johnson Transformation
✓ ColumnTransformer
✓ StandardScaler
✓ MinMaxScaler
✓ MaxAbsScaler
✓ RobustScaler
✓ Normalizer
✓ Data Quality Reporting
```

---

# 📁 Important Project Files

| File | Description |
|---|---|
| `Holistic_Data_Preparer.ipynb` | Main preprocessing and feature engineering notebook |
| `Dataset_creation.ipynb` | Dataset creation/preparation notebook |
| `customer_metadata.json` | Customer metadata |
| `main_transactions.xlsx` | Main transaction data |
| `loan_data.db` | SQLite loan database |
| `final_cleaned_credit_risk_dataset.xlsx` | Final processed dataset |
| `Data_quality_report.html` | YData Profiling report |
| `Holistic_Data_Preparer_Part_A.docx` | Project documentation |

---

# ▶️ How to Run

## 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

## 2. Navigate to the Project

```bash
cd Holistic-Data-Preparer
```

## 3. Install Required Libraries

```bash
pip install pandas numpy scipy matplotlib seaborn scikit-learn ydata-profiling openpyxl
```

## 4. Start Jupyter Notebook

```bash
jupyter notebook
```

## 5. Open

```text
Holistic_Data_Preparer.ipynb
```

Run the notebook cells sequentially.

---

# ⚠️ Important Notes

- Keep the `Dataset` folder in the same project structure.
- The notebook uses local dataset files.
- Make sure the required files are available before running the notebook.
- Some preprocessing techniques are demonstrated for learning and comparison.
- The final preprocessing strategy should depend on the dataset and Machine Learning problem.
- Make sure the Google Drive video has appropriate sharing permissions.

---

# 📈 Future Improvements

- 🤖 Machine Learning model training
- 📊 Model evaluation
- 🔄 End-to-end preprocessing pipelines
- 🧪 Automated data validation
- 📈 Model comparison
- 🌐 Streamlit application
- 🚀 Deployment
- 📦 Reusable preprocessing functions
- 🔍 Automated data quality monitoring
- 📋 Experiment tracking

---

# 🏆 Project Outcome

The final outcome is a structured and processed dataset that has gone through a complete Data Preparation workflow.

```text
Raw Multi-Source Data
        ↓
Data Integration
        ↓
Data Understanding
        ↓
Data Quality Analysis
        ↓
Missing Value Handling
        ↓
Outlier Treatment
        ↓
Feature Engineering
        ↓
Encoding
        ↓
Feature Transformation
        ↓
Feature Scaling
        ↓
Clean & ML-Ready Dataset
```

---

# 👨‍💻 Author

## Mayur Makvana

**Data Science & Machine Learning Enthusiast**

This project was developed as part of my practical Data Science learning journey, with a focus on real-world data preprocessing and feature engineering.

---

# ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ **Star**.

Thank you for visiting this project! 🚀

---

<p align="center">

### 🚀 Data → Clean → Transform → Engineer → Scale → ML Ready

**Built with Python & Data Science**

</p>

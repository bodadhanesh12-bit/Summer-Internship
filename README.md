# Customer Churn Prediction & Retention Framework

## Project Overview

Customer Churn Prediction & Retention Framework is a Machine Learning project developed to identify customers who are likely to discontinue a company's services. The project analyzes customer behavior, service usage patterns, contract details, and payment information to predict churn and help businesses improve customer retention.

The framework combines Data Preprocessing, Exploratory Data Analysis (EDA), and Machine Learning techniques to generate insights and predict customer churn effectively.

--

## Project Information

**Project Title:** Customer Churn Prediction & Retention Framework

**Submitted By:** Boda Dhanesh

**Enrollment No:** 24162121004

**Branch:** Computer Science & Engineering

**College:** Ganpat University

---

## Objectives

- Identify customers who are likely to churn.
- Analyze factors influencing customer churn.
- Improve customer retention strategies.
- Reduce revenue loss caused by customer attrition.
- Apply Machine Learning techniques for predictive analytics.

---

##  Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

##  Dataset

Dataset Used:

**Telco Customer Churn Dataset**

Dataset contains:

- Customer ID
- Gender
- Senior Citizen Status
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn Status

---

##  Data Preprocessing

The following preprocessing steps were performed:

- Loaded dataset using Pandas
- Checked missing values
- Converted TotalCharges to numeric datatype
- Removed null values
- Removed duplicate records
- Encoded categorical features
- Verified data consistency

---

## Exploratory Data Analysis (EDA)

Several visualizations were created to understand customer behavior.

### Customer Churn Distribution
- 73.5% customers retained
- 26.5% customers churned

### Contract Type Distribution
- Majority use Month-to-Month contracts
- Long-term contracts have lower churn

### Senior Citizen Analysis
- Smaller customer segment
- Higher tendency to churn

### Paperless Billing Analysis
- Most customers use paperless billing

### Gender Distribution
- Nearly equal distribution between males and females

---

##  Churn Analysis

### Churn Rate by Contract Type
- Highest churn among Month-to-Month customers
- Lowest churn among Two-Year contract customers

### Churn Rate by Internet Service
- Fiber Optic users show highest churn rate

### Churn Rate by Payment Method
- Electronic Check customers have highest churn

### Churn Rate by Gender
- Similar churn rates across genders

### Churn Rate by Customer Tenure
- Highest churn within first year
- Customer loyalty increases with tenure

---

##  Machine Learning Model

### Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm used for classification tasks.

### Working

- Represents customers as data points in multi-dimensional space.
- Creates an optimal hyperplane separating churn and non-churn customers.
- Maximizes the margin between classes.
- Uses support vectors to determine decision boundaries.

### Features Used

- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Internet Service
- Payment Method

### Advantages

- High classification accuracy
- Effective for medium-sized datasets
- Works well in high-dimensional spaces
- Less prone to overfitting

---

## Project Structure

```
Customer-Churn-Prediction/
│
├── Dataset/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── Week-1/
│   ├── Introduction and Project Statement
│   └── Google Colab Tools
│
├── Week-2/
│   ├── Data Preprocessing
│   ├── Python Fundamentals
│   └── EDA Scripts
│
├── Week-3/
│   ├── EDA Report
│   ├── Churn Analysis Graphs
│   └── Support Vector Machine
│
├── README.md
│
└── requirements.txt
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

### Move to Project Folder

```bash
cd customer-churn-prediction
```

### Install Required Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

or open notebooks directly in Google Colab.

---

##  Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis
5. Feature Engineering
6. Model Training (SVM)
7. Churn Prediction
8. Evaluation
9. Retention Strategy Recommendation

---

## Results

- Successfully analyzed customer churn patterns.
- Identified major churn factors.
- Built an SVM-based churn prediction model.
- Generated actionable retention insights.
- Improved understanding of customer behavior.

---

##  Future Scope

- Deploy model using Flask or Streamlit.
- Create real-time prediction dashboard.
- Implement advanced algorithms such as:
  - Random Forest
  - XGBoost
  - Gradient Boosting
  - Neural Networks
- Integrate with CRM systems.

---

##  Learning Outcomes

Through this project, the following skills were developed:

- Data Cleaning
- Data Analysis
- Data Visualization
- Machine Learning
- Support Vector Machine
- Customer Behavior Analysis
- Business Analytics

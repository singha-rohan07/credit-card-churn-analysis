# 💳 Credit Card Customer Churn Analysis

An end-to-end **Data Analytics Portfolio Project** analyzing customer attrition in the banking industry using **Python, SQL, Excel, and Power BI**.

This project analyzes over 10,000 customer records to identify churn patterns, understand customer behavior, and generate actionable business recommendations to improve customer retention.

---

## 📌 Table of Contents

1. [Project Overview](#-project-overview)
2. [Project Objectives](#-project-objectives)
3. [Dataset Information](#-dataset-information)
4. [Tools and Technologies](#-tools-and-technologies)
5. [Project Workflow](#-project-workflow)
6. [Data Cleaning](#-data-cleaning)
7. [Exploratory Data Analysis](#-exploratory-data-analysis)
8. [Statistical Analysis](#-statistical-analysis)
9. [SQL Analysis](#-sql-analysis)
10. [Power BI Dashboards](#-power-bi-dashboards)
11. [Key Business Insights](#-key-business-insights)
12. [Business Recommendations](#-business-recommendations)
13. [Project Structure](#-project-structure)
14. [How to Run the Project](#-how-to-run-the-project)
15. [Future Enhancements](#-future-enhancements)
16. [Author](#-author)

---

## 📌 Project Overview

Customer churn is a major challenge in the banking industry. Losing existing customers can increase acquisition costs, reduce revenue opportunities, and affect long-term profitability.

This project examines customer demographics, credit card usage, transaction behavior, and engagement patterns to identify factors associated with customer attrition.

The analysis combines Python-based data preparation, statistical analysis, SQL queries, Excel reporting, and interactive Power BI dashboards to transform raw customer data into meaningful business insights.

## 🎯 Project Objectives

- Analyze customer churn behavior and distribution.
- Identify customer segments associated with higher attrition.
- Perform exploratory data analysis (EDA).
- Apply statistical techniques to understand data distributions and outliers.
- Use SQL to analyze customer demographics and transaction behavior.
- Build interactive Power BI dashboards for business stakeholders.
- Develop data-driven recommendations to improve customer retention.

## 📊 Dataset Information

| Attribute | Details |
|---|---|
| Dataset | BankChurners |
| Source | Kaggle |
| Total Records | 10,127 |
| Features | 23 |
| Target Variable | `Attrition_Flag` |
| Domain | Banking and Credit Cards |

## 🛠️ Tools and Technologies

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Manipulation | Pandas, NumPy |
| Database | MySQL |
| Data Analysis | SQL, Exploratory Data Analysis |
| Statistics | Descriptive Statistics, Outlier Detection |
| Visualization | Matplotlib, Seaborn |
| Business Intelligence | Microsoft Power BI |
| Reporting | Microsoft Excel |
| Development | VS Code |
| Version Control | Git, GitHub |

## 🔄 Project Workflow

```text
Raw Customer Dataset
        |
        v
Data Cleaning and Preparation
        |
        v
Exploratory Data Analysis (EDA)
        |
        v
Statistical Analysis
        |
        v
SQL-Based Business Analysis
        |
        v
Excel Reporting
        |
        v
Interactive Power BI Dashboards
        |
        v
Business Insights and Recommendations
```

## 🧹 Data Cleaning

**Tools:** Python, Pandas, NumPy

The raw dataset was prepared for analysis through the following steps:

- Checked for duplicate records.
- Identified and examined missing values.
- Validated column data types.
- Checked inconsistent or unexpected values.
- Prepared a cleaned dataset for downstream analysis.

## 📈 Exploratory Data Analysis (EDA)

**Tools:** Python, Pandas, Matplotlib, Seaborn

The exploratory analysis focused on understanding customer profiles, financial attributes, and transaction behavior.

### Areas of Analysis

- Customer age distribution.
- Gender and education-level distribution.
- Income-category analysis.
- Credit card category distribution.
- Credit limit distribution.
- Transaction count and transaction amount.
- Credit utilization ratio.
- Customer attrition distribution.
- Correlation analysis between numerical variables.

## 📐 Statistical Analysis

Descriptive and distribution-based statistical techniques were applied to understand customer attributes and identify potential anomalies.

### Statistical Measures

- Mean, median, and mode.
- Minimum and maximum values.
- Variance and standard deviation.
- Skewness and kurtosis.
- Interquartile range (IQR).
- Outlier detection.

**Objective:** Understand data distributions, variability, and unusual observations before drawing business conclusions.

## 💻 SQL Analysis

**Database:** MySQL

SQL was used to perform structured business analysis and extract customer-level insights.

### Analysis Areas

- Customer segmentation.
- Overall churn distribution.
- Churn analysis by card category.
- Income-category analysis.
- Transaction behavior analysis.
- Customer demographic analysis.
- Creation of reusable SQL views for reporting, where applicable.

## 📊 Power BI Dashboards

The project includes three interactive dashboards designed to present customer attrition patterns and business insights.

### 1. Executive Dashboard

![Executive Dashboard](Power%20BI/Dashboards/Executive%20Dashboard.png)

**Key Metrics and Visualizations**

- Total customers.
- Existing customers.
- Attrited customers.
- Overall churn rate.
- Customer churn distribution.
- Gender-wise churn analysis.
- Card-category analysis.
- Income-category analysis.

**Purpose:** Provide a high-level overview of customer retention and attrition performance.

### 2. Customer Insights Dashboard

![Customer Insights](Power%20BI/Dashboards/Customer%20Insights%20.png)

**Key Metrics and Visualizations**

- Customer age distribution.
- Education-level analysis.
- Credit limit by card category.
- Average transaction amount.
- Income-wise customer profile.

**Purpose:** Understand customer demographics, financial profiles, and card usage patterns.

### 3. Business Insights Dashboard

![Business Insights](Power%20BI/Dashboards/Business%20Insights.png)

**Key Metrics and Visualizations**

- Churn by marital status.
- Inactive months versus churn.
- Average transaction count by card category.
- Customer churn by credit utilization group.

**Purpose:** Identify customer engagement patterns and segments that may require targeted retention efforts.

## 🔍 Key Business Insights

1. **Overall churn rate:** The project reports a customer churn rate of **16.07%**.

2. **Customer demographics:** Married and single customers represent substantial customer segments and account for high numbers of attrited customers. Segment sizes should be considered when interpreting these counts.

3. **Customer inactivity:** Customers inactive for approximately 2–4 months show higher churn levels in the analyzed data.

4. **Card category:** Platinum cardholders have the highest average transaction count among the card categories analyzed.

5. **Credit utilization:** Customers in the 0–20% credit-utilization group account for the largest number of churned customers in the analysis.

6. **Customer engagement:** Lower transaction activity and customer inactivity are associated with attrition patterns and may help identify customers for further investigation.

## 💡 Business Recommendations

Based on the observed patterns, the following strategies could help improve customer retention.

### 1. Proactive Inactivity Monitoring

Identify customers who have not used their cards for two consecutive months and trigger targeted engagement campaigns.

### 2. Improve Cardholder Engagement

Design relevant rewards, cashback offers, and personalized campaigns to encourage regular card usage, particularly among customer segments with lower engagement.

### 3. Encourage Responsible Card Usage

Investigate low-utilization customer segments to understand their needs and offer relevant benefits, usage education, or suitable card features.

### 4. Develop Targeted Retention Strategies

Combine inactivity, transaction frequency, customer demographics, and other relevant indicators to prioritize retention outreach.

### 5. Measure Campaign Effectiveness

Track customer reactivation, retention rates, transaction frequency, and campaign costs to evaluate whether retention initiatives deliver measurable benefits.

---

## 📁 Project Structure

```text
Credit-Card-Customer-Churn-Analysis/
│
├── Data/
│   ├── Raw_Data/
│   │   └── BankChurners.csv
│   └── Cleaned_Data/
│       └── BankChurners_Cleaned.csv
│
├── documentation/
│
├── Excel/
│
├── MySQL/
│   ├── create db.sql
│   ├── important SQL Views.sql
│   ├── Load_CSV_To_MySQL.py
│   ├── SQL DATA ANALYSIS.sql
│   └── SQL_Data_Analysis.sql
│
├── Power BI/
│   ├── Credit Card Customer Churn Analysis (Banking).pbix
│   └── Dashboards/
│       ├── Executive Dashboard.png
│       ├── Customer Insights .png
│       └── Business Insights.png
│
├── Reports/
│   ├── EDA_Report.txt
│   └── Statistical_Analysis_Report.csv
│
├── Scripts/
│   ├── Data_Cleaning_Python_code/
│   │   └── BankChurners.py
│   └── Exploratory_Data_Analysis/
│       ├── EDA.PY
│       ├── EDA_Visualizations.py
│       └── Statistical_Analysis.py
│
├── Statistical_Analysis/
│   ├── Statistical_Analysis.docx
│   └── Statistical_Analysis_Report.csv
│
├── Visualizations/
│   └── Visualization/
│       ├── age_distribution.png
│       ├── boxplot_credit_limit.png
│       ├── card_category.png
│       ├── churn_by_gender.png
│       ├── churn_distribution.png
│       ├── correlation_heatmap.png
│       ├── credit_limit_distribution.png
│       ├── gender_distribution.png
│       ├── income_category.png
│       └── transaction_amount_distribution.png
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

*Note: This structure is based on the files listed in the project description. Ensure folder names and filenames match your actual GitHub repository.*

## 🚀 How to Run the Project

### Prerequisites

Install the following tools:

- Python 3.x
- MySQL Server
- MySQL Workbench or another MySQL client
- Microsoft Excel
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/singha-rohan07/credit-card-churn-analysis.git

cd credit-card-churn-analysis
```

### Step 2: Install Python Dependencies

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install the project dependencies:

```bash
pip install -r requirements.txt
```

### Step 3: Run the Python Scripts

Run the data-cleaning and analysis scripts using the paths and execution order defined in the repository.

For example:

```bash
python Scripts/Data_Cleaning_Python_code/BankChurners.py
```

```bash
python Scripts/Exploratory_Data_Analysis/EDA.PY
```

### Step 4: Run the SQL Analysis

1. Start MySQL Server.
2. Open the SQL scripts in MySQL Workbench.
3. Create the database and load the dataset.
4. Execute the analysis queries and SQL views.

Update database credentials and file paths as required by your environment.

### Step 5: Explore the Power BI Dashboards

Open the following file in Power BI Desktop:

`Power BI/Credit Card Customer Churn Analysis (Banking).pbix`

If prompted, configure the data source paths and refresh the data.

## 🚀 Future Enhancements

- **Machine Learning:** Build a churn prediction model using Logistic Regression, Random Forest, or XGBoost.
- **Explainable AI:** Use SHAP to explain the factors influencing model predictions.
- **Customer Segmentation:** Apply clustering techniques to identify distinct customer groups.
- **Automated ETL:** Develop a repeatable data extraction, transformation, and loading pipeline.
- **Automated Reporting:** Generate recurring churn reports and business summaries.
- **Predictive Analytics:** Estimate customer churn risk and prioritize retention efforts.

## 👨‍💻 Author

**Neeladri Singha**

Aspiring Data Analyst

### Technical Skills

- Python and Pandas
- SQL and MySQL
- Microsoft Excel
- Power BI and DAX
- Statistics and Exploratory Data Analysis
- Data Visualization
- Git and GitHub

---

**Project Goal:** Transform customer data into actionable insights that support data-driven customer retention strategies.

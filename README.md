# Customer Churn Analysis & Retention Insights

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes customer data to identify churn patterns, understand the factors associated with customer attrition, and generate actionable insights to improve customer retention.

The project follows an end-to-end data analytics workflow using **Python, Pandas, MySQL, and Power BI**.

---

## 🎯 Business Objective

The main objectives of this project are to:

* Calculate the overall customer churn rate.
* Identify customer segments with higher churn.
* Analyze the relationship between churn and customer demographics.
* Understand how contracts and services influence churn.
* Analyze monthly and total charges of churned customers.
* Identify potential high-risk customer segments.
* Provide data-driven recommendations for improving customer retention.

---

## 📊 Dataset

I used Telcom Customer Churn dataset, which is available at http://www.kaggle.com. The data was downloaded from IBM Sample Data Sets https://www.ibm.com/communities/analytics/watsonanalytics- blog/guide-to-sample-datasets/. The dataset provides 7043 customers information in 33 columns. We have both numerical and categorical type of information in this dataset

### Dataset Information

* **Records:** 7,043 customers
* **Columns:** 33
* **Target Variable:** `Churn Label`

### Major Data Categories

**Customer Information**

* Customer ID
* Gender
* Age
* Senior Citizen
* Partner
* Dependents

**Service Information**

* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming Services

**Account Information**

* Tenure
* Contract
* Payment Method
* Paperless Billing

**Financial Information**

* Monthly Charges
* Total Charges

**Churn Information**

* Churn Label
* Churn Value
* Churn Score
* Churn Reason
* Customer Status

---

## 🛠️ Tools & Technologies

* **Python** – Data cleaning and exploratory data analysis
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **MySQL** – SQL-based data analysis
* **Power BI** – Interactive dashboard and visualization
* **Excel** – Dataset inspection and validation
* **GitHub** – Project documentation and version control

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning using Python/Pandas
     ↓
Exploratory Data Analysis
     ↓
SQL Analysis using MySQL
     ↓
Data Visualization using Power BI
     ↓
Business Insights
     ↓
Retention Recommendations
```

---

## 🧹 Data Cleaning

The dataset was inspected and prepared before analysis.

### Cleaning activities included:

* Checked dataset dimensions and data types.
* Identified missing values.
* Checked for duplicate records.
* Standardized column names and categorical values.
* Validated customer and churn-related fields.
* Verified the cleaned dataset before loading it into MySQL and Power BI.

---

## 🐍 Python & Pandas Analysis

Python/Pandas was used for:

* Data inspection
* Data cleaning
* Missing-value analysis
* Duplicate detection
* Descriptive statistics
* Exploratory data analysis
* Churn distribution analysis

---

## 🗄️ SQL Analysis

MySQL was used to perform business-oriented analysis.

### Key SQL analyses included:

* Total customer count
* Active customer count
* Churned customer count
* Overall churn rate
* Churn rate by contract
* Churn rate by payment method
* Churn rate by internet service
* Churn rate by tenure group
* Average monthly charges
* Revenue associated with churned customers
* Identification of high-churn customer segments

SQL concepts used:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `CASE`
* Aggregate functions
* Window functions

---

## 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to provide a business-focused view of customer churn.

### Dashboard KPIs

* Total Customers
* Active Customers
* Churned Customers
* Churn Rate

### Dashboard Analysis

The dashboard provides analysis of:

* Customer churn trends
* Churn by contract type
* Churn by tenure
* Churn by payment method
* Churn by internet service
* Churn by customer demographics
* Churn by service usage

### Interactive Features

* Slicers
* Filters
* KPI cards
* Drill-down analysis
* Interactive charts
* Cross-filtering

---

## 💡 Key Business Insights

The analysis was used to identify the customer segments and factors associated with higher churn.

Examples of insights investigated include:

* Contract type and its relationship with customer churn.
* Higher churn among customers with shorter tenure.
* Differences in churn across payment methods.
* Relationship between monthly charges and churn.
* Impact of service adoption on customer retention.
* Customer segments requiring targeted retention strategies.

> **Note:** Final insight statements should be updated with the actual findings and percentages obtained from the analysis.

---

## 🎯 Business Recommendations

Based on the analysis, potential retention strategies include:

1. **Target high-risk customer segments** with personalized retention campaigns.

2. **Encourage longer-term contracts** by offering suitable incentives to customers on short-term contracts.

3. **Focus on early-tenure customers** because new customers may require stronger onboarding and engagement.

4. **Review pricing and service value** for customers with high monthly charges.

5. **Promote relevant support and service features** where analysis shows an association with better retention.

6. **Monitor churn KPIs regularly** through an interactive Power BI dashboard.

---

## 📁 Project Structure

```text
Customer-Churn-Analysis/
│
├── data/
│   └── Telco_customer_churn.xlsx
│
├── python/
│   └── customer_churn_analysis.ipynb
│
├── sql/
│   └── customer_churn_analysis.sql
│
├── powerbi/
│   └── customer_churn_dashboard.pbix
│
├── dashboard/
│   └── customer_churn_dashboard.png
│
├── presentation/
│   └── customer_churn_presentation.pdf
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Install Python libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

### 3. Run the Python notebook

Open:

```text
python/customer_churn_analysis.ipynb
```

Run the notebook to perform data cleaning and exploratory analysis.

### 4. Run SQL analysis

Open the SQL file:

```text
sql/customer_churn_analysis.sql
```

Run the queries in MySQL Workbench.

### 5. Open the Power BI dashboard

Open:

```text
powerbi/customer_churn_dashboard.pbix
```

Refresh the data source if required.

---

## 📌 Project Outcome

This project demonstrates an end-to-end Data Analytics workflow, from raw customer data preparation to SQL analysis, interactive dashboard development, business insights, and retention recommendations.

### Skills Demonstrated

**Data Cleaning | Exploratory Data Analysis | Python | Pandas | SQL | MySQL | Power BI | Data Visualization | KPI Analysis | Customer Segmentation | Business Intelligence | Business Insights**

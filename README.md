# TITANIC EDA ANALYSIS
## Task 1: Data Collection & Data Source Identification
**Edutech Solution — Data Analytics Internship**

---
## Objective

- The objective of this task is to identify reliable data sources, collect a dataset, and validate it for analysis.
---

## Tools
- **Kaggle** — Platform used to find and download the public dataset
- **Python (Pandas)** — Used to load and inspect the raw CSV data
- **CSV / SQL** — Common formats for storing and querying structured data
- **APIs** — Platforms like Kaggle provide API access to download datasets

---

## Dataset
- **Name:** Titanic - Machine Learning from Disaster
- **Source:** Kaggle — [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/datasets/pranjalyadav92905/titanic-eda-data/data)
- **Type:** Public Dataset
- **Format:** CSV
- **Size:** 891 rows × 12 columns
  
Titanic EDA analysis dataset
This project focuses on data collection and data source identification using a public dataset. The dataset used is the Titanic dataset from Kaggle, which contains information about passengers such as age, gender, class, and survival status.

The goal of this task is to demonstrate the ability to identify reliable data sources, understand data types, and collect raw data for analysis.

---

## Hints

### Identify Relevant Data Sources
The Titanic dataset was selected from Kaggle, a public platform hosting thousands of free datasets. It was chosen because:
- It is free and openly available for educational use
- It is well-structured (tabular CSV format)
- It is well-documented with a clear data dictionary
- It contains a realistic mix of numerical and categorical data

### Understand Primary vs Secondary Data
| | Primary Data | Secondary Data |
|---|---|---|
| **Definition** | Data you collect yourself | Data collected by someone else |
| **Examples** | Surveys, interviews, experiments | Kaggle datasets, UCI repository, government data |
| **Cost** | Time-consuming and expensive | Usually free and readily available |


> The Titanic dataset is **secondary data** — compiled from historical ship records and published on Kaggle for public use.

---

## Deliverables

### 1. Data Source Report

| Field | Details |
|---|---|
| **Dataset Name** | Titanic Dataset |
| **Source Platform** | Kaggle |
| **URL** | https://www.kaggle.com/c/titanic/data |
| **Data Type** | Secondary Data |
| **File Format** | CSV |
| **Rows** | 891 |
| **Columns** | 12 |
| **License** | Free for educational use |

**Data Dictionary:**

| Column | Description | Type |
|---|---|---|
| `PassengerId` | Unique ID per passenger | Integer |
| `Survived` | Survival — 0 = No, 1 = Yes | Integer |
| `Pclass` | Ticket class — 1st, 2nd, 3rd | Integer |
| `Name` | Passenger full name | String |
| `Sex` | Gender | String |
| `Age` | Age in years | Float |
| `SibSp` | No. of siblings/spouses aboard | Integer |
| `Parch` | No. of parents/children aboard | Integer |
| `Ticket` | Ticket number | String |
| `Fare` | Ticket fare paid | Float |
| `Cabin` | Cabin number | String |
| `Embarked` | Port of embarkation (C, Q, S) | String |

---

### 2. Sample Raw Data

First 10 rows of `titanic.csv`:

| PassengerId | Survived | Pclass | Name | Sex | Age | SibSp | Parch | Ticket | Fare | Cabin | Embarked |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 0 | 3 | Braund, Mr. Owen Harris | male | 22 | 1 | 0 | A/5 21171 | 7.25 | | S |
| 2 | 1 | 1 | Cumings, Mrs. John Bradley | female | 38 | 1 | 0 | PC 17599 | 71.28 | C85 | C |
| 3 | 1 | 3 | Heikkinen, Miss. Laina | female | 26 | 0 | 0 | STON/O2. 3101282 | 7.93 | | S |
| 4 | 1 | 1 | Futrelle, Mrs. Jacques Heath | female | 35 | 1 | 0 | 113803 | 53.10 | C123 | S |
| 5 | 0 | 3 | Allen, Mr. William Henry | male | 35 | 0 | 0 | 373450 | 8.05 | | S |
| 6 | 0 | 3 | Moran, Mr. James | male | — | 0 | 0 | 330877 | 8.46 | | Q |
| 7 | 0 | 1 | McCarthy, Mr. Timothy J | male | 54 | 0 | 0 | 17463 | 51.86 | E46 | S |
| 8 | 0 | 3 | Palsson, Master. Gosta Leonard | male | 2 | 3 | 1 | 349909 | 21.08 | | S |
| 9 | 1 | 3 | Johnson, Mrs. Oscar W | female | 27 | 0 | 2 | 347742 | 11.13 | | S |
| 10 | 1 | 2 | Nasser, Mrs. Nicholas | female | 14 | 1 | 0 | 237736 | 30.07 | | C |


---

## Final Outcome
Through this task, I was able to:
- Find and validate a reliable public dataset from Kaggle
- Distinguish between primary and secondary data
- Understand the structure and contents of the raw dataset before any analysis

---

## Interview Questions

**Q: What is the difference between Primary and Secondary data?**
> Primary data is data you collect yourself through surveys, experiments, or observations. Secondary data is data that has already been collected by someone else and is being reused — like the Titanic dataset from Kaggle.

**Q: What are common data formats?**
> - **CSV** — Comma-Separated Values, simple tabular data (used here)
> - **JSON** — Key-value format, common in APIs
> - **SQL** — Data stored in relational database tables
> - **Excel (.xlsx)** — Spreadsheet format used in business
> - **XML** — Hierarchical format used in legacy systems


---

## Task 2: Data Cleaning and Preprocessing

---

## Deliverables

### Clean Dataset
**File:** `titanic.csv`

**Contains:**
- No missing values  
- No duplicates  
- Normalized numerical features  
- Outliers removed  

---

### Preprocessing Code
- Implemented using Python (Pandas, NumPy, Scikit-learn)  
- Covers:
  - Handling missing values  
  - Removing duplicates  
  - Feature normalization  
  - Outlier detection and removal  

---

## Final Outcome

Through this task, I gained understanding of:
- Data cleaning techniques  
- Handling missing values  
- Feature scaling  
- Outlier detection  

The dataset is now clean and ready for:
- Data analysis  
 

---

## Interview Questions & Answers

### Q1: What is data cleaning?
Data cleaning is the process of fixing or removing incorrect, missing, or inconsistent data to improve data quality before analysis.



### Q2: How to handle missing values?
- Fill with mean/median (numerical data)  
- Fill with mode (categorical data)  
- Drop rows or columns if necessary  



### Q3: What are outliers?
Outliers are extreme values that are very different from other data points and can affect analysis results.

---


**Author:** Marianne Ongondi | Data Analytics Intern — Edutech Solution

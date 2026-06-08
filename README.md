# Data-Science-Internship-Task1

# Titanic Dataset Analysis: Understanding Dataset & Data Types

## Project Overview

This project focuses on understanding the structure, characteristics, and quality of a real-world dataset using Python and Pandas. The analysis was performed on the Titanic dataset, a widely used dataset in data science and machine learning for exploratory data analysis (EDA) and predictive modeling.

The primary objective of this task is to gain hands-on experience in dataset exploration, data type identification, missing value analysis, and statistical summarization.

---

## Dataset Information

**Dataset:** Titanic Dataset (`train.csv`)

**Source:** Kaggle Titanic - Machine Learning from Disaster

**Total Records:** 891 Passengers

**Total Features:** 12 Columns

Each record represents a passenger aboard the RMS Titanic and contains demographic, ticketing, and survival-related information.

---

## Technologies Used

* Python 3
* Pandas
* Google Colab
* GitHub

---

## Project Workflow

### 1. Data Loading

The dataset was imported using Pandas and loaded into a DataFrame for further analysis.

Tasks Performed:

* Imported Pandas library
* Loaded CSV dataset
* Verified successful data loading

---

### 2. Dataset Exploration

Initial exploration was conducted to understand the overall structure of the dataset.

Methods Used:

* `head()`
* `shape`
* `info()`

Key Findings:

* Dataset contains 891 rows and 12 columns.
* Dataset includes both numerical and categorical features.
* Several columns contain missing values.

---

### 3. Data Type Analysis

Columns were classified into numerical and categorical categories.

#### Numerical Features

* PassengerId
* Survived
* Pclass
* Age
* SibSp
* Parch
* Fare

#### Categorical Features

* Name
* Sex
* Ticket
* Cabin
* Embarked

---

### 4. Statistical Analysis

Descriptive statistics were generated using Pandas.

Metrics Analyzed:

* Count
* Mean
* Standard Deviation
* Minimum Value
* Maximum Value
* Quartiles

Key Insights:

* Average passenger age is approximately 29.7 years.
* Average ticket fare is approximately 32.20.
* Survival rate is approximately 38%.

---

### 5. Missing Value Assessment

A missing value audit was performed to identify data quality issues.

| Column   | Missing Values |
| -------- | -------------- |
| Age      | 177            |
| Cabin    | 687            |
| Embarked | 2              |

Observations:

* Cabin contains a significant number of missing values.
* Age contains moderate missing data.
* Embarked contains minimal missing values.

---

### 6. Categorical Feature Exploration

Unique values were extracted from categorical columns to understand category distribution.

Examples:

* Sex → Male, Female
* Embarked → Southampton (S), Cherbourg (C), Queenstown (Q)
* Cabin → Multiple cabin categories with missing values

---

## Business Understanding

Although this dataset is commonly used for machine learning, understanding the dataset structure is the first and most critical phase of any data science project.

This analysis helps:

* Understand feature characteristics
* Identify data quality issues
* Prepare data for cleaning and preprocessing
* Build a strong foundation for future predictive modeling

---

## Key Findings

* Dataset consists of 891 passenger records and 12 attributes.
* Both numerical and categorical data types are present.
* Cabin has the highest percentage of missing values.
* Passenger age ranges from approximately 0.42 to 80 years.
* Approximately 38% of passengers survived.
* The dataset is suitable for further exploratory analysis and machine learning applications.

---

## Conclusion

This project successfully demonstrates the initial stages of Exploratory Data Analysis (EDA), including dataset understanding, data type identification, missing value assessment, and statistical summarization.

The analysis provides valuable insights into the dataset's structure and quality, creating a strong foundation for future data preprocessing, visualization, and machine learning tasks.

---

## Repository Structure

```text
Task1-Understanding-Dataset/
│
├── Task1_Understanding_Dataset.ipynb
├── train.csv
├── README.md
```

---

## Author

Ankit Yadav
Data science Intern - EDutech

# 📊 Loan Approval Data Analysis & Visualization

## Project Overview
This project focuses on **data preprocessing, cleaning, exploratory data analysis, and visualization** using the **Loan Approval Dataset**. The main goal is to analyze applicant data and identify key factors that influence loan approval decisions by applying Python-based data analysis techniques.

The project demonstrates practical usage of **NumPy**, **Pandas**, and **Matplotlib** to work with a real-world financial dataset. It is designed for beginners and students who want hands-on experience in data analysis and visualization.

---

## Dataset
- **Dataset Name:** Loan Approval Dataset  
- **Source:** Kaggle  
- **File Used:** `loanapproval.csv`

The dataset contains both numerical and categorical attributes such as age, income, credit score, employment status, dependents, existing loans, and loan approval status.

---

## Tools & Libraries Used
- **Python**
- **NumPy** – Numerical operations  
- **Pandas** – Data manipulation and preprocessing  
- **Matplotlib** – Data visualization  

---

## Data Inspection
Initial exploration was carried out using:
- `head()` and `tail()` to view sample records  
- `info()`, `shape`, and `dtypes` to understand structure and data types  
- `loc` and `iloc` for label-based and index-based data selection  
- `value_counts()` to analyze categorical variable distributions  

---

## Data Cleaning
To improve data quality, the following steps were applied:
- Identification of missing values using `isnull()` and `notnull()`  
- Handling missing data with `dropna()` and `interpolate()`  
- Detection and removal of duplicate records using `duplicated()` and `drop_duplicates()`  
- Summary statistics calculated using `mean()`, `median()`, and `std()`  

---

## Data Visualization
Different visualization techniques were used to uncover insights:
- **Line Graphs:** Trends in age, income, loan amount, credit score, dependents, and loan approval  
- **Multiple Line Graphs:** Comparisons such as age vs credit score and loan amount vs credit score  
- **Bar Charts:** Gender, marital status, employment status, and loan approval distribution  
- **Histograms:** Distribution of age, income, loan amount, and credit score  
- **Pie Charts:** Proportions of loan approval and employment status  
- **Scatter Plot:** Relationship between credit score and loan amount  

---

## Key Insights
- Credit score plays a major role in loan approval decisions  
- Employment status and existing loans significantly affect approval outcomes  
- Income alone is not a strong indicator of loan approval  
- Applicants with fewer dependents and higher credit scores have higher approval chances  

---

## Conclusion
This project demonstrates how Python libraries can be effectively used to clean, explore, analyze, and visualize real-world datasets. The insights gained help in understanding the factors affecting loan approval decisions and provide a strong foundation for further machine learning or predictive modeling tasks.

---

## Author
**Bushra Shaukat**  


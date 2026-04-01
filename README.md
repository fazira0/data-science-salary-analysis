# Data Science Salary Analysis

## Overview
This project focuses on cleaning, transforming, and analyzing a global data science salary dataset. The goal is to ensure data quality and extract meaningful insights regarding salary distribution across experience levels and locations.

---

## Objectives
- Prepare raw salary data for analysis through cleaning and validation  
- Standardize categorical variables for better interpretability  
- Perform exploratory data analysis (EDA)  
- Answer key analytical questions related to salary trends  

---

## Dataset
The dataset contains information on:
- Job titles  
- Experience levels  
- Employment types  
- Salaries (USD)  
- Company locations  
- Remote work ratios  

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  

---

## Process

### 1. Data Exploration
- Reviewed dataset structure and data types  
- Analyzed unique values in categorical columns  
- Interpreted encoded labels (experience level, employment type, remote ratio)  

---

### 2. Data Cleaning
- Checked and handled missing values  
- Identified and removed duplicate records  

---

### 3. Data Transformation
- Converted encoded categorical variables into readable labels  
- Created descriptive columns for better clarity:
  - `experience_level_desc`  
  - `employment_type_desc`  
  - `remote_ratio_desc`  

---

### 4. Feature Engineering
- Simplified job titles into broader categories  
- Created an `adjusted_salary` column to account for inflation  

---

### 5. Analysis

#### Salary by Experience Level
- Calculated median adjusted salary for Data Scientist roles across experience levels  

#### Company Location Distribution
- Analyzed the distribution of companies by location  

#### Case Analysis: Indonesia
- Median adjusted salary: **37,045.804 USD**  
- Sample size: **2 records**  

**Note:**  
This result is not representative due to the very small sample size.

---

## Key Takeaways
- Data cleaning is essential before performing analysis  
- Standardizing categorical variables improves interpretability  
- Feature engineering enables better comparison across data points  
- Small sample sizes can lead to misleading conclusions  
- Context is critical when interpreting results  


---

## Conclusion
This project highlights the importance of structured data preparation and critical analysis. By transforming raw data into a clean and usable format, more reliable insights can be generated while avoiding misinterpretation.

---

## Future Improvements
- Incorporate data visualization for better insight communication  
- Expand dataset to improve representativeness  
- Perform deeper analysis on salary drivers  

---
## Lisence
This project is created for educational purposes.

# Healthcare Patient Data Analysis (Level 2 Project 1)

##  Project Overview
This project is a Python-based Healthcare Data Analysis system designed to analyze patient records, identify common medical conditions, and discover demographic risk patterns using Exploratory Data Analysis (EDA).

The goal is to understand how age, gender, and medical conditions are related and to identify high-risk patient groups.

---

##  Objective
- Clean and validate healthcare patient data
- Handle missing values and duplicates
- Standardize data formats
- Perform exploratory data analysis (EDA)
- Identify disease patterns across demographics
- Visualize insights using graphs

---

##  Dataset Information
- Source: Kaggle Healthcare Dataset  
- Link: https://www.kaggle.com/datasets/prasad22/healthcare-dataset  
- Format: CSV  

### Key Columns Used:
- age
- gender
- medical_condition
- date_of_admission
- discharge_date
- hospital
- insurance_provider
- billing_amount

---

##  Technologies Used
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

##  Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Checked structure using `.info()` and `.describe()`

### 2. Data Cleaning
- Removed duplicate records
- Handled missing values
- Standardized gender values
- Converted age into numeric format
- Cleaned medical condition names

### 3. Feature Engineering
- Created age groups:
  - 0–18
  - 19–35
  - 36–60
  - 60+

### 4. Exploratory Data Analysis
- Most common medical conditions
- Disease distribution by gender
- Disease distribution by age group

### 5. High-Risk Group Analysis
- Identified age group with highest disease occurrence
- Analyzed gender-based risk patterns

### 6. Data Visualization
- Bar charts for disease frequency
- Count plots for demographic comparison
- Histogram for age distribution

---

##  Key Insights
- Certain age groups show higher prevalence of medical conditions
- Gender differences exist in specific disease patterns
- Older age groups are generally at higher risk
- Some medical conditions are significantly more common than others

---


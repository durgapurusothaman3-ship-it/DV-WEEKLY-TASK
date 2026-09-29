# Healthcare Data Understanding, Cleaning & Exploratory Analysis

##  Project Description

This project focuses on analyzing a healthcare dataset to understand patient demographics, medical conditions, admission types, billing amounts, and hospital stay duration.

The dataset is cleaned, transformed, and analyzed using Python to identify meaningful patterns and generate useful healthcare insights.

---

##  Objectives

- Understand the structure of the healthcare dataset.
- Check and handle missing values.
- Clean and standardize categorical data.
- Convert date attributes into proper date formats.
- Analyze patient demographics based on medical conditions.
- Categorize admissions into Emergency, Elective, and Urgent.
- Calculate hospital stay duration.
- Generate summary statistics for billing amounts.
- Analyze hospital stay patterns using visualizations.

---

##  Dataset Information

**Dataset:** `healthcare_dataset.csv`

The dataset contains **55,500 patient records** and includes information such as:

- Patient Name
- Age
- Gender
- Blood Type
- Medical Condition
- Date of Admission
- Discharge Date
- Admission Type
- Doctor
- Hospital
- Insurance Provider
- Billing Amount
- Medication
- Test Results

---

##  Data Cleaning & Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset using Pandas.
2. Checked the number of rows and columns.
3. Checked for missing values.
4. Standardized categorical attributes.
5. Converted admission and discharge dates into datetime format.
6. Calculated hospital stay duration from admission and discharge dates.
7. Prepared the cleaned data for exploratory analysis.

---

##  Exploratory Data Analysis

### 1. Patient Demographics

Patient demographics were analyzed based on different medical conditions such as:

- Arthritis
- Asthma
- Cancer
- Diabetes
- Hypertension
- Obesity

A comparison of patient counts by gender and medical condition was performed.

### 2. Admission Analysis

Admissions were categorized into:

- Emergency
- Elective
- Urgent

The number of patients under each admission type was analyzed using visualizations.

### 3. Billing Analysis

Statistical analysis was performed on patient billing amounts using:

- Mean
- Median
- Minimum
- Maximum
- Standard Deviation
- Quartiles

### 4. Hospital Stay Analysis

Hospital stay duration was calculated using:

**Stay Days = Discharge Date − Date of Admission**

The distribution of hospital stay duration was analyzed using statistical measures and charts.

---

## Visualizations

The project includes visualizations such as:

- Gender distribution by medical condition
- Patient admission type distribution
- Billing amount distribution
- Hospital stay duration distribution
- KDE and histogram plots

---

##  Key Findings

- The dataset contains **55,500 patient records**.
- Six major medical conditions are represented in the dataset.
- Admissions are categorized into Emergency, Elective, and Urgent.
- The average billing amount is approximately **25,539**.
- The average hospital stay is approximately **15.5 days**.
- Data cleaning and visualization helped identify patterns in patient and healthcare information.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

---

##  Project Structure

```text
Healthcare-Data-Analysis/
│
├── healthcare_dataset.csv
├── Week_5.ipynb
├── week_5.py
└── README.md

**## Conclusion**
This project demonstrates the process of healthcare data understanding, data cleaning, statistical analysis, and exploratory data visualization.
The analysis provides insights into patient demographics, medical conditions, admission patterns, billing amounts, and hospital stay duration. These findings can help in better understanding healthcare data and supporting data-driven healthcare analysis.

Week 5 – Healthcare Data Understanding, Cleaning & Exploratory Analysis
 Project Overview
This project focuses on understanding, cleaning, and performing exploratory data analysis on a healthcare dataset containing patient information, medical conditions, admission details, billing amounts, and hospital stay duration.
The analysis helps identify patterns in patient demographics, admission types, healthcare costs, and length of hospital stays.
 Objectives
- Understand the structure and characteristics of the healthcare dataset.
- Identify and handle missing values.
- Clean and standardize categorical and date attributes.
- Analyze patient demographics based on medical conditions.
- Categorize patient admissions into Emergency, Elective, and Urgent.
- Calculate hospital stay duration from admission and discharge dates.
- Generate summary statistics for patient billing amounts.
- Analyze hospital stay duration using statistical measures and visualizations.
- Identify useful patterns and insights from the healthcare data.
Dataset
Dataset Name: healthcare_dataset.csv
The dataset contains 55,500 patient records with information such as:
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
 Technologies Used
- Python
- Pandas – Data cleaning and analysis
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Jupyter Notebook / Google Colab
 Data Cleaning
The following preprocessing steps were performed:
1. Loaded the healthcare dataset using Pandas.
2. Checked the dataset structure and data types.
3. Checked for missing values.
4. Standardized categorical values by removing unnecessary spaces and formatting inconsistencies.
5. Converted admission and discharge dates into proper datetime format.
6. Calculated hospital stay duration using admission and discharge dates.
 Exploratory Data Analysis
1. Medical Condition Analysis
Patient demographics were analyzed across different medical conditions such as:
- Arthritis
- Asthma
- Cancer
- Diabetes
- Hypertension
- Obesity
2. Admission Type Analysis
Patient admissions were categorized into:
- Emergency
- Elective
- Urgent
The number of patients in each category was analyzed and visualized.
3. Billing Analysis
Statistical measures were calculated for patient billing amounts, including:
- Mean
- Median
- Standard Deviation
- Minimum
- Maximum
- Quartiles
4. Hospital Stay Analysis
Hospital stay duration was calculated and analyzed using:
- Mean stay duration
- Median stay duration
- Minimum stay
- Maximum stay
- Standard deviation
Visualizations were also created to understand the distribution of hospital stays.
 Key Insights
- The dataset contains 55,500 patient records.
- Multiple medical conditions are represented, including Diabetes, Cancer, Asthma, Arthritis, Hypertension, and Obesity.
- Patient admissions are distributed across Emergency, Elective, and Urgent categories.
- The average billing amount is approximately 25,539.
- The average hospital stay is approximately 15.5 days.
- Data visualization provides a better understanding of patient demographics, healthcare costs, and hospital stay patterns.
 Conclusion
This project demonstrates the complete process of healthcare data understanding, cleaning, and exploratory analysis using Python. The analysis provides useful insights into patient demographics, medical conditions, admission patterns, billing amounts, and hospital stay duration. These insights can support better understanding of healthcare data and help identify patterns that may be useful for healthcare management and decision-making.

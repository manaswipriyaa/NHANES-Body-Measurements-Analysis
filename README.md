# NHANES-Body-Measurements-Analysis

==================================
NHANES Body Measurements Analysis 
==================================

Project Overview
----------------
This project is part of my Corizo Data Science Minor Project. 
It focuses on analysing NHANES (National Health and Nutrition Examination Survey) 
adult body measurement data using Python libraries such as NumPy, Matplotlib, 
Pandas, Seaborn, and SciPy.

The objective is to explore and compare male and female body measurements, 
compute health-related indicators like BMI, Waist-to-Height Ratio (WHtR), 
and Waist-to-Hip Ratio (WHR), and visualise statistical patterns.

---------------------------------------------------------
Project Objectives
---------------------------------------------------------
1. Import and clean NHANES male and female datasets.
2. Visualise weight distributions using histograms.
3. Compare male and female weights using boxplots.
4. Compute statistical aggregates (mean, variance, skewness, kurtosis).
5. Add Body Mass Index (BMI) as a new feature.
6. Standardise the female dataset using z-scores.
7. Perform correlation analysis (Pearson & Spearman) with scatterplot matrices.
8. Compute Waist-to-Height Ratio (WHtR) and Waist-to-Hip Ratio (WHR).
9. Compare BMI, WHtR, and WHR as health indicators.

---------------------------------------------------------
Project Structure
---------------------------------------------------------
Mini-Project/
│
├── data/                      (optional) raw CSV files
│   ├── nhanes_adult_male_bmx_2020.csv
│   ├── nhanes_adult_female_bmx_2020.csv
│
├── notebooks/
│   └── Minor_Project.ipynb   (main Jupyter Notebook)
│
├── README.txt                 (project description)
└── requirements.txt           (Python libraries required)

---------------------------------------------------------
Libraries Used
---------------------------------------------------------
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- jupyter

---------------------------------------------------------
How to Run
---------------------------------------------------------
1. Clone this repository
   git clone https://github.com/<your-username>/nhanes-body-measurements-analysis.git

2. Navigate into the folder
   cd nhanes-body-measurements-analysis

3. Install the required libraries
   pip install -r requirements.txt

4. Open the Jupyter Notebook
   jupyter notebook notebooks/Corizo_Mini_Project.ipynb

---------------------------------------------------------
Example Outputs
---------------------------------------------------------
- Histograms & boxplots comparing male vs. female weights
- Scatterplot matrix showing correlations between body measurements
- Boxplots comparing BMI, WHtR, and WHR

---------------------------------------------------------
Learning Outcomes
---------------------------------------------------------
- Hands-on experience with NumPy for matrix operations
- Data visualisation using Matplotlib and Seaborn
- Application of descriptive statistics (mean, std, skewness, kurtosis)
- Use of health indicators: BMI, Waist-to-Height Ratio, Waist-to-Hip Ratio
- Writing a structured and professional data analysis report

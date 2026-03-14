# NHANES Body Measurements Analysis

An exploratory data analysis project on the NHANES (National Health and Nutrition Examination Survey) dataset - examining relationships between body measurements, health indicators, and demographic factors across a large population sample.

---

## About the Dataset

**Source:** NHANES - National Health and Nutrition Examination Survey (CDC)
**Type:** Public health survey data collected by the US Centers for Disease Control and Prevention
**Size:** Thousands of respondents across multiple survey cycles
**Features:** Body measurements (height, weight, BMI, waist circumference), blood pressure, age, gender, ethnicity, activity levels

---

## Objectives

- Explore distributions of key body measurements across demographic groups
- Identify correlations between BMI, blood pressure, and lifestyle factors
- Visualise health trends across age groups and gender
- Detect outliers and anomalies in measurement data

---

## Analysis Performed

### 1. Data Cleaning
- Handled missing values using median/mode imputation
- Removed physiologically implausible values (outlier filtering)
- Standardised column names and data types

### 2. Exploratory Data Analysis
- Distribution plots for BMI, height, weight, waist circumference
- Age-wise and gender-wise breakdown of body measurements
- Correlation heatmap between all numerical health indicators
- Box plots comparing measurements across demographic subgroups

### 3. Health Insights
- Identified age groups with highest average BMI
- Analysed relationship between waist circumference and blood pressure
- Compared body measurement trends between male and female respondents

---

## Key Findings

- BMI shows a strong positive correlation with waist circumference (r > 0.85)
- Blood pressure increases steadily with age across all demographic groups
- Significant variation in average body measurements across ethnicity groups

---

## Tech Stack

| Category | Tools |
|---|---|
| Language | Python 3.x |
| Data | Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Notebook | Jupyter Notebook |

---

## Project Structure

```
NHANES-Body-Measurements-Analysis/
│
├── data/
│   └── nhanes_data.csv
├── notebooks/
│   └── nhanes_analysis.ipynb
├── outputs/
│   ├── bmi_distribution.png
│   ├── correlation_heatmap.png
│   └── age_vs_bp.png
└── README.md
```

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/manaswipriyaa/NHANES-Body-Measurements-Analysis.git
cd NHANES-Body-Measurements-Analysis

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook notebooks/nhanes_analysis.ipynb
```

---

## Author

**Manaswi Priya Maddu**
B.Tech - AI & Machine Learning | Acharya Nagarjuna University
[LinkedIn](https://linkedin.com/in/manaswi-priya-2126481b8) | [GitHub](https://github.com/manaswipriyaa)

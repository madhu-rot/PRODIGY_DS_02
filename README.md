# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

**Prodigy InfoTech – Data Science Internship | Task 02**

## 📌 Project Overview

This project focuses on data cleaning and Exploratory Data Analysis (EDA) using the Titanic passenger dataset.

The objective is to explore the dataset, identify patterns, handle missing values, understand passenger demographics, and analyze the factors that influenced passenger survival.

Python libraries were used for data preprocessing, statistical analysis, and visualization. A Power BI dashboard was also created to present the findings in an interactive and visually appealing format.

## 🎯 Objectives

- Understand and explore the Titanic dataset.
- Identify missing values and duplicate records.
- Clean and preprocess the dataset.
- Perform exploratory data analysis.
- Analyze survival patterns based on passenger characteristics.
- Create meaningful visualizations.
- Develop a Power BI dashboard to present the analysis.

## 📂 Dataset

The project uses the Titanic dataset provided for the Prodigy InfoTech task.

The original dataset ZIP contains:

- `train.csv` – Passenger information with survival labels.
- `test.csv` – Passenger information without survival labels.
- `gender_submission.csv` – Sample survival predictions.

**Dataset Used:** `train.csv`

The training dataset contains 891 passenger records and 12 original columns. It was selected because it includes the `Survived` column required for survival analysis.

## 🧹 Data Cleaning & Preprocessing

The following data-cleaning operations were covered:

- Inspected the dataset using `head()`, `shape`, `columns`, `info()`, and `describe()`.
- Checked for missing values in each column.
- Identified and checked duplicate records.
- Removed duplicate records where present.
- Filled missing values in the `Age` column using the median.
- Filled missing values in the `Embarked` column using the mode.
- Dropped the `Cabin` column because it contained a large number of missing values.
- Verified the dataset after cleaning.

## 🔍 Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand passenger demographics and survival patterns.

### Analysis Performed

- Passenger survival distribution.
- Survival comparison between male and female passengers.
- Survival analysis based on passenger class.
- Age distribution of passengers.
- Fare distribution and comparison.
- Survival patterns across embarkation ports.
- Statistical summaries and correlation analysis.

### Feature Engineering

Additional features were explored to improve the analysis:

- **FamilySize:** Calculated using the number of siblings/spouses and parents/children aboard, plus the passenger.
- **IsAlone:** Identified passengers travelling alone.
- **AgeGroup:** Categorized passengers into different age groups.
- **Title:** Extracted passenger titles from their names.

## 📊 Data Visualization

The Titanic Survival Analysis dashboard consists of two interactive pages:

Page 1: Titanic Survival Overview

KPI Cards – Total Passengers, Total Survivors, Overall Survival Rate, and Average Age.

Survival Analysis by Gender.

Survival Analysis by Passenger Class.

Passenger Distribution by Age Group.

Passenger Distribution by Embarkation Port.

Passenger Distribution by Gender.

Overall Survival Distribution.

Page 2: Beyond the Numbers

Survival Across Fare Categories – Treemap.

Family Size vs Survival – Ribbon Chart.

Survival Rate by Passenger Class – Gauge Chart.

Key Features

Interactive dashboard layout.

KPI-based performance indicators.

Multiple chart types for exploring passenger data.

Dark-themed dashboard with gold and red accents.

Comparative analysis of survival patterns across passenger demographics.
## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to present the Titanic analysis in a clear and visual format.

The dashboard brings together passenger information and survival patterns through visual reports and key metrics.

**Dashboard Preview:**



## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI


## 👩‍💻 Author

**Madhusmita Nayak**

BCA Student | Aspiring Data Analyst

**Internship:** Prodigy InfoTech – Data Science Internship

# PRODIGY_DS_02

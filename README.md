# eda-data-cleaning
#Exploratory Data Analysis and Data Cleaning on Titanic Dataset
# Exploratory Data Analysis (EDA) & Data Cleaning on Titanic Dataset
## Project Overview
This project demonstrates Exploratory Data Analysis (EDA) and Data Cleaning using Python. The Titanic dataset was analyzed to identify missing values, handle inconsistencies, detect outliers, and visualize important patterns in the data.
The project was completed using Pandas, NumPy, Matplotlib, and Seaborn in Jupyter Notebook.
---
## Dataset Information
**Dataset Name:** Titanic Dataset (Sample Dataset)
**Number of Rows:** 20
**Number of Columns:** 7
### Columns
- PassengerId
- Survived
- Pclass
- Sex
- Age
- Fare
- Embarked
---
## Project Objectives
- Load and inspect a CSV dataset using Pandas.
- Identify missing values and calculate their percentage.
- Handle missing values using appropriate imputation techniques.
- Detect and remove duplicate records.
- Identify and handle outliers using the IQR method.
- Perform Exploratory Data Analysis (EDA).
- Generate visualizations using Matplotlib and Seaborn.
- Create a cleaned dataset for further analysis.
---
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
---
## Project Structure
```text
README.md
data/raw_dataset.csv
data/cleaned_dataset.csv
notebooks/eda_and_cleaning.ipynb
docs/summary_report.pdf
.gitignore
```
## Data Cleaning Steps
### Missing Value Treatment
- Missing values were identified using Pandas functions.
- Missing value percentages were calculated.
- Missing values in the Age column were replaced using median imputation.
### Duplicate Removal
- Duplicate records were identified using duplicated().
- Duplicate rows were removed using drop_duplicates().
### Outlier Handling
- Boxplots were used to detect outliers.
- The IQR (Interquartile Range) method was used to handle outliers in numerical columns.
---
## Exploratory Data Analysis
The following visualizations were created:
1. Survival Distribution Count Plot
2. Gender Distribution Count Plot
3. Age Distribution Histogram
4. Correlation Matrix Heatmap
5. Fare Boxplot for Outlier Detection
---
## Key Insights
- Female passengers showed a higher survival rate than male passengers.
- Most passengers were between 20 and 40 years old.
- Passenger class influenced survival outcomes.
- Missing values were successfully handled using median imputation.
- Outlier detection improved data quality.
---
## How to Run
1. Open the notebook:
```text
notebooks/eda_and_cleaning.ipynb
```
2. Run all cells in Jupyter Notebook.
---
## Author
Submitted as part of the Data Science Internship Task – Exploratory Data Analysis (EDA) & Data Cleaning.

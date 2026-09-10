# Road Accident Analysis — EDA

## Project Overview

This project analyzes the 2025 UK road accident dataset to identify
patterns in collision frequency and severity.

The project follows a complete data-analysis workflow:

Raw Data
→ Data Understanding
→ Data Quality Assessment
→ Data Cleaning
→ Exploratory Data Analysis
→ Insights
→ Recommendations

## Dataset

The dataset contains 101,525 recorded road collisions from 2025.

The analysis covers:

- Collision severity
- Date and time
- Day of week
- Road type
- Speed limit
- Weather conditions
- Light conditions
- Road surface
- Urban/Rural area
- Number of vehicles
- Number of casualties

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI

## Project Structure

```text
Road Accident Analysis - EDA
│
├── 01_Raw_Data
│   └── collisions_2025.csv
│
├── 02_Notebooks
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Quality_Assessment.ipynb
│   ├── 03_Data_Cleaning_Preparation.ipynb
│   ├── 04_Exploratory_Data_Analysis.ipynb
│   └── 05_Insights_and_Recommendations.ipynb
│
├── 03_Cleaned_Data
│   └── road_accidents_2025_cleaned.csv
│
├── 04_Visualizations
│
└── 05_Insights
    ├── 01_Key_Findings.md
    ├── 02_Business_Recommendations.md
    └── 03_Project_Summary.md
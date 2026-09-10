# 🚗 Road Accident Analysis – EDA

An end-to-end Exploratory Data Analysis (EDA) project using Python to analyze UK road accident collision data for 2025.

The project focuses on understanding accident patterns, severity, road conditions, time-based trends, casualties, vehicles, and urban/rural differences through data analysis and visualization.

---

## 📌 Project Overview

Road accidents are influenced by many factors such as road type, speed limit, weather, lighting, time of day, and location characteristics.

In this project, I analyzed **101,525 UK road accident collision records from 2025** to identify important patterns and trends.

The analysis follows a complete data analytics workflow:

```text
Raw Data
   ↓
Data Understanding
   ↓
Data Quality Assessment
   ↓
Data Cleaning & Preparation
   ↓
Exploratory Data Analysis
   ↓
Insights & Recommendations
```
This project is completed entirely using Python and EDA techniques.

--- 

## 🎯 Objectives

The main objectives of this project are:

- Understand the structure of the accident dataset.
- Check data quality and identify potential issues.
- Clean and prepare the data for analysis.
- Analyze accident severity.
- Identify monthly and weekly accident patterns.
- Analyze accidents by road type and speed limit.
- Study weather, lighting, and road-surface conditions.
- Compare accident patterns between urban and rural areas.
- Analyze vehicle involvement and casualties.
- Identify meaningful patterns through visualization.
- Convert analytical findings into practical recommendations.

---

## 📊 Dataset

The dataset contains UK road accident collision records for **2025**.

**Source:** UK Department for Transport – Road Safety Open Data

| Dataset Information | Value |
|---|---:|
| Year | 2025 |
| Collision Records | 101,525 |
| Original Columns | 44 |
| Cleaned Columns | 60 |
| File Format | CSV |

---

## 🗂️ Project Structure

```text
road-accident-analysis-eda/
│
├── 01_Raw_Data/
│   └── collisions_2025.csv
│
├── 02_Notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Quality_Assessment.ipynb
│   ├── 03_Data_Cleaning_Preparation.ipynb
│   ├── 04_Exploratory_Data_Analysis.ipynb
│   └── 05_Insights_and_Recommendations.ipynb
│
├── 03_Cleaned_Data/
│   └── road_accidents_2025_cleaned.csv
│
├── 04_Visualizations/
│   └── 15 Final Visualizations
│
├── 05_Insights/
│   └── README.md
│
└── README.md
```

---

## 🔍 Analysis Process

### 1. Data Understanding

The first notebook focuses on understanding the dataset before making any changes.

The analysis includes:

- Dataset shape
- Column names
- Data types
- Numerical and categorical columns
- Missing values
- Duplicate records
- Unique values
- Statistical summary
- Date and time fields
- Accident severity
- Road and environmental variables
- Geographic information

---

### 2. Data Quality Assessment

The dataset was checked for common data-quality issues.

Checks included:

- Missing values
- Duplicate records
- Identifier uniqueness
- Invalid dates and times
- Coordinate validation
- Zero and negative values
- Unusual vehicle counts
- Unusual casualty counts
- Categorical value consistency
- Logical consistency between related fields

Unusual records were investigated rather than automatically removed.

---

### 3. Data Cleaning & Preparation

The raw dataset was prepared for analysis using Pandas.

Main preparation steps included:

- Converting accident dates into datetime format.
- Converting time into a usable time format.
- Creating month and month-name fields.
- Extracting accident hour.
- Creating `part_of_day`.
- Creating `day_type` for weekday/weekend analysis.
- Creating readable accident severity labels.
- Creating readable road-type labels.
- Creating readable weather labels.
- Creating readable light-condition labels.
- Creating readable road-surface labels.
- Creating urban/rural labels.

The cleaned dataset contains **101,525 records and 60 columns**.

---

## 📈 Exploratory Data Analysis

The EDA covers both accident frequency and accident severity.

### Accident Frequency Analysis

The following areas were analyzed:

- Collision severity
- Monthly accident trends
- Day of week
- Part of day
- Road type
- Speed limit
- Urban vs Rural
- Casualties
- Number of vehicles
- Weather conditions
- Light conditions
- Road surface conditions

### Severity Analysis

Additional analysis was performed to understand how severity varies across:

- Speed limits
- Urban and rural areas
- Road types
- Months
- Days of the week
- Parts of the day
- Weather conditions
- Light conditions
- Road surface conditions

---

## 📊 Key Findings

Some of the main findings from the analysis are:

- **101,525 collisions** were analyzed.
- **73.76%** of collisions were Slight.
- **24.81%** were Serious.
- **1.43%** were Fatal.
- **Friday** recorded the highest number of collisions.
- **November** recorded the highest monthly collision count.
- **Single carriageways** had the highest number of recorded collisions.
- **30 mph roads** had the highest number of recorded collisions.
- **Afternoon** had the highest number of collisions among the defined parts of day.
- Most collisions involved **one casualty**.
- Rural areas showed a **higher fatal collision rate** than urban areas.

> **Important:** A higher number of collisions does not automatically mean a higher accident risk. Traffic exposure data such as traffic volume or vehicle miles travelled would be required to measure risk properly.

---

## 💡 Insights & Recommendations

Based on the EDA, several areas can be considered for further road-safety attention.

### Road Safety

Focus further investigation on road types and locations with high collision frequency.

### Rural Roads

The higher fatal collision rate observed in rural areas suggests that rural-road safety deserves additional attention.

### High-Collision Periods

Monthly and weekly patterns can help support better planning of road-safety awareness activities.

### Speed Limits

The high collision count on 30 mph roads should be interpreted together with traffic exposure before drawing conclusions about risk.

### Further Analysis

Combining accident data with traffic volume and road-network information could provide a stronger understanding of accident risk.

---

## 📊 Visualizations

The project contains **15 final visualizations** covering:

1. Collision Severity Distribution
2. Monthly Accident Trend
3. Accidents by Day of Week
4. Accidents by Part of Day
5. Accidents by Road Type
6. Accidents by Speed Limit
7. Urban vs Rural Accident Distribution
8. Casualty Distribution per Collision
9. Vehicles vs Average Casualties
10. Severity Rate by Speed Limit
11. Severity by Urban/Rural Area
12. Monthly Accident Severity Trend
13. Severity by Road Type
14. Severity by Speed Limit
15. Fatal Accident Rate by Area

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**
- **GitHub**

---

## ⚠️ Limitations

This analysis has some limitations:

- The analysis covers only the **2025** collision dataset.
- Traffic exposure data is not included.
- Collision frequency should not be treated as direct accident risk.
- The analysis identifies patterns and associations, not causation.
- Some unusual records require further domain-level investigation.
- Geographic analysis is limited by the available location information.

---

## 🚀 Future Scope

This project can be extended with:

- Multi-year accident trend analysis
- Traffic exposure analysis
- Geographic accident hotspot analysis
- Statistical hypothesis testing
- More detailed time-series analysis
- Accident severity prediction
- Machine learning models
- Integration with additional road and traffic datasets

---

## 📚 Data Source

**UK Department for Transport – Road Safety Open Data**

[https://www.gov.uk/government/statistical-data-sets/road-safety-open-data](https://www.gov.uk/government/statistical-data-sets/road-safety-open-data)

---

## 👨‍💻 Author

**Shivendra Ghadage**

Data Analyst | Python | SQL | Data Analysis

**GitHub:**  
[https://github.com/Shivendra-Ghadage](https://github.com/Shivendra-Ghadage)

---

## ⭐ Project Takeaway

> **Data analysis is not just about creating charts. It is about understanding the data, checking its quality, finding meaningful patterns, and turning those findings into useful insights.**

### 🚗 Raw Data → 🧹 Clean Data → 📊 EDA → 💡 Insights

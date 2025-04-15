# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset using Python libraries: **Pandas**, **Matplotlib**, and **Seaborn**. The aim is to extract meaningful insights from the data using statistical summaries and visualizations.

---

## Objectives

- Understand the structure and contents of the Titanic dataset
- Handle missing values and explore data distributions
- Identify trends, patterns, and correlations
- Visualize survival rates based on different features
- Summarize key findings for further modeling or decision-making

---

## Tools & Libraries Used

- Google Colab (Jupyter Notebook)
- Python 3
- Pandas
- Seaborn
- Matplotlib

---

## Dataset

- **Source**: Seaborn's built-in Titanic dataset (`sns.load_dataset('titanic')`)
- Contains details of passengers including age, sex, class, fare, and survival status.

---

## Key Steps Performed

1. **Data Loading & Exploration**  
   - Used `.info()`, `.describe()`, and `.value_counts()` to understand the dataset.
  
2. **Data Cleaning**  
   - Identified and noted missing values.

3. **Univariate Analysis**  
   - Visualized distributions of age, fare, and class using histograms and boxplots.

4. **Bivariate Analysis**  
   - Explored survival rates by gender, class, and fare using countplots and scatterplots.

5. **Correlation Analysis**  
   - Generated a heatmap to identify numeric relationships between features.

6. **Summary of Findings**  
   - Highlighted key patterns and trends observed in the dataset.

---

## Findings

- **Females** had significantly higher survival rates than males.
- **1st Class passengers** had better survival chances.
- Most passengers were aged between **20–40 years**.
- **Fare** and **Passenger Class** were correlated.
- Missing values were found in **'age'**, **'embarked'**, and **'deck'** columns.

---

## Deliverables

- `Titanic_EDA_Task.ipynb`: Google Colab notebook with all analysis
- `Titanic_EDA_Task.pdf`: PDF version with outputs and visualizations
- `README.md`: This file summarizing the project

---

## How to Use

1. Clone or download this repository
2. Open the `.ipynb` notebook in [Google Colab](https://colab.research.google.com/) or Jupyter
3. Run the cells step-by-step to explore and understand the analysis

---

## Author

- [Your Name]
- B. Pharmacy Graduate | Clinical SAS Trainee | Data Analyst Aspirant

---

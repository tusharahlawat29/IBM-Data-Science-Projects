# Project 03: Titanic Exploratory Data Analysis (EDA)

## Overview
This project involves performing exploratory data analysis on the Titanic passenger dataset to uncover insights about the passengers and factors affecting survival rates.

## Dataset
The dataset contains information about Titanic passengers such as age, sex, passenger class, fare, embarkation port, and survival status.

## Objective
- Understand the structure and contents of the dataset.
- Clean missing values and prepare the data.
- Analyze distributions of important features.
- Visualize survival rates across different groups.
- Identify relationships between features using a correlation heatmap.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Steps Performed
1. **Data Loading:** Imported the Titanic dataset from an online source.
2. **Data Cleaning:** Filled missing values in `Age` and `Embarked` columns; dropped the `Cabin` column due to too many missing values.
3. **Univariate Analysis:** Plotted distributions for numerical variables like Age and Fare, and counts for categorical variables like Gender, Passenger Class, and Embarked port.
4. **Bivariate Analysis:** Analyzed survival rates across Gender and Passenger Class.
5. **Correlation Analysis:** Converted categorical variables to numeric and plotted a correlation heatmap to identify relationships among features.

## Key Findings
- The majority of passengers were between 20-40 years old.
- Females had a higher survival rate compared to males.
- Passengers in first class (`Pclass = 1`) had better survival chances.
- The correlation heatmap shows that gender and passenger class are positively correlated with survival.

## Conclusion
This exploratory data analysis provides useful insights that set the foundation for building predictive models in future projects.


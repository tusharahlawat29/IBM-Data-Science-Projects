# Project 02: Titanic Data Cleaning using Pandas

##  Project Description

This project is part of the IBM Data Science Professional Certificate.  
The goal was to clean and preprocess the Titanic dataset using Python and Pandas to prepare it for further analysis or machine learning tasks.

---

##  Dataset

Dataset used: [Titanic Dataset from GitHub](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)

---

##  Tasks Performed

### 1. **Loading Data**
- Loaded the dataset from an online CSV URL using `pandas.read_csv()`.

### 2. **Identifying Missing Values**
- Checked for missing values using `isnull().sum()`.

### 3. **Handling Missing Data**
- Filled missing values in the `Age` column with the median age.
- Filled missing values in the `Embarked` column with the mode (most frequent value).
- Dropped the `Cabin` column since it had too many missing values.

### 4. **Final Check**
- Printed the dataset to confirm all missing values were handled properly.

---

##  Key Concepts Learned

- Data cleaning using `fillna()`, `drop()`, and summary functions in Pandas.
- Importance of handling missing data before analysis or modeling.
- How to safely clean a real-world dataset using best practices.

---

##  Files Included

- `Titanic_Data_Cleaning.ipynb` → Jupyter notebook containing the full code and outputs.
- `README.md` → This file.

---

##  Next Steps

The cleaned dataset is now ready for data analysis or building machine learning models like logistic regression or decision trees.



Bank Marketing Data Cleaning and Preprocessing

Project Overview

This project focuses on acquiring, assessing, cleaning, and preprocessing the Bank Marketing dataset using Python.

Objectives

* Load and inspect a publicly available dataset.
* Identify actual missing values and unknown categorical entries.
* Detect and remove exact duplicate rows.
* Analyze numerical columns using descriptive statistics.
* Visualize campaign contacts and call duration.
* Save and verify the cleaned dataset.

Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

Dataset

The dataset contains bank marketing campaign records, customer information, campaign details, and the target variable y, 
which indicates whether a customer subscribed to a term deposit.

Data Cleaning Results

* Original dataset: 41,188 rows and 21 columns.
* Dataset after exact duplicate removal: 41,176 rows and 21 columns.
* Actual missing values after cleaning: 0.
* Duplicate rows remaining: 0.
* Unknown categorical values were identified and retained for further investigation.
* We examined potential numerical outliers and retained them pending further investigation.

Files

* Week1_Data_Cleaning.ipynb — Jupyter Notebook containing code, analysis, and visualizations.
* bank_marketing_cleaned.csv — Dataset after exact duplicate removal.

Conclusion

The project establishes a reproducible workflow for inspecting data, removing exact duplicates, examining numerical distributions, and documenting data quality decisions.

Base further preprocessing decisions on the analysis objectives and documented evidence.

# MMLA TEAM 4

**Homework: Data Preprocessing of Machine Learning Solution Project Dataset (Submission)**

_This project contains a Python script for a data preprocessing pipeline. The script addresses data quality issues and inconsistencies, as identified in our Week 2 analysis, to produce a finalized, clean, and reliable dataset ready for the Milestone 1 analysis._

**How to Use**
Place Datasets: Ensure the three contaminated datasets (customer_demographics_contaminated.csv, social_media_interactions_contaminated.csv, and customer_transactions_contaminated.csv) are located in the specified directory: C:\Users\Buboy\Downloads\.

Install Dependencies: Install the necessary libraries using pip:

Bash

pip install pandas numpy matplotlib seaborn scikit-learn scipy
Run the Notebook: Execute the Python script within a Jupyter Notebook. The code will perform all preprocessing steps automatically.

**Preprocessing Techniques Applied**
Following the issues identified in Week 2, the pipeline applies the following data preprocessing techniques using pandas:

Merging: All three datasets are merged into a single DataFrame based on the CustomerID column.

Missing Values:

Visualization: A missing values heatmap is generated and saved as missing_values_heatmap.png.

Imputation: Missing categorical values are filled with the mode, while missing numeric values are filled with the median.

Outliers: Extreme numeric outliers are capped using the Interquartile Range (IQR) method to produce more robust data.

Duplicates: Duplicate rows are removed to ensure each record is unique.

Data Type Conversion: Columns containing dates are converted to the correct datetime format.

Encoding: Categorical variables are converted into a numeric format suitable for machine learning models.

**Output and Submission**

Upon completion, the script will save the following preprocessed datasets in the same directory:

1. cleaned_merged_data.csv

2. normalized_data.csv

3. standardized_data.csv

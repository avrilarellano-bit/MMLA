# MMLA
collaboration 
FinMark Data Preprocessing ProjectOverview
This project is part of a machine learning solution development for FinMark. It focuses on data preprocessing, which is a critical step to ensure the datasets are clean, consistent, and ready for model training.
The datasets used are:
customer_demographics_contaminated.csv
customer_transactions_contaminated.csv
social_media_interactions_contaminated.csv
Objectives
Understand the structure and quality of the datasets.
Remove duplicate entries.
Identify and handle missing values using MCAR and MNAR strategies.
Format and standardize data types.
Encode categorical variables for machine learning compatibility.
Normalize numerical features to improve model performance.
Save cleaned datasets for further analysis and modeling.
Files
FinMark_Data_Preprocessing.ipynb: Jupyter notebook containing all preprocessing steps.
customer_demographics_cleaned.csv: Cleaned version of the customer demographics dataset.
customer_transactions_cleaned.csv: Cleaned version of the transactions dataset.
social_media_interactions_cleaned.csv: Cleaned version of the social media interactions dataset.
How to Use
Open the notebook FinMark_Data_Preprocessing.ipynb in Jupyter.
Ensure the contaminated CSV files are located in the folder:
C:\Users\Buboy
Run each cell sequentially to:
Load and inspect the data
Clean and transform the datasets
Save the cleaned versions
Requirements
Python 3.8+
Libraries:
pandas
numpy
matplotlib
scikit-learn

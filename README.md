# Week 1

Executed these steps in 1st week of internship:

- **Step 1:** Import Required Libraries  
- **Step 2:** Load Dataset  
- **Step 3:** Data Preprocessing


# Week 2

Specifically, I performed the following steps:

- **Dropped the 'Unnamed: 7' column**  
  This column was identified as having no data.

- **Inspected the DataFrame**  
  We checked the column names, data types, and non-null counts using `df.info()` and summary statistics using `df.describe()`.

- **Checked for Null Values**  
  We confirmed there were no null values remaining after dropping the 'Unnamed: 7' column.

- **Visualized Target Variable Distribution**  
  Created a histogram to understand the distribution of the *'Supply Chain Emission Factors with Margins'*.

- **Examined and Encoded Categorical Features**  
  Mapped unique values in `'Substance'`, `'Unit'`, and `'Source'` to numerical representations.

- **Dropped Irrelevant Columns**  
  Removed the `'Name'`, `'Code'`, and `'Year'` columns as they were not needed for modeling.

- **Defined Features and Target**  
  Split the data into features (`X`) and target variable (`y`) for machine learning.

- **Performed Univariate and Multivariate Analysis**  
  Created count plots for categorical variables and a correlation heatmap for numerical variables.

- **Identified Top Emitting Industries**  
  Grouped and visualized data to find the top 10 industries with the highest average supply chain emission factors.

These steps were crucial for **cleaning and preparing the dataset** before building a machine learning model.


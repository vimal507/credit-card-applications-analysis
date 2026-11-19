Credit Card Application Analysis Using Python

Project Overview

This project focuses on analyzing credit card application data using Python. The main objective is to understand customer characteristics and identify patterns associated with credit card approval.

The project uses Exploratory Data Analysis (EDA) techniques to examine customer information, financial details, credit history, and approval status.

Objectives

- Analyze credit card application data.
- Perform data cleaning and preprocessing.
- Identify missing values and duplicate records.
- Explore customer income and expenditure patterns.
- Analyze credit card approval and rejection rates.
- Understand the relationship between customer characteristics and approval status.
- Create visualizations to communicate important findings.

Dataset Information

- Dataset: Credit Card Applications
- Total Records: 1,319
- Total Columns: 13
- Target Column: "card"
- Approval Categories: Yes and No

Important Columns

Column| Description
card| Credit card approval status
reports| Number of major derogatory reports
age| Customer age
income| Customer income
share| Expenditure share
expenditure| Customer expenditure
owner| Home ownership status
selfemp| Self-employment status
dependents| Number of dependents
months| Customer account duration in months
majorcards| Number of major credit cards
active| Number of active credit accounts
rownames| Row identifier

Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Project Workflow

1. Data Loading

Imported the credit card application dataset using Pandas.

2. Data Inspection

- Checked dataset dimensions.
- Examined column names and data types.
- Used "head()", "tail()", "info()", and "describe()".

3. Data Cleaning

- Checked missing values.
- Identified duplicate records.
- Checked numerical variables for potential outliers using boxplots.

4. Exploratory Data Analysis (EDA)

- Analyzed credit card approval distribution.
- Calculated average age, income, and expenditure.
- Compared customer characteristics based on approval status.
- Examined correlations between numerical variables.

5. Data Visualization

Created the following visualizations:

- Correlation heatmap.
- Home ownership vs. credit card approval.
- Customer expenditure distribution.
- Credit card approval distribution.
- Income vs. credit card approval.
- Income vs. expenditure scatter plot.

Key Insights

1. Credit Card Approval: Out of 1,319 applicants, 1,023 (77.56%) received approval, while 296 (22.44%) were rejected.

2. Credit History: Applicants with zero major derogatory reports had an approval rate of approximately 86.32%, compared with 41.70% for applicants with one or more reports.

3. Home Ownership: Homeowners had an approval rate of approximately 84.51%, compared with 72.09% for non-homeowners.

4. Expenditure and Share: The correlation analysis showed a strong positive relationship between expenditure and share (0.84).

Conclusion

This project provided practical experience in Python-based data analysis, data cleaning, exploratory data analysis, and data visualization.

The analysis identified differences in credit card approval patterns based on credit history and home ownership. It also highlighted relationships between financial variables such as income, expenditure, and expenditure share.

Overall, this project demonstrates how Python can be used to explore financial datasets and generate meaningful business insights.

Author

Vimal

Aspiring Data Analyst

Skills: Python | Pandas | NumPy | Matplotlib | Seaborn | Exploratory Data Analysis

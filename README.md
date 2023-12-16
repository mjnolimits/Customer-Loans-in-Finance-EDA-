# Exploratory Data Analysis - Customer Loans in Finance

# Purpose

This project aims to conduct EDA on a loan portfolio using statistical and data visualization techniques to unveil patterns, relationships, and anomalies in loan data. The data is prepared for machine learning algorithms by addressing the impact of outliers and data skewness. Additionally, the project visualizes future payments and attempts to correlate user data parameters with failing loan payments. The ultimate goal is to empower the business to make more informed decisions regarding loan approvals, pricing, and risk management.

# Installation Instructions
1. ```pip install -r requirements.txt```


# Running Instructions
1. Run the main.ipynb file

# File Modules
1. ./format.py: Class to convert columns into the correct format, such as categorical columns, more efficient data types, and numerical columns that better fit into numerical representations, as well as dates.
2. ./info.py: Provides information about the shape of the data, skewness of numericals, missing data, and general statistics where needed.
3. ./plotter.py: Offers visualization methods for the data, including histograms, KDE, qq_plot, and the ability to do so across multiple columns.
4. ./transform.py: Responsible for imputation and transformation of data to prepare for more machine learning applications by creating a normal distribution.

# Note
I use __main__ within each of these modules to explore the data initially and then finally use main.ipynb to follow a specific structure.
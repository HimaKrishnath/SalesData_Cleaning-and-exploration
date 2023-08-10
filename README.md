# SalesData_Cleaning-and-exploration
Machine Learning Python Project
This repository contains code and data for a Machine Learning project conducted using Python. The project aims to analyze and derive insights from a sales dataset using various data analysis and visualization techniques.

Contents
Introduction
Downloading the Data
Getting Started with the Code
Task #1: Merging CSVs into a Single DataFrame
Task #2: Adding a Month Column
Cleaning the Data
Task #3: Adding a Sales Column
Question #1: Best Month for Sales
Question #2: City with the Most Sales
Question #3: Optimal Advertisement Time
Question #4: Most Frequently Sold Product Pairs
Question #5: Best-Selling Product and its Impact

Introduction
In this project, we analyze a sales dataset using Python's Pandas library. The dataset includes information on sales transactions, including products, quantities, cities, and timestamps. We use data analysis and visualization techniques to derive insights and answer key questions related to sales trends.
Downloading the Data
The first step involves downloading the dataset. The data is stored in separate CSV files, and we'll need to merge them into a single DataFrame for analysis.



Getting Started with the Code
Before running the code, ensure you have Jupyter Notebook installed. The code is provided in Jupyter Notebook format for better visualization and interactivity.

Task #1: Merging CSVs into a Single DataFrame
To work with the dataset effectively, we merge multiple CSV files into a single DataFrame. This allows us to analyze the complete dataset in one place.

Task #2: Adding a Month Column
We add a 'Month' column to the DataFrame to facilitate time-based analysis. This involves parsing timestamps and extracting the month information.

Cleaning the Data
Data cleaning is a crucial step to remove inconsistencies and missing values. We demonstrate how to drop NaN values and remove rows based on certain conditions.

Task #3: Adding a Sales Column
We calculate and add a 'Sales' column to the DataFrame. This involves converting columns to numeric types and performing calculations.

Question #1: Best Month for Sales
We analyze the sales data to determine the best month for sales. Visualization using a bar chart helps us understand sales trends over different months.

Question #2: City with the Most Sales
We identify the city that recorded the highest sales. By adding a 'City' column and using Pandas' .apply() method, we answer this question and visualize the results.

Question #3: Optimal Advertisement Time
To maximize the likelihood of purchases, we analyze the best time for displaying advertisements. We use the to_datetime() method to process timestamps and plot the results.

Question #4: Most Frequently Sold Product Pairs
We explore which products are most often sold together. Using techniques like identifying duplicates and joining values, we determine commonly paired products.

Question #5: Best-Selling Product and its Impact
We investigate the product that sold the most and speculate on the reasons behind its success. Visualization, including overlaying a second Y-axis, helps interpret the data.






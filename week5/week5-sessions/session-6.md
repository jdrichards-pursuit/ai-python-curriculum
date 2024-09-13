# Session 6: Introduction to pandas, Data Exploration, and Working with Datasets

## Lesson Objectives

- Understand what pandas is and its significance in data manipulation
- Create and work with pandas Series and DataFrames
- Read and write data using pandas
- Perform data exploration and basic analysis
- Use essential pandas methods like .describe(), .head(), .columns
- Learn how to create and export datasets to CSV files
- Compare pandas DataFrames to JavaScript data structures

## Topics Covered

### Introduction to pandas

- What is pandas?
  - A powerful library for data manipulation and analysis in Python
  - Built on top of NumPy, providing additional functionality
- Importing pandas
  - Standard import: import pandas as pd
- Role in data analysis workflows
  - Data cleaning, transformation, merging, and analysis

### pandas Series and DataFrames

- Series
  - 1-dimensional labeled array
  - Creating Series from lists or dictionaries
  - Accessing elements using labels or integer indices
- DataFrames
  - 2-dimensional labeled data structure with columns of potentially different types
  - Creating DataFrames from dictionaries, lists, or NumPy arrays
  - Understanding DataFrame structure: index, columns, and data

### Data Input/Output

- Reading Data from CSV Files
  - Using pd.read_csv('filename.csv') to load data into a DataFrame
  - Understanding file paths and common parameters
- Writing Data to CSV Files
  - Exporting DataFrames to CSV using .to_csv('filename.csv')
  - Parameters like index and header options
- Creating a CSV from a Dataset
  - Collecting or creating data within pandas
  - Saving the DataFrame to a CSV file

### Data Exploration and Analysis

- Viewing Data
  - .head() Method: Displays the first few rows of the DataFrame
  - .tail() Method: Displays the last few rows of the DataFrame
  - .columns Attribute: Accessing the list of column names in the DataFrame
  - .shape Attribute: Getting the number of rows and columns in the DataFrame
- Descriptive Statistics
  - .describe() Method: Generates summary statistics of numerical columns
  - Includes count, mean, standard deviation, min, max, and quartiles
  - Understanding the Output: Interpreting the statistical measures
- Data Selection and Filtering
  - Selecting columns and rows
  - Filtering data based on conditions
- Handling Missing Data
  - Identifying missing values with .isnull()
  - Handling missing data using .dropna() and .fillna()

### Working with Datasets

- Introduction to Datasets
  - What datasets are and their importance in data analysis
  - Examples of common datasets (e.g., Iris dataset, Titanic dataset)
- Loading Sample Datasets
  - Using pandas to load datasets from CSV files
  - Exploring the structure and content of datasets
- Creating Custom Datasets
  - Collecting data manually or generating synthetic data
  - Structuring data into DataFrames
- Exporting DataFrames to CSV
  - Saving processed or new datasets for future use
  - Ensuring data integrity during export

### Integrating with Jupyter Notebook

- Displaying DataFrames within the notebook
- Documenting findings using Markdown cells
- Visualizing data distributions using basic plots (if time permits)

### Comparison with JavaScript

- Comparing pandas DataFrames to JavaScript objects and arrays
- Discussing JavaScript libraries like D3.js or Lodash for data manipulation
- Highlighting the strengths of pandas for data analysis tasks

## Additional Resources

- [pandas Official Documentation](https://pandas.pydata.org/docs/)
- [10 Minutes to pandas - Official Tutorial](https://pandas.pydata.org/docs/user_guide/10min.html)
- [pandas Cheat Sheet - DataCamp](https://www.datacamp.com/community/blog/python-pandas-cheat-sheet)
- [JavaScript for Data Science - Observable](https://observablehq.com/@observablehq/javascript-for-data-science)

# SalesAnalysis

In this project Python Pandas & Python Matplotlib have been used to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

Data Cleaning | Tasks performed:

1. Drop NaN values from DataFrame
2. Removing rows based on a condition
3. Change the type of columns (to_numeric, to_datetime, astype)

Exploratory Data Analysis | 5 high level business questions related to our data:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

The following were covered as to answer the aforementioned questions :

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling graphs

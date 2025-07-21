# Mall-Customers

## Table of Contents

- [Data Description](#dataset-description)
- [Content](#content)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [EDA](# EDA)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

### Dataset Description(Overview)
A Company with the dataset Mall-Customers is on a quest to extract insights from their customer database in other to fast-speed the Company’s revenue and to enhance their operations and sales strategies.

### Content
 The dataset comprises 201 rows, observations across 5 variables, each illuminating different facets of the company's operations and customer interactions:

The key data points used for analysis include:
- Customer Id: Identifier for each customer.
- Gender: Identifier for Sex
- Age: The Age of the customers tha patronize
- Annual_Income_(k$): The income generated to mall company
- Spending_Score: The value assigned to mustomers base on spending habits and other criteria

### Data Sources

- The data source for the analysis is a CSV file (comma separated values) named "Mall_Customers.csv" from Kaggle for analytical illustration.

### Tools:
- The analysis involves several queries performed against the ' Mall Customers' table in the SQLite database, along with some data manipulation and visualization using pandas, matplotlib, seaborn and plotly.

### Data Cleaning
* 1. Null/empty value check: 2 rows missing value detected.
* 2. Removal of the null values
* 3. Duplicate value check: no duplicates found.
 
###  EDA
 is performed on the dataset using visualization techniques to gain insights about sales trends. These visualizations include:
- Relplot (scatter plot matrix): Showing the gender that patronized most
- Pie charts: Showing the gender counts
- Bar plots: Showing gender with highest income.
- Dis plots: Showing gender count. 

### Findings
* Total Annual income is 12,084
* Females are the gender with more patronage with 56.3% compare to the males with 43.7%.
* Age with the highest Annual Income is age 32, and the lowest revenue is 55,56, and 64.
* Despite female having the highest revenue the male largely supersede in the area of Spending Score.

### Recommendations

### Conclusion

# Topic:  Mall Customers Analysis

### Project Overview: Sales Analysis and Visualization for Lita

- This project analyzes sales data from the Mall customers dataset to identify key business insights. 
- The analysis is performed using SQL queries and Python libraries (pandas, matplotlib, seaborn) for data manipulation and visualization.
- The dataset about Mall customers contains of 201 rows and 5 columns and alse some Null values.


### Data Understanding

The key data points used for analysis include:
- Customer Id: Identifier for each customer.
- Gender: Identifier for Sex
- Age: The Age of the customers tha patronize
- Annual_Income_(k$): The income generated to mall company
- Spending_Score: The value assigned to mustomers base on spending habits and other criteria 

### Data Sources:
- The data source for the analysis is a CSV file named "Mall_Customers.csv"

### Key Objectives:

1. Sales Performance:
- Calculating the total Annual Income.
- Finding the gender that patronize the Mall most
- Checking for gender that visited most
- Identify the Age with highest Income
- Identify the gender that generate the highest Income
- Deleting the Null values

### Tools

- The analysis involves several queries performed against the ' Mall Customers' table in the SQLite database,
  along with some data manipulation and visualization using pandas, matplotlib, seaborn and plotly.

###  EDA (Exploratory Data Analysis)
 is performed on the dataset using visualization techniques to gain insights about sales trends. These visualizations include:
- Relplot (scatter plot matrix): Showing the gender that patronized most
- Pie charts:Showing the gender counts
- Bar plots: Showing gender with highest income.
- Dis plots: Showing gender count.
### Recommendation

1. Targeted Regional Marketing:
The analysis reveals varying product demand across regions.  For instance, "Jackets" might be a primary need in the North, but less so elsewhere.  Implement targeted marketing campaigns in each region, highlighting products relevant to local needs and climate.  This includes promotions, advertising, and localized product displays.

2. Promotional Pricing Strategies:
Introduce tiered pricing or promotions for products less popular in certain regions.  "Second-class" products (perhaps variations or older models) could be offered at discounted prices to expand market share in regions where they aren't primary needs. This incentivizes trial and adoption, increasing sales and visibility in the long run.  Simultaneously offer these discounted options in primary regions to target price-sensitive customers.

3. Inventory Optimization:
Based on regional sales data, adjust inventory levels to ensure sufficient stock of high-demand products in specific regions while minimizing surplus of low-demand products.  This can improve sales efficiency and reduce storage costs.

4. Customer Segmentation:
Analyze customer purchasing behavior to identify segments with distinct needs and preferences. This allows for more tailored marketing efforts, product recommendations, and loyalty programs.  Combine regional data with customer segmentation to create highly targeted promotions.

5. Data-Driven Decision Making:
Continue to regularly monitor sales data, product performance, and regional trends.  Use dashboards and visualizations to identify emerging patterns and quickly adjust strategies. This ensures agile responses to changing market conditions and customer preferences.

6. Product Diversification (Consideration):
Explore expanding the product line to include items that better cater to the specific needs of underperforming regions.   This may increase sales and expand the customer base in those regions.

7. Enhance Data Collection:
Consider expanding data collection to include additional customer demographics, purchase motivations, and feedback.  This will allow for deeper insights into customer preferences and refined marketing strategies.

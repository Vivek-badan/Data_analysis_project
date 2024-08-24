[README.md](https://github.com/user-attachments/files/16736466/README.md)# Diwali Sales Analysis

This project provides a comprehensive analysis of the Diwali sales dataset. It involves data cleaning, exploratory data analysis (EDA), and visualization to uncover insights about sales patterns.

## Dataset

The dataset `diwali_sales.csv` contains sales data with the following columns:

- **User_ID**: Unique identifier for each user.
- **Cust_name**: Customer's name.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the customer.
- **Age Group**: Age group of the customer.
- **Age**: Age of the customer.
- **Marital_Status**: Marital status of the customer (0: Single, 1: Married).
- **State**: State where the purchase was made.
- **Zone**: Zone of the state.
- **Occupation**: Occupation of the customer.
- **Product_Category**: Category of the purchased product.
- **Orders**: Number of orders placed.
- **Amount**: Total amount spent.

## Data Cleaning

- **Dropping Unnecessary Columns**: Removed columns `Status` and `unnamed1` as they contained no useful information.
- **Handling Missing Values**: Dropped rows with missing values in the `Amount` column.
- **Data Type Conversion**: Converted the `Amount` column to integer type for better analysis.

## Exploratory Data Analysis (EDA)

### Gender Analysis

- **Distribution of Genders**: Visualized the count of male and female buyers using a bar chart.
- **Total Amount by Gender**: Analyzed the total amount spent by each gender.

### Age Analysis

- **Age Group Distribution**: Explored the distribution of buyers across different age groups.
- **Total Amount by Age Group**: Visualized the total amount spent by each age group.

### State Analysis

- **Top States by Number of Orders**: Identified the top 10 states with the highest number of orders.
- **Top States by Total Sales**: Analyzed the top 10 states with the highest total sales amount.

### Marital Status Analysis

- **Distribution of Marital Status**: Visualized the count of orders based on marital status.

## Visualizations

- **Gender Distribution**: Shows that most buyers are female and their purchasing power is higher.
- **Age Group Analysis**: Provides insights into which age groups are spending more.
- **State Analysis**: Highlights states with the highest number of orders and sales amount, with Uttar Pradesh and Karnataka being significant contributors.
- **Marital Status Distribution**: Illustrates the purchasing pattern based on marital status.

## Libraries Used

- `numpy` for numerical operations
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization
g README.md…]()

## Conclusion
This analysis provides insights into customer behavior during Diwali sales, helping businesses understand spending patterns and customer demographics.

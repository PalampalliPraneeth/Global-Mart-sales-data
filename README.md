# Global-Mart-sales-data
This project involves analyzing a retail orders dataset to derive insights such as the top revenue-generating products, the highest selling products by region, month-over-month sales growth, and more. The project is implemented using Python for data preprocessing and SQL for querying the data.The main objectives are data cleaning, transformation, and exploratory data analysis.

## Installation
### Prerequisites
- Python 3.x
- pandas
- sql alchemy library
- Kaggle API
- Microsoft SQL Server
- An ODBC driver for SQL Server
### Clone the Repository
First, clone the repository to your local machine:
```bash
git clone https://github.com/PalampalliPraneeth/Global-Mart-sales-data.git
cd Global-Mart-sales-data
```
### Install the required Python libraries
```bash
pip install pandas sqlalchemy kaggle
```
### Kaggle API Setup
Ensure you have your Kaggle API key set up. Follow Kaggle API setup instructions.
### Usage
### Step 1: Download and Extract the Dataset
The script downloads the dataset from Kaggle, extracts it, and loads it into a pandas DataFrame.
### Step 2: Data Preprocessing
The script handles null values, renames columns, derives new columns (discount, sale price, profit), converts the order date to datetime format, and drops unnecessary columns.
### Step 3: Load Data into SQL Server
The script loads the processed data into a SQL Server database.
### Step 4: Execute SQL Queries
The SQL code provides insights into the retail orders data by executing the following queries:
1) Top 10 Highest Revenue Generating Products:
Finds the top 10 products with the highest revenue based on the sum of sale_price.
2) Top 5 Highest Selling Products in Each Region:
Retrieves the top 5 highest-selling products for each region, based on the sum of sale_price.
3) Month-over-Month Growth Comparison for 2022 and 2023 Sales:
Compares the sales between 2022 and 2023 on a month-by-month basis.
4) Month with Highest Sales for Each Category:
Identifies the month with the highest sales for each product category.
5) Sub-category with Highest Growth by Profit in 2023 Compared to 2022:
Finds the sub-category that experienced the highest growth in profit in 2023 compared to 2022.
Run the provided SQL queries to derive insights from the data.

### Contributions
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

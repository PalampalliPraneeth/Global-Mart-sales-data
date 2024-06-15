# Global-Mart-sales-data
This project involves analyzing a retail orders dataset to derive insights such as the top revenue-generating products, the highest selling products by region, month-over-month sales growth, and more. The project is implemented using Python for data preprocessing and SQL for querying the data.The main objectives are data cleaning, transformation, and exploratory data analysis.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Python Script](#python-script)
4. [SQL Queries](#sql-queries)
5. [Contributing](#contributing)
6. [License](#license)

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
git clone https://github.com/yourusername/retail-orders-analysis.git
cd retail-orders-analysis
```
### Install the required Python libraries

```bash
pip install pandas sqlalchemy kaggle
```
### Kaggle API Setup
Ensure you have your Kaggle API key set up. Follow Kaggle API setup instructions.

### Usage
Step 1: Download and Extract the Dataset
The script downloads the dataset from Kaggle, extracts it, and loads it into a pandas DataFrame.

### Step 2: Data Preprocessing
The script handles null values, renames columns, derives new columns (discount, sale price, profit), converts the order date to datetime format, and drops unnecessary columns.

### Step 3: Load Data into SQL Server
The script loads the processed data into a SQL Server database.

### Step 4: Execute SQL Queries
Run the provided SQL queries to derive insights from the data.

### Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

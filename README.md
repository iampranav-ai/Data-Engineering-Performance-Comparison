# DuckDB vs Pandas Performance Comparison

This project compares the performance of DuckDB and pandas for various data analysis tasks on an e-commerce dataset. It aims to provide insights into which library performs better for different types of operations.

## Project Description

The script performs the following operations on an e-commerce dataset:

1. Count the total number of events
2. Count the number of unique users
3. Find the top 10 most viewed products
4. Calculate the total revenue
5. Calculate the average purchase price
6. Count events by type

These operations are performed using both DuckDB and pandas, and the execution time for each operation is measured and compared.

## Requirements

- Python 3.7+
- DuckDB
- pandas

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/duckdb-pandas-comparison.git
   cd duckdb-pandas-comparison
   ```

2. Install the required packages:
   ```
   pip install duckdb pandas
   ```

## Usage

1. Ensure your e-commerce dataset (named '2019-Oct_ecommerce_bigData.csv') is in the same directory as the script.

2. Run the script:
   ```
   python duckdb_pandas_comparison.py
   ```

3. The script will output the results and execution times for each operation, followed by an overall performance comparison.

## Sample Output

The output will look something like this:

```
DuckDB Performance:
1. Total number of events: [...], Time: X.XXXX seconds
2. Number of unique users: [...], Time: X.XXXX seconds
...

Pandas Performance:
1. Total number of events: [...], Time: X.XXXX seconds
2. Number of unique users: [...], Time: X.XXXX seconds
...

Total time (DuckDB): X.XXXX seconds
Total time (Pandas): X.XXXX seconds
DuckDB is X.XXx faster than Pandas for these operations
```

## Acknowledgments

- This project uses [DuckDB](https://duckdb.org/) and [pandas](https://pandas.pydata.org/), two powerful data analysis libraries for Python.

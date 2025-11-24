
## Objective
Use SQL queries inside Python to get a basic sales summary (total quantity sold & total revenue) and visualize it using a simple bar chart.

## Tools Used
- Python
- SQLite (sqlite3 module)
- Pandas
- Matplotlib
- Google Colab (online, free)

## Steps Performed
1. Created a SQLite database named `sales_data.db`.
2. Created a table `sales` with columns: product, quantity, price.
3. Inserted sample sales data.
4. Executed SQL query to calculate:
   - Total quantity sold per product
   - Total revenue per product
5. Loaded results using pandas.
6. Printed the results using DataFrame.
7. Created a bar chart using matplotlib to visualize revenue by product.


## Output Sample
SQL Result:

| Product | Qty | Revenue |
|---------|-----|----------|
| Apple | 15 | 225 |
| Banana | 35 | 175 |
| Mango | 20 | 400 |

Bar chart also included in the repo.

🛠️ Technologies Used

Python 3

SQLite3

Pandas

Matplotlib

Jupyter Notebook / Google Colab


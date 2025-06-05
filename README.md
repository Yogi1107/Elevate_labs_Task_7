# Basic Sales Summary with SQLite and Python

This project shows how to connect to a SQLite database using Python, execute simple SQL queries to summarize sales data, and visualize the results using a bar chart.

---

## Features

- Create and connect to a SQLite database (`sales_data.db`)
- Store sample sales data in a table
- Run SQL queries to compute:
  - Total quantity sold per product
  - Total revenue per product
- Display results using:
  - `print()` statements
  - A `matplotlib` bar chart
- Save the chart as `sales_chart.png`

---

## Technologies Used

- Python 3.x
- SQLite (via `sqlite3` module — built-in)
- pandas
- matplotlib

---

## Project Structure

- task_7.ipynb # Python script to generate report
- sales_chart.png # Output chart image (auto-generated)
- README.md # Project documentation

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sales-summary-sqlite.git
cd sales-summary-sqlite
```

2. Install requirements
```bash
pip install pandas matplotlib
```

3. Run the script (in Jupyter Notebook)
```bash
python task_7.ipynb
```

The script will:
  - Create sales_data.db (if not already present)
  - Insert sample sales data
  - Print product-wise total quantity and revenue
  - Show and save a bar chart of revenue per product

## Sample Output
Console Output:
```css
Sales Summary:
  product  total_qty  revenue
0   Apple         15     37.5
1  Banana         27     27.0
2  Orange         15     45.0
```

Learning Goals
  - This project helps you learn:
  - How to use SQLite with Python
  - Basic SQL aggregation (GROUP BY, SUM)
  - Data loading with pandas
  - Simple data visualization with matplotlib

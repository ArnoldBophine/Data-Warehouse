## Bophine Arnold Odiyo 668821

## Database and Data Analysis Project
This project demonstrates the use of Python, SQLite, and Pandas for basic database creation, manipulation, and data analysis. It is structured to introduce fundamental operations such as printing output, setting up a relational database, inserting records, retrieving them, and analyzing the data using Pandas.

## Objectives

The main objectives of this project are:

To demonstrate a simple "Hello World" program in Python.

To create and interact with a SQLite database (data_warehouse.db).

To define and populate a relational table (employees).

To perform data retrieval and store the results in a Pandas DataFrame.

To explore the dataset using Pandas functionalities:

Displaying data samples.

Getting column info.

Generating descriptive statistics.

Checking for missing values.

##  Project Structure

## Notebook/Script contains:

Cell 1: Prints hello world.

Cell 2:

Connects to a SQLite database (data_warehouse.db).

Creates a table called employees.

Inserts sample employee records.

Fetches and displays the data.

Converts the results into a Pandas DataFrame.

Displays DataFrame info, description, and missing value checks.

## Requirements

Install the following Python libraries before running the project:

pip install pandas matplotlib


(Standard libraries like sqlite3 are included with Python.)

 ## How to Run

Clone/download this repository.

Open the Jupyter Notebook (.ipynb) or Python script (.py).

Run all cells in order.

## Expected output includes:

"hello world" printed to the console.

Confirmation of database creation and table setup.

Employee records displayed.

DataFrame overview (head, info, description).

Missing values summary.

## Example Output
hello world

Connected to database: data_warehouse.db
Table employees created successfully
Fetched Data:
(1, 'Alice', 24, 50000)
(2, 'Bob', 30, 60000)
(3, 'Charlie', 22, 55000)
(4, 'David', 35, 70000)
(5, 'Eva', 28, 65000)

Sample DataFrame Output:
   id     name  age   salary
0   1    Alice   24  50000.0
1   2      Bob   30  60000.0
2   3  Charlie   22  55000.0
3   4    David   35  70000.0
4   5      Eva   28  65000.0

Pandas Summary Statistics:

             age        salary
count   5.000000      5.000000
mean   27.800000  60000.000000
std     4.768647   7905.694150
min    22.000000  50000.000000
25%    24.000000  55000.000000
50%    28.000000  60000.000000
75%    30.000000  65000.000000
max    35.000000  70000.000000

Followed by DataFrame details and statistics.

 ## Future Improvements

Add more database tables and relationships.

Implement CRUD (Create, Read, Update, Delete) operations.

Visualize employee data using Matplotlib/Seaborn.

Extend analysis for real-world HR or finance datasets.

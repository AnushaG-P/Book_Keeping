# Book Keeping Database

## Overview

The **Book Keeping Database** contains detailed information about books, authors, publishers, and their ratings. It is designed to store and manage book-related data efficiently. This repository includes a SQLite database, code snippets, and visualization components to help with data analysis.

### Contents
- **Database File**: The SQLite database is stored in the `database` folder and is in `.zip` format for easier access and portability. Inside the zip file, you'll find two primary tables: `book_data` and `book_details`, which store key book information.
  
- **Code (Jupyter Notebook)**: The associated `.ipynb` file contains Python code snippets that can be used to create new CSV files and import data into the database. It also includes sample code for data analysis and visualization, which can be used to generate insights from the database.

- **Visualizations**: The Jupyter notebook provides several visualization components that will allow users to explore the data visually. These visualizations help in understanding trends, patterns, and correlations across different data points such as book ratings, publication dates, and more.

## Features

1. **Book Data**: 
   - `book_data` contains columns such as book title, author, publisher, average rating, publication date, and more.
   - The database supports queries for grouping, counting, filtering, and sorting based on various criteria.

2. **Book Details**:
   - The `book_details` table stores detailed information like the number of pages, language, and other metadata associated with each book.

3. **Code for Data Ingestion**: 
   - The `.ipynb` file includes Python code that allows you to generate and import new CSV files into the database. You can also update the existing records as needed.

4. **Visualizations**:
   - Visualizations are included in the notebook to help you analyze the dataset. These include graphs and charts to visualize the average ratings, publication trends, and more.

## How to Use

### Step 1: Extract the Database
1. Download and unzip the `Book_keeping.db.zip` file.
2. Place the `Book_keeping.db` file in the `database` folder.

### Step 2: Set Up Your Environment
1. Ensure you have Python installed along with the necessary libraries:
   - `sqlite3` for interacting with the SQLite database
   - `pandas` for data manipulation
   - `matplotlib`, `seaborn` for visualizations

   You can install the required libraries using the following:
   ```bash
   pip install pandas matplotlib seaborn

# Book Keeping Database

## Overview

This project utilizes both **structured** and **unstructured data** to build a comprehensive book database. While the structured data consists of attributes such as book titles, authors, ratings, and publication details, the **unstructured data** is represented by **book cover images**. These images are converted into multi-dimensional arrays, which are then used to uniquely identify and associate books.

## Unstructured Data - Book Covers

The **book cover images** serve as the unstructured data in the database. By processing these images into multi-dimensional arrays, we enable the system to identify each book in a unique manner. This integration allows the database to not only store traditional book details but also incorporate visual features, enhancing its ability to categorize and recognize books dynamically.

## File Structure

- **Database Folder**: The database is stored in a zip file located in the `database` folder. It includes the main `Book_keeping.db` database file, which contains the tables for both book data and book details.

## Features

- **CSV File Creation**: The accompanying `.ipynb` file contains code snippets that help in creating new CSV files from the database, providing flexibility for data exports and further analysis.
- **Visualizations**: The notebook also includes visualizations that help analyze and interpret the data, giving insights into the books and their attributes.

## Getting Started

1. **Extract the Database**: Unzip the database file in the `database` folder.
2. **Run the Code**: Use the provided `.ipynb` file to create and modify CSV files, as well as to explore the data visually.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

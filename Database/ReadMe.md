# Book Keeping Database

## Overview

This repository contains a **Book Keeping Database** that stores structured data about books, including details like author names, book titles, ratings, publishers, and more. In addition to the structured data, the database integrates **unstructured data** in the form of book cover images, which are processed into multi-dimensional arrays for unique identification of books.

The database is stored in a **ZIP format** and resides within the `database` folder.

## Structure

The database consists of the following tables:

1. **book_data**: Contains structured data about books, including:
   - Title
   - Author
   - Publisher
   - Average Rating
   - Number of Pages
   - Publication Date

2. **book_details**: Contains additional details such as:
   - Book cover images (as multi-dimensional arrays)
   - Audio files associated with each book (for auditory learning)

Additionally, the **ZIP** file format allows easy downloading, extraction, and management of the database.

## Files Included

- **Book_keeping.db**: The primary SQLite database file containing the structured and unstructured data.
- **Images Folder**: A folder containing book cover images used as unstructured data in the database.
- **Audio Folder**: A folder containing audio files associated with books, sourced from open-source platforms.

## Features

- **Structured and Unstructured Data**: Combines structured book data with unstructured data like images and audio files to offer a rich, multi-faceted resource.
- **Book Cover Identification**: The book covers are processed into multi-dimensional arrays for unique book identification, improving the overall functionality of the database.
- **Comprehensive Data**: The database supports querying and analysis based on a variety of book attributes, such as ratings, publishers, and authors.

## Usage

### Extract the Database

To begin using the database:
1. Download and extract the `Book_keeping.zip` file.
2. Access the database file `Book_keeping.db` inside the `database` folder.

### Code Examples

In the included **Jupyter Notebook** (`ipynb` file), you will find code snippets to:
- Create new CSV files
- Import them into the database
- Visualize the data from the database

### Visualizations

The notebook also includes visualizations that present:
- Book ratings distribution
- Publisher trends
- Author performance

These visualizations help in understanding the patterns and relationships within the book data.

## License

This project is licensed under the [MIT License](LICENSE), which allows you to freely use, modify, and distribute the database.

## Conclusion

The **Book Keeping Database** offers a comprehensive resource for managing and exploring book-related data, combining both structured information and unstructured media for an enriched experience. It is ideal for use in data science, machine learning, and information retrieval projects.


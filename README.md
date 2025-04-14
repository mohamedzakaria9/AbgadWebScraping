# Abjad Books Data Scraper

This repository contains data scraped from the Abjad website, featuring book information across multiple categories. The data is saved in both CSV and XLSX formats for flexibility and ease of access.

## Project Structure

- `books_data.csv` - The dataset saved in CSV format.
- `books_data.xlsx` - The dataset saved in XLSX format.
- `webScrapping.ipynb` - The Python script used for scraping the data.

## Data Description

The dataset includes the following columns:

- **book\_title**: The title of the book.
- **book\_author**: The author of the book.
- **book\_description**: A brief summary or description of the book.
- **book\_number\_of\_pages**: The number of pages in the book.
- **book\_rating**: The book's rating on Abjad.
- **book\_genera**: The genre or category of the book.
- **book\_numbers\_of\_reviews**: The number of reviews the book has received.
- **book\_url**: A direct link to the book's Abjad page.
- **book\_cover\_photo\_url**: A link to the book's cover image.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/abjad-books-data.git
   cd abjad-books-data

## Viewing the Data

- For **CSV** data: Open with any text editor, Excel, or use pandas in Python.
- For **XLSX** data: Open with Excel or any compatible spreadsheet software.

## Example (Using Pandas)

```python
import pandas as pd

# Load CSV file
df = pd.read_csv("books_data.csv")
print(df.head())

# Load XLSX file
df_xlsx = pd.read_excel("books_data.xlsx", engine='openpyxl')
print(df_xlsx.head())
```

## Notes

- The data may contain some missing values due to incomplete entries on the Abjad website.
- The scraper includes a delay to prevent overloading the website and to comply with ethical scraping practices.

## License

This project is open-source under the [MIT License](LICENSE).

## Contributing

Feel free to submit pull requests or open issues for improvements, new features, or bug fixes.



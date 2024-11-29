# Quotes Web Scraper and Analyzer

This project is a Python-based web scraper and data analyzer that extracts quotes, authors, and associated tags from the website [Quotes to Scrape](http://quotes.toscrape.com). It processes the data to create structured CSV files and includes functionalities for filtering and analyzing quotes by tags.

## Features

- Scrapes quotes, authors, and tags from multiple pages.
- Cleans and processes the data for further analysis.
- Identifies the top 10 most frequent tags on the website.
- Creates CSV files:
  - `data1.csv`: Contains all scraped quotes with binary columns for the top 10 tags.
  - `data2.csv`: Filters quotes by selected tags and sorts them by the author's name.

## Setup and Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```
2. Navigate to the project directory:
   ```bash
   cd yourrepository
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   *(Make sure to include a `requirements.txt` file with libraries such as `requests`, `beautifulsoup4`, `pandas`, and `nltk`.)*

4. Download the NLTK stopwords and tokenizer resources:
   ```python
   import nltk
   nltk.download('stopwords')
   nltk.download('punkt')
   ```

## How to Use

1. Run the Jupyter Notebook or script:
   ```bash
   jupyter notebook Script.ipynb
   ```
   or execute it as a Python script:
   ```bash
   python Script.ipynb
   ```

2. The output CSV files (`data1.csv` and `data2.csv`) will be saved in the project directory.

## Collaboration

This project was developed by:
- [Migueldiazpdj](https://github.com/migueldiazpdj)
- [Stefanie03](https://github.com/Stefanie03)
- [DanteSc03](https://github.com/DanteSc03)

## License

This project is licensed under the MIT License.
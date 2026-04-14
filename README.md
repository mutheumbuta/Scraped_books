# Scraped_books

## Project Overview

The Price Scraper + Currency Converter is a Python data project that extracts product prices from an e-commerce website and converts them into different currencies.

The project demonstrates practical skills in web scraping, API integration, data processing, and data storage. It simulates how businesses monitor product pricing and convert prices for international markets.

The scraper collects product titles and prices, converts the prices into another currency, and stores the results in structured formats such as CSV and JSON.

## Project Objectives

Scrape product information from an online store

Extract and clean product titles and prices

Convert prices between currencies

Display results in a readable table format

Save the processed data into files for further analysis

## Technologies Used
Python

Requests

BeautifulSoup

Pandas

Tabulate

## Data Source

The product data is scraped from:

https://books.toscrape.com/

This website is specifically designed for practicing web scraping.

Data collected includes:

Product title

Product price (GBP)

Converted prices (USD and KES)

## Project Structure

price-scraper-currency-converter

│
├── price_scraper_converter.py

├── product_prices.csv

├── product_prices.json

├── requirements.txt

└── README.md

## Features

### Web Scraping

The program uses BeautifulSoup to scrape at least 10 products from the website.

Extracted information includes:

Book title

Original price

### Currency Conversion

Product prices are converted into additional currencies such as:

USD

KES

This simulates how businesses display prices for international customers.

### Data Display

The scraped data is displayed in a structured table format using Pandas.

Example output:

Product Name	Price GBP	Price USD	Price KES

Book Title	51.77	64.71	8283

### Data Export

The program automatically saves the results into:

CSV file

JSON file

These files can be used for further analysis or integration into other systems.

## Installation

Clone the repository:

git clone https://github.com/yourusername/price-scraper-currency-converter.git

Navigate into the project folder:

cd price-scraper-currency-converter

Install required libraries:

pip install -r requirements.txt

### Running the Project

Run the Python script:

python price_scraper_converter.py

The program will:

. Scrape product data

Convert prices

Display results

Save data to files

## Example Output
Scraped Product Prices

Product Name                 Price_GBP   Price_USD   Price_KES

A Light in the Attic           51.77       64.71       8283

Tipping the Velvet             53.74       67.17       8598

Soumission                     50.10       62.62       8016

Generated files:

product_prices.csv

product_prices.json

## Error Handling

The program includes error handling to manage:

Internet connection issues

Website request failures

Invalid responses

## Future Improvements

1. Possible enhancements include:

2. Adding pagination to scrape more products

3. Using a live currency exchange API

4. Allowing users to select currencies dynamically

5. Creating a Streamlit dashboard for interactive visualization

6. Scheduling automatic price monitoring

## Skills Demonstrated

. This project demonstrates the following data and programming skills:

. Web scraping

. Data cleaning

. Data transformation

. API usage

. File handling

. Error handling

## License

## author
Nancy Mutheu Mbuta

email:mutheumbuta@gmail.com

Github: mutheumbuta

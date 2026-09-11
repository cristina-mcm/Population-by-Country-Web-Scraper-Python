# Population by Country Web Scraper

## Overview

This project uses Python to scrape population statistics by country from the Worldometer website. The extracted data is cleaned, organized in a pandas DataFrame, and exported as a CSV file.

The project:

1. Sends a request to the webpage using UTF-8 encoding.
2. Parses the webpage HTML with Beautiful Soup.
3. Locates the population table.
4. Extracts and cleans the column headings and rows.
5. Standardizes Unicode minus signs.
6. Stores the results in a pandas DataFrame.
7. Exports the completed dataset as a UTF-8 encoded CSV file.

## Data Source

[Worldometer – Population by Country](https://www.worldometers.info/world-population/population-by-country/)

The table includes population, yearly change, land area, population density, fertility rate, median age, urban population, and world population share.

## Tools Used

- Python
- Requests
- Beautiful Soup
- pandas
- Jupyter Notebook

## Repository Contents

- `Population by Country Scraper.ipynb` – Web-scraping code and explanations
- `world_population.csv` – Extracted population data
- `README.md` – Project documentation

## Acknowledgement

This was completed as a guided project based on Alex The Analyst's Data Analyst Bootcamp tutorial, using a different website and dataset for additional practice.

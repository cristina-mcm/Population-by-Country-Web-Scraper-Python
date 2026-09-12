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

## Table on the website

<img width="1111" height="266" alt="image" src="https://github.com/user-attachments/assets/62b00ce1-5683-4ebe-a6d7-b47b8a8b4276" />

## CSV Table

<img width="1172" height="142" alt="image" src="https://github.com/user-attachments/assets/3394e0c6-a618-4c4f-ba92-5a7998654079" />


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

This was completed as a guided project based on Alex The Analyst's Data Analyst Bootcamp tutorial, using a different website and dataset and with a few changes to the code.

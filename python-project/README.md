# Stock Price and Revenue Analysis with Python

This Python script performs analysis and visualization of historical stock prices and revenue data for Tesla and GameStop using data fetched from Yahoo Finance and web scraping HTML tables.

## Overview

The script demonstrates how to:

- Retrieve historical stock price data using the `yfinance` library.
- Scrape revenue data from HTML tables hosted on specified URLs using `requests` and `BeautifulSoup`.
- Clean and preprocess the scraped revenue data using `pandas`.
- Visualize the data using `matplotlib` and `plotly.graph_objects`.

## Dependencies

Ensure you have the following Python libraries installed:

- `yfinance`: Fetches historical stock price data.
- `pandas`: Manipulates and analyzes data.
- `requests`: Retrieves HTML content from URLs.
- `beautifulsoup4`: Parses HTML content.
- `matplotlib`: Plots static graphs.
- `plotly`: Creates interactive visualizations.

You can install these dependencies using pip:

```
pip install yfinance pandas requests beautifulsoup4 matplotlib plotly
```

## Usage

1. **Data Collection**:
   - Uses `yfinance` to fetch historical stock price data (`Close` prices).
   - Scrapes revenue data from HTML tables hosted on specified URLs.

2. **Data Processing**:
   - Cleans and preprocesses revenue data to remove null values and format numerical data.

3. **Visualization**:
   - Utilizes `matplotlib` for basic stock price and revenue line plots.
   - Uses `plotly` for interactive subplot visualizations of stock prices and revenues.

4. **Examples**:
   - Includes examples of fetching and visualizing data for Tesla (`TSLA`) and GameStop (`GME`).

## Example Code

The script contains functions to fetch data, clean it, and visualize it using Plotly and Matplotlib. It focuses on demonstrating how to integrate financial data retrieval, web scraping, data cleaning, and visualization in Python.

# IPython Notebook (.ipynb)

This IPython Notebook (Stock_Price_and_Revenue_Analysis.ipynb) is formatted as an interactive computational document. It contains Python code cells interspersed with markdown cells for documentation.

## File Format
- **Format:** IPython Notebook (.ipynb)
- **Content:** Combination of executable code cells (Python) and markdown cells (formatted text, headings, lists). 
- **Execution:** Execute code cells sequentially to run the analysis and generate visualizations.

# Screenshots

Screenshots showing outputs of the code execution are provided in the images folder within the project directory. These images illustrate the generated plots and data visualizations from the notebook.

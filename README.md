# Stock Data Analysis and Visualization: Tesla & GameStop

This project is a Python-based analysis and visualization of Tesla and GameStop stock data. It involves extracting stock and revenue data using web scraping and the `yfinance` library, followed by visualizing the data with graphs to create a simple dashboard.

## Project Overview

In this project, we analyze the stock prices and revenue data of two major companies: Tesla and GameStop. The data is retrieved using two approaches:
1. **yfinance** for extracting stock price data.
2. **Web Scraping** for extracting revenue data from financial websites like MacroTrends.

The extracted data is visualized using `matplotlib` to generate an informative dashboard-like presentation with multiple graphs.

### Key Features:
- **Stock Data Extraction:** Using `yfinance` to extract historical stock data for Tesla and GameStop.
- **Revenue Data Extraction:** Using web scraping techniques to collect revenue data for Tesla and GameStop.
- **Data Visualization:** Visualizing stock prices and revenue data using `matplotlib` for both Tesla and GameStop in a cohesive dashboard layout.

## Technologies Used
- **Python 3**
- **yfinance** for stock data extraction
- **BeautifulSoup** and **requests** for web scraping revenue data
- **Matplotlib** for data visualization

## Project Structure
The project is structured into the following sections:

1. **Data Extraction:**
    - Extracting Tesla stock data using `yfinance`.
    - Extracting GameStop stock data using `yfinance`.
    - Web scraping Tesla revenue data from MacroTrends.
    - Web scraping GameStop revenue data from MacroTrends.

2. **Data Visualization:**
    - Plotting Tesla stock prices and revenue data.
    - Plotting GameStop stock prices and revenue data.
    - Creating a dashboard-like layout with subplots for side-by-side comparison.

3. **Interactive Dashboard (Optional):**
    - This project provides static visualizations, but can be extended to an interactive dashboard using libraries like `plotly` or `dash`.

## Future Improvements

- **Interactive Dashboard:** Integrate `plotly` or `dash` for an interactive, web-based dashboard.
- **Data Updates:** Automate the data extraction process to keep the stock and revenue data up-to-date.
- **Extended Analysis:** Add more companies or additional financial metrics for a broader analysis.

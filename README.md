# Tesla Stock and Revenue Analysis Dashboard
This project explores Tesla’s financial performance over time by analyzing historical stock prices and revenue data. Using Python, web scraping, and data visualization tools, it brings together real-world data to build    insights and create a simple dashboard.
# Project Overview
The goal of this project is to:
- Extract Tesla’s historical stock data using the yfinance API.
- Scrape quarterly revenue data from a financial website using requests and BeautifulSoup.
- Clean and organize both datasets for analysis.
- Visualize Tesla’s stock price and revenue trends using Plotly.
- Build an interactive dashboard to explore this data side by side.
# Tools and Technologies
Python
pandas
yfinance
requests
BeautifulSoup
plotly.graph_objects
Jupyter Notebook
#  Steps Performed
- Collected stock data using the Ticker function from the yfinance library.
- Scraped revenue data from a public website using requests.get() and BeautifulSoup for HTML parsing.
- Cleaned the data by removing missing values and converting string formats to numeric.
- Filtered dates to ensure both stock and revenue data align on a common timeline.
- Built an interactive dual-axis line chart showing Tesla’s stock closing price and reported revenue over time.
# Result
A cleaned dataset containing Tesla’s historical revenue and stock data.
An interactive Plotly line graph with:
Stock price on one axis
Revenue on the other
Insights into how Tesla’s revenue aligns with its stock market performance

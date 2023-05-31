# Stock-Price Analysis
## Analyzed the Stock Price of Tesla and GME

* In this project, we analyzed the share price and quarterly revenue of Tesla(TSLA) and GameStop(GME).

* The yfinance package was used to extract the share price data for both Tesla(TSLA) and GameStop(GME).

* The quarterly revenue data for both companies was extracted using web scraping with the BeautifulSoup package.

* We created a function called "Graph" to visualize the share price and quarterly revenue data. The graph includes an X-axis range slider, allowing the user to select the desired period for data analysis.

* To create the graphs, we utilized the Plotly package, providing users with an interactive experience for analyzing and extracting more information.

* When analyzing Tesla (TSLA) stock, we observed a correlation between quarterly revenue and share price.

![FALIED TO LOAD THE GRAPH PLEASE GO THROUGH THE ATTACHED SOURCE CODE](https://github.com/rockys-project/Stock-Price-Analysis/blob/main/Graphs/TSLA.png)

* Analyzing the graph, we noticed that GameStop Corp's(GME) quarterly revenue has consistently been high during the last quarter of every year, coinciding with the holiday season in the United States when customers purchase games for the holidays.

![FALIED TO LOAD THE GRAPH PLEASE GO THROUGH THE ATTACHED SOURCE CODE](https://github.com/rockys-project/Stock-Price-Analysis/blob/main/Graphs/TSLA.png)

* However, there was no significant fluctuation in share price in relation to the revenue in GameStop(GME). It is presumed that the shareholders understand the revenue pattern of the company and do not sell off their shares.

### Below are descriptions of the packages used for further information.

# yfinance 
yfinance is a Python library that provides an easy-to-use interface for accessing and retrieving historical market data, as well as real-time financial information from Yahoo Finance. It allows developers and data scientists to programmatically interact with the vast amount of financial data available on Yahoo Finance's website.

With yfinance, users can easily obtain historical pricing data, stock quotes, dividend data, corporate actions, and more. It provides a convenient and efficient way to fetch financial data for a wide range of assets, including stocks, ETFs (Exchange-Traded Funds), mutual funds, options, currencies, and cryptocurrencies.

One of the notable features of yfinance is its ability to fetch historical market data for a specified time period. Users can retrieve historical prices for a particular asset, allowing them to analyze trends, perform technical analysis, and backtest trading strategies. This capability makes yfinance a valuable tool for quantitative analysis and algorithmic trading.

In addition to historical data, yfinance also offers real-time data through the use of the get_live_price() function. This function allows users to access the current market price of a specific asset, enabling them to build applications that require real-time financial data.

yfinance is built on top of the popular pandas library, which makes it easy to manipulate and analyze financial data once it has been retrieved. It provides a simple and intuitive interface, allowing users to fetch data with just a few lines of code.


# BeautifulSoup

The BeautifulSoup package is a popular Python library used for web scraping tasks. It provides a convenient and efficient way to extract data from HTML and XML documents. With BeautifulSoup, developers can parse and navigate through the structure of a web page, allowing them to extract specific information of interest.

Here are some key features and functionalities of the BeautifulSoup package:

1. **Parsing HTML and XML:** BeautifulSoup can handle imperfect or poorly formatted HTML and XML documents. It automatically converts such documents into a parse tree, making it easier to navigate and extract data.

2. **Navigating the parse tree:** BeautifulSoup provides various methods and techniques to navigate the parse tree and locate specific elements. Developers can search for elements by their tags, attributes, text content, or other criteria, allowing them to target the desired data.

3. **Extracting data:** Once the desired elements are located, BeautifulSoup provides methods to extract the data from those elements. Developers can retrieve the text content, attributes, or even the entire HTML structure of the elements.

4. **Modifying and manipulating data:** BeautifulSoup allows developers to modify the parse tree or manipulate the data extracted from it. They can add, remove, or modify elements, attributes, or text content as needed.

5. **Integration with web scraping workflows:** BeautifulSoup can be seamlessly integrated with other libraries and tools commonly used in web scraping workflows. It works well with libraries such as requests for fetching web pages and pandas for data manipulation and analysis.

Overall, BeautifulSoup simplifies the process of extracting data from HTML and XML documents, making it an essential tool for web scraping tasks. It provides a robust and flexible API that enables developers to efficiently navigate and extract the desired information from web pages, saving time and effort in data collection and analysis.


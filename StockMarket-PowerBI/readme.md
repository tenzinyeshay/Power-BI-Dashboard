# Stock Market Performance Dashboard (Power BI)

This repository contains a Power BI dashboard designed to provide a comprehensive overview and detailed summary of stock market performance. It aims to help users analyze stock data, track key metrics, and gain insights into investment trends.

## Dashboards

The project includes two main dashboard views:

1.  **Stock Overview:**
    * **Purpose:** Provides a high-level summary of stock performance, focusing on key aggregated metrics.
    * **Key Metrics:** Total current value, total investment, total gain/loss, overall gain/loss percentage, and total number of holdings.
    * **Visualizations:** Includes cards for key metrics, a donut chart showing the split by sector, and a line chart to visualize gain/loss over time.
    * **Interactive Features:** Filters for different sectors and the ability to drill down into monthly data.
    * **Example Image:** `StockOverview.png`

2.  **Stock Summary:**
    * **Purpose:** Offers a detailed breakdown of individual stock holdings, allowing for granular analysis.
    * **Key Metrics:** Individual stock values, investment amounts, gain/loss, current price, shares held, and average buy price.
    * **Visualizations:** Primarily a detailed table summarizing each stock, along with a bar chart showing gain/loss by stock.
    * **Interactive Features:** Filters for individual stocks and the ability to sort by various columns.
    * **Example Image:** `StockSummary.png`

## Features

* **Key Performance Indicators (KPIs):** Track overall portfolio health at a glance.
* **Sector Analysis:** Understand the performance distribution across different industry sectors.
* **Historical Trends:** Visualize gain/loss over time to identify performance patterns.
* **Detailed Stock Breakdown:** Review individual stock performance with essential metrics.
* **Interactive Filtering:** Easily filter data by sector, stock name, and timeframes to focus on specific areas of interest.

## Getting Started

To view and interact with this Power BI dashboard:

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/tenzinyeshay/stock-market-powerbi.git
    ```
    
2.  **Open the Power BI File:** Locate the `StockDashboard.pbix` file in the cloned repository and open it with Power BI Desktop.

3.  **Explore the Dashboards:** Navigate through the different pages (tabs) in Power BI Desktop to explore the "Stock Overview" and "Stock Summary" views.

## Data Source

The data for "BUKA stock market" originates from the Indonesia Stock Exchange (IDX), as "BUKA" is the stock ticker for PT Bukalapak.com Tbk, an Indonesian e-commerce company. 
The historical stock price data for IDX 30 stocks, including BUKA, is sourced from Kaggle.
You can find the dataset here: [IDX 30 Stocks Price History](https://www.kaggle.com/datasets/rhesamulyadi/idx-30-stocks-price-history?select=BUKA_2006-01-01_to_2022-03-16.csv)

## Contact

For any questions or feedback, please contact Tenzin Yeshay at tenzin.yeshay89@gmail.com 

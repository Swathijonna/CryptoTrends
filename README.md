# CryptoTrends: Analyzing Bitcoin's Price History
# Overview
This project aims to analyze historical Bitcoin price data using Python and various data visualization libraries. The analysis covers exploratory data analysis (EDA), visualization of price trends, and examining the daily percentage change in Bitcoin's closing price.
# Dataset Description
 ## The dataset used in this project contains historical Bitcoin prices from April 28, 2013, to July 31, 2017. It includes the following columns:
               Date: The date of the recorded price.
               Open: Opening price of Bitcoin on that date.
               High: Highest price of Bitcoin reached during that day.
               Low: Lowest price of Bitcoin reached during that day.
               Close: Closing price of Bitcoin on that date.
               Volume: Trading volume of Bitcoin on that date.
               Market Cap: Market capitalization of Bitcoin on that date.
# Tools Used
   ## Python Libraries:
      Pandas: For data manipulation and analysis.
      NumPy: For numerical operations.
      Matplotlib and Seaborn: For data visualization.
      Plotly and Cufflinks: For interactive visualizations.
# Analysis Steps
## 1.Data Cleaning and Preparation:
      Converted the 'Date' column to datetime format.
      Checked for missing values and duplicates.
      Sorted the data by date in descending order for better visualization. 
## 2.Exploratory Data Analysis (EDA):
        Plotted the trend of Open, High, Low, and Close prices over time.
        Visualized candlestick plots using Plotly to show high, low, open, and close prices of Bitcoin on a subset of data.
## 3.Visualization:
       Examined the distribution and trends of closing prices.
       Explored closing prices on yearly, quarterly, and monthly bases to understand Bitcoin's price movements over different time periods.
       Calculated and visualized the daily percentage change in Bitcoin's closing price.
# Conclusion:
The analysis shows that Bitcoin prices have been highly unpredictable, with periods of rapid growth followed by significant drops, demonstrating how Bitcoin's value can change dramatically over time.

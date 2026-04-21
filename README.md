# ACC102 Track 2: AAPL Stock Price Analysis

## 1. Problem & User
This project analyzes historical price trends, volatility, and moving averages of Apple Inc. (AAPL) stock using Python. It is intended for finance students, beginner investors, and anyone learning financial data analysis.

## 2. Data
- **Source**: Yahoo Finance
- **Access Date**: April 2026
- **Key Fields**: Open, High, Low, Close, Adjusted Close, Volume
- **Time Range**: 2020-01-01 to 2025-12-31

## 3. Methods
- Data loading and cleaning using `pandas` (handling missing values, renaming columns, converting data types)
- Descriptive statistics (mean, median, standard deviation, min/max values)
- Daily return calculation
- Moving average analysis (20-day and 50-day)
- Data visualization with `matplotlib` (price trend, moving averages)

## 4. Key Findings
- The average closing price of AAPL stock over the period was approximately $164.55.
- The stock showed an overall upward trend from 2020 to 2025.
- The highest closing price reached around $285.93, while the lowest was approximately $55.11.
- Moving averages helped identify short-term and medium-term price trends.
- Daily returns followed a roughly normal distribution with moderate volatility.

## 5. How to Run
1. Download or clone this GitHub repository to your local computer.
2. Open the project folder on your computer.
3. Make sure Python and pip are installed.
4. Open a terminal or command prompt inside the project folder.
5. Install all required libraries by running this command:
   ```bash
   pip install -r requirements.txt

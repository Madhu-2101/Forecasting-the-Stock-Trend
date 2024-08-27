# Stock Market Analysis

## Project Summary:

- **Objective:** Analyze stock price data and implement a moving average crossover strategy for generating buy/sell signals.
- **Dataset:** Historical stock price data is retrieved using the `yfinance` library.
- **Moving Averages:** Calculated short-term (20-day) and long-term (50-day & 200-day) simple moving averages (SMA).
- **Signal Generation:** Buy and sell signals are generated based on the crossover of short and long-term SMAs.
- **Visualization:** The stock prices and SMAs are visualized using `matplotlib` and `mplfinance`. Buy/sell points are marked on the graphs.
- **Custom Function:** The `crossover` function allows for selecting different time zones ('LONG' or 'SHORT') and generates appropriate trading signals.
- **Image Processing:** Used `OpenCV` to highlight specific sections of the graph by masking specific colors and displaying the results.

## Conclusion:
The project effectively predicts buy/sell points based on SMA crossovers, offering a visual and analytical approach to stock trading strategies.

# Currency-exchange-rate
### Objective:
The goal of this project is to analyze daily exchange rate trends of major global currencies against the Vietnamese Dong (VND), detect unusual patterns or outliers, evaluate volatility and appreciation/depreciation trends, and forecast short-term movements. This helps understand how global macroeconomic factors—such as tariffs and political shifts—affect currency value over time.

### Data Source:
Exchange rate data was collected through daily web scraping from [Vietcombank website](https://www.vietcombank.com.vn/vi-VN/KHCN/Cong-cu-Tien-ich/Ty-gia). A loop-based function was developed to automatically fetch and generate daily exchange rates, which were then compiled and stored in a single dataset for analysis. Timeframe: 01/01/2025 - 20/04/2025

### Project Content:
Crawl and Create Dataset:
- Crawl Data from Website and Clean Data: Retrieved raw data and standardized it for consistency and accuracy.
- Create a Function to Auto-generate Exchange Rate: Designed a reusable function to automate the scraping process.
- Fetch Exchange Rate Data for a Time Range and Save to a File: Applied the function over a time range and consolidated the output.
Analyzing Currency Exchange Rate:
- Current Exchange Rate Analysis and Outlier Detection: Identified high-value currencies and detected extreme outliers like the Kuwaiti Dinar (KWD) using box plots.
- Currency Volatility and Appreciation/Depreciation Trends: Assessed the fluctuation of exchange rates and evaluated which currencies were strengthening or weakening.
- Future Value Forecasting: Predicted short-term exchange rate trends using time series models, highlighting currencies with stable or volatile outlooks.

### Findings:
- The Kuwaiti Dinar (KWD) consistently outperforms other currencies, appearing as a significant outlier.
- Major currencies like the GBP, EUR, and CHF show both high value and high volatility, while regional currencies such as CNY and THB remain more stable.
- The RUB showed the strongest appreciation, while KRW and AUD showed signs of depreciation.
- Forecasts indicate continued stability in key currencies like USD and JPY, with slight upward trends for EUR and GBP.

# Time-Series-Analysis-of-Financial-Data
Objective:
The objective of this analysis was to examine the autocorrelation and stationarity of financial time series data, specifically for AAPL (Apple Inc.) stock prices and EUR/USD exchange rates. Additionally, a Vector Autoregression (VAR) model was applied to US Treasury Bond yields to assess interdependencies.

Data and Methodology:
Data for AAPL stock prices, EUR/USD exchange rates, and various US Treasury Bond yields were obtained and processed. Time series analysis techniques, including Autocorrelation Function (ACF) analysis, Augmented Dickey-Fuller (ADF) tests, and VAR modeling, were employed.

1. Autocorrelation Function Analysis:

AAPL Stock Prices: High autocorrelation values were observed for price levels across multiple lags, indicating a strong persistent trend in the data. The highest autocorrelation was at lag 1 (0.995), gradually decreasing with further lags.
AAPL Stock Returns: ACF values for returns were significantly lower, with most values close to zero, suggesting that returns do not exhibit significant autocorrelation.
EUR/USD Exchange Rates: Similar to AAPL prices, the EUR/USD exchange rate showed high autocorrelation in price levels, indicating a persistent trend. The return series, however, displayed low autocorrelation.

2. Stationarity Analysis (ADF Test):
AAPL Stock Prices and EUR/USD Exchange Rates: The ADF test indicated non-stationarity in price levels (high p-values), suggesting a unit root presence in the series.
AAPL Stock Returns and EUR/USD Exchange Returns: These series were found to be stationary (p-values of 0.0), implying no unit root.

3. Vector Autoregression (VAR) Model for US Treasury Bond Yields:
The VAR model was applied to analyze the interdependencies among different maturities of US Treasury Bond yields.
The results showed various degrees of influence between different maturities, as evidenced by the coefficients in the VAR model.
The correlation matrix of residuals indicated a strong correlation between different bond yields, especially between longer maturities.
Interpretation and Conclusions:
The ACF analysis revealed significant trends in the price levels of AAPL and EUR/USD, while their returns showed characteristics of a white noise series. The stationarity analysis confirmed these findings, indicating the need for differencing to achieve stationarity in price levels.

The VAR model highlighted the interrelated movements of US Treasury Bond yields. The results can be beneficial for understanding the dynamic interactions in the bond market, which is crucial for risk management and investment strategies.



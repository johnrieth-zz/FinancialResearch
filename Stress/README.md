# Financial Stress Index

### Readings
- [Kansas City Federal Reserve Stress Index](https://www.kansascityfed.org/research/indicatorsdata/kcfsi)
- [Financial Stress: What Is It, How Can It Be Measured, and Why Does It Matter?](https://www.kansascityfed.org/PUBLICAT/ECONREV/pdf/09q2hakkio_keeton.pdf) (PDF)
- [What is the St. Louis Fed Financial Stress Index?](https://www.stlouisfed.org/on-the-economy/2014/june/what-is-the-st-louis-fed-financial-stress-index)
- [Measuring Financial Market Stress](https://files.stlouisfed.org/files/htdocs/publications/es/10/ES1002.pdf) (PDF)
- [List of Data Series Used to Construct the St. Louis Fed Financial Stress Index](https://www.stlouisfed.org/news-releases/st-louis-fed-financial-stress-index/stlfsi-key)
- [St. Louis Fed’s Financial Stress Index Appendix](https://files.stlouisfed.org/files/htdocs/publications/net/NETJan2010Appendix.pdf) (PDF)

### Creating the Index

I did my best to follow construction of the St. Louis Fed's Financial Stress Index. The Monthly and Weekly Stress Indexes are different than the Federal Reserve Indexes. One reason is using different data. I do not want to use proprietary data such as Baa-rated corporate and Merrill Lynch assets. A second reason could be different tools to implement the indexes.

"First, each of the data series is de-meaned. The de-meaned series are then divided by their respect
ive sample standard deviations (SDs). With the variables now expressed in the same units, we use the method of principal components to calculate the coefficients of the variables in the financial stress index (FSI). We then scale these coefficients so that the SD of the index is 1. Finally, each data series is multiplied by its respective adjusted coefficient, and the observation of the FSI for time _t_ is the sum of each series multiplied by its respective adjusted coefficient. Higher values of the FSI indicate a greater degree of financial stress in the economy." [St. Louis Fed’s Financial Stress Index][1]

[1]: https://files.stlouisfed.org/files/htdocs/publications/net/NETJan2010Appendix.pdf  "St. Louis Fed’s Financial Stress Index"

### Data
| Monthly Stress Index Variables |
|---------- |
| Effective federal funds rate |
|  10-Year Treasury Constant Maturity Minus 3-Month Treasury Constant Maturity |
| 10-Year Treasury Constant Maturity Rate |
| 2-Year Treasury Constant Maturity Rate |


### Data used by Federal Reserve banks

| Kansas City Financial Stress Index Variables | 
|---------- | 
| 3-month LIBOR/3-month T-bill spread |
| 2-year swap spread |
| Off-the-run/on-the-run 10-year Treasury spread |
| Aaa/10-year Treasury spread |
| Baa/Aaa spread |
| High-yield bond/Baa spread |
| Consumer ABS/ 5-year Treasury spread |
| Negative value of correlation between stock and
Treasury returns |
| Implied volatility of overall stock prices (VIX) |
| Idiosyncratic volatility (IVOL) of bank stock prices |
| Cross-section dispersion (CSD) of bank stock returns |

| St. Louis Financial Stress Index Variables |
| ---------- |
| Effective federal funds rate |
| 2-year Treasury |
| 10-year Treasury |
| 30-year Treasury |
| Baa-rated corporate |
| Merrill Lynch High-Yield Corporate Master II Index |
| Merrill Lynch Asset-Backed Master BBB-rated |
| Yield curve: 10-year Treasury minus 3-month Treasury |
| Corporate Baa-rated bond minus 10-year Treasury (corporate credit risk spread) |
| Merrill Lynch High-Yield Corporate Master II Index minus 10-year Treasury (high-yield credit risk spread) |
| 3-month London Interbank Offering Rate–Overnight Index Swap spread (3-month LIBOR-OIS spread) |
| 3-month Treasury-Eurodollar spread (TED spread) |
| 3-month commercial paper minus 3-month Treasury bill (commercial paper spread (3-month)) |
| J.P. Morgan Emerging Markets Bond Index Plus |
| Chicago Board Options Exchange Market Volatility Index (VIX) |
| Merrill Lynch Bond Market Volatility Index (1-month) |
| 10-year nominal Treasury yield minus 10-year Treasury Inflation Protected Security yield (breakeven inflation rate (10-year)) |
| S&P 500 Financials Index |

#### Similar Work

- [An Index of Financial Stress for Canada](https://www.bankofcanada.ca/2003/06/working-paper-2003-14/)
- [OFR Financial Stress Index](https://www.financialresearch.gov/financial-stress-index/)
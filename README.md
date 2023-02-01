# Project 1: Analysis of Asset Performance in a Recession

Code developed by Andrew Bader, Evelyn Nazginov, Kunal S, and Max Accurso

## Table of Contents
1. [Introduction](#Introduction)
    - a. [Current Market Environment in America](#Market)
    - b. [Project Objectives](#Objectives)
    - c. [Ressions and Time Periods](#Time)
    - d. [Asset Classes and Index Used](#Asset)
2. [Analysis of Recessions](#Analysis)
    - a. [The 2001 Recession](#2001)
    - b. [The 2008 Recession](#2008)
    - c. [The 2020 Recession](#2020)
3. [Conclusions and Key Findings](#Findings)
4. [Project Operations](#Operations)
    - a. [Data Collection and Cleanup](#Data)
    - b. [Approach](#Approach)
    - c. [Data Sources](#Sources)

## 1. Introduction <a name="Introduction"></a>

As fears of an upcoming recession in the USA ramp up, our group conducted an in-depth analysis of various asset’s performance throughout the previous three recessionary environments. We utilized the S&P 500 as the benchmark to measure each other asset against. We included a diverse group of assets in attempt to capture the entirety of the market. Of the twelve assets analyzed, we chose six equity sectors, the ten-year treasury, gold, oil, USD, and the CBOE volatility index. The goal was to reveal the overall impact of a recession on each asset and define any trends or relationships among classes and across recession periods. Our group aimed to discover market tendencies which could lead to further insight into future recessions and guide capital providers on how to protect their investments.

### a. Current Market Environment in America <a name="Market"></a>

Since mid-2022, a heated debate has been taking place among politicians, economists, and market experts regarding the future of the US economy, and whether it is headed towards a recession or not. The argument is often swayed by political affiliations and hinges on the interpretation of the word "recession".

According to a widely accepted definition of recession, two consecutive quarters of negative GDP growth would signal a recession, which would have started in the summer of 2022. However, the National Bureau of Economic Research (NBER), the organization responsible for defining US business cycles, does not agree with this assessment. The NBER views a recession as a substantial decrease in economic activity across the country that persists for more than a few months, and does not believe that a recession occurred in the summer of 2022.

Despite this disagreement, the possibility of a recession still looms in the near future. The Federal Reserve has expressed its intention to increase interest rates until inflation begins to cool down from its current state, which could trigger a downturn in the economy that would be universally recognized as a recession.

Economic Data from the Most Recent Reports:
 - GDP Q4 2022 +2.9% (good)
 - CPI December +6.5% (bad)
 - Treasury Yield Curve 10Y/2Y Spread -0.66% (inverted, bad)
 - Unemployment Rate December 3.5% (good)
 - Initial Jobless Claims January 190,000 (good)
 - Housing Starts December -1.4% (bad)

### b. Project Objectives <a name="Objectives"></a>

- Analyze the performance of major indices, sectors, and securities throughout past recessions
- Calculate steepest decline (or incline) for the assets from peak to trough in each recession
- Calculate the percentage of value decrease (or increase) over the course of the recession
- Calculate the time to recovery (pre-recession levels) for each asset
- Report any intermarket relationship or correlations findings
- Utilize findings to provide guidance into future recessionary environments

### c. Recessions and Time Periods <a name="Time"></a>

- The 2001 Recession a.k.a 9/11 Recession (March-November 2001)
- The 2008 Recession a.k.a Great Recession (December 2007 - June 2009) 
- The 2020 Recession a.k.a COVID-19 Recession (February-April 2020)

### d. Asset Classes and Index Used <a name="Asset"></a>

- Stocks: S&P 500 (SPX) 
- CBOE Volatility Index (VIX)
- Bonds: Treasury Yield 10 Years (TNX)
- Gold: LBMA Gold Price
- US Dollar: USDX Index (DX-Y.NYB)
- Technology Sector: SPDR Fund (XLK) 
- Financial Sector: SPDR Fund (XLF) 
- Energy Sector: SPDR Fund (XLE) 
- Utilities Sector: SPDR Fund (XLU) 
- Health Care Sector: SPDR Fund (XLV) 
- US Real Estate ETF: iShares (IYR) 
- Oil Prices: Crude Oil WTI Futures

## 2. Analysis of Recessions <a name="Analysis"></a>

### a. The 2001 Recession <a name="2001"></a>

![9/11 Recession Equity Sectors](Charts/9-11%20Recession/9_11_Sectors.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![9/11 Recession TNX and S&P](Charts/9-11%20Recession/9_11_TNX_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![9/11 Recession Gold and S&P](Charts/9-11%20Recession/9_11_Gold_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![9/11 Recession USD and S&P](Charts/9-11%20Recession/9_11_USD_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![9/11 Recession CBOE and S&P](Charts/9-11%20Recession/9_11_CBOE_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

### b. The 2008 Recession <a name="2008"></a>

![Great Recession Equity Sectors](Charts/Great%20Recession/Great_Sectors.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![Great Recession TNX and S&P](Charts/Great%20Recession/Great_TNX_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![Great Recession Gold and S&P](Charts/Great%20Recession/Great_Gold_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![Great Recession USD and S&P](Charts/Great%20Recession/Great_USD_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![Great Recession CBOE and S&P](Charts/Great%20Recession/Great_CBOE_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

### c. The 2020 Recession <a name="2020"></a>

![COVID-19 Recession Equity Sectors](Charts/COVID%20Recession/COVID_Sectors.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![COVID-19 Recession TNX and S&P](Charts/COVID%20Recession/COVID_TNX_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![COVID-19 Recession Gold and S&P](Charts/COVID%20Recession/COVID_Gold_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![COVID-19 Recession USD and S&P](Charts/COVID%20Recession/COVID_USD_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

![COVID-19Recession CBOE and S&P](Charts/COVID%20Recession/COVID_CBOE_S%26P.png)
<p>&nbsp;</p>
<p>&nbsp;</p>

## 3. Conclusions and Key Findings <a name="Findings"></a>

## 4. Project Operations <a name="Operations"></a>

### a. Data Collection and Cleanup <a name="Data"></a>

### b. Approach <a name="Approach"></a>

### c. Data Sources <a name="Sources"></a>

1. Yahoo Finance (https://finance.yahoo.com/)
2. Crude Oil Historical (https://www.investing.com/commodities/crude-oil-historical-data)
3. Economic Data (https://www.bankrate.com/banking/federal-reserve/economic-indicator-survey-recession-risks-january-2023/)
4. Sector ETFs (https://www.cnbc.com/sector-etfs/)
5. Gold Historical (https://data.nasdaq.com/data/LBMA/GOLD-gold-price-london-fixing)
6. Past Recessions Overview (https://www.forbes.com/advisor/investing/how-long-do-recessions-last/)
7. Recession Definition (https://www.rba.gov.au/education/resources/explainers/recession.html)
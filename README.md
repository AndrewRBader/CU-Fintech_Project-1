# Project 1: Analysis of Asset Performance in a Recession

Code developed by Andrew Bader, Evelyn Nazginov, Kunal Srinivasan, and Max Accurso

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

The 2001 recession, lasting from March to November, was one of the mildest on record and followed the longest economic expansion in U.S. history. The Federal Reserve played a crucial role in mitigating the recession by raising and later cutting the fed funds rate. By mid-2003, the benchmark rate reached a low of 1%. The dot-com bubble bust was the main cause of the recession, triggered by a boom in the dot-com industry partly fueled by Y2K concerns. Companies invested heavily in new software, leading to significant overvaluation and failure of many dot-com businesses. The 9/11 attacks added to the economic turmoil and resulted in two quarters of contraction, with the economy contracting by -1.3% in Q1 and -1.6% in Q3. Unemployment continued to rise, peaking at 6.3% in June 2003.

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

The Great Recession was a major economic downturn that impacted the world from 2007 to 2009, becoming the longest period of contraction since the Great Depression. The subprime mortgage market was the trigger for the crisis which quickly spread to the global banking sector. The widespread use of derivatives worsened the situation, as evidenced by a decrease in GDP over three consecutive quarters in 2008, with an 8.5% drop in the final quarter. Unemployment rose to 10% in October 2009, following the end of the recession. The recovery began in the third quarter of 2009, thanks to the American Recovery and Reinvestment Act, which boosted GDP. The recession caused a global financial crisis and bear market in stocks, becoming the most severe economic downturn since the 1937-38 recession. The inflow of global investment into the U.S. may have played a role in unethical practices in the mortgage market, while the fluctuations in oil prices caused a depression in the U.S. oil industry.

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

The year 2020 was marked by one of the most severe economic downturns since the Great Depression. To combat this, the Federal Reserve stepped in, reducing the fed funds rate to nearly 0% in March. The government also offered substantial financial aid in the form of billions of dollars. The U.S. economy experienced a record contraction of 31.2% in Q2, following a 5.1% decrease in the preceding quarter. This resulted in an unprecedented loss of 20.5 million jobs in April, causing the unemployment rate to surge to 14.7%, remaining in double digits until August. The COVID-19 pandemic also caused a great deal of uncertainty, leading to a stock market crash. Although the economy did recover to some extent, with a growth of 33.8% in Q3, it was not enough to fully offset the earlier losses. The federal funds rate remained near zero until March 2022.

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

The US economy has experienced 11 recessions since 1948, averaging to approximately one recession every six years. Nevertheless, economic growth can vary greatly in length, with some lasting as short as a year and others spanning a decade. Historically, recessions have lasted an average of 11 months, with the Great Recession of 2008 lasting 18 months and the 2020 recession being the shortest on record, lasting just two months.

Why do we study recessions if they are relatively rare events?

Every recession is unique in its own way, and experts have been attempting for decades to uncover the underlying indicators that may signal their onset. However, the COVID-19 pandemic created a recessionary environment that was completely unexpected, leaving many experts struggling for answers. While we may not be able to predict the exact timing of a recession, our goal is to be as prepared as possible. Recessions can wipe out significant amounts of wealth and value in a short period of time, so it's important to understand which sectors and securities to avoid and which to consider during economic downturns.

Our group reached our conclusions by analyzing three metrics: the steepest decline within the timeframe, the percentage change from the start to finish, and the recovery time in days to pre-recession levels. We created two types of charts to visualize this data: a line chart of equity sectors to show their relative movement during a recession, and scatter plots to reveal the relationships between the stock market, gold, the US dollar, bonds, and volatility index.

Let's first examine the scatter plots for any correlations that may have emerged. Our analysis revealed consistent relationships between two of the four data points across all three recessionary periods. The 10-Year Treasury Yield and the S&P 500 consistently exhibited a strong positive correlation during recessions, while the CBOE Volatility Index and the S&P 500 showed a strong negative correlation. This suggests that bonds and stocks tend to move in tandem during economic downturns and that investors can expect similar returns from both markets during recessions.

The CBOE Volatility Index, or VIX, is a real-time market index that reflects market expectations for volatility in the next 30 days. Investors use the VIX to gauge the level of risk, fear, or stress in the market when making investment decisions, which is why it has an inverse relationship with the stock market. As stock prices drop, investor worries increase and the volatility index spikes.

The relationship between the US dollar and the S&P 500 during the 2001 recession was different compared to more recent recessions. In 2001, the US dollar and the S&P 500 showed a positive relationship, however, this relationship has become negative in recent years. This can be attributed to foreign investment, as more investors put their money into US equities, they first need to buy US dollars to purchase American stocks, causing both indexes to increase in value.

The most intriguing relationship is between gold and the stock market. During periods when the S&P 500 is in the lower half of its value, there is a positive relationship between the index and gold. However, as the S&P 500 approaches its median value, an inflection point occurs and the relationship turns negative as the S&P 500 continues to rise. Investors prefer the higher returns of the S&P 500 over the stability of gold during economic expansion, causing this shift in the relationship.

Now let's examine how individual sectors perform during economic recessions. By using three metrics, we have identified the best and worst performers. Although all sectors tend to move in a similar fashion during a recession, we have singled out those that should be avoided and those that are considered safe bets.

Avoid: The oil futures sector was the biggest red flag due to its steepest decline and overall percentage change, with an average 60% drop from peak to trough. The second and third riskiest sectors, finance and energy, saw an average decline of 12% lower than oil. These three sectors comprised the bottom 25% of performers and had a slower time to recovery compared to others.

Longest to Recover: The sectors that took the longest to return to pre-recession levels were utilities, tech, and finance, with an average recovery time of over 1000 days.

Winners: Of all the sectors, only two assets showed positive overall change during a recession - gold and the US dollar. The healthcare sector emerged as the least risky and most stable option of the equities, with a negative 30% steepest decline but only a 10.7% decrease overall in each recession. Healthcare also had the quickest recovery time amongst its ETF peers, at an average of 564 days. Gold and the US dollar were the clear favorites during economic downturns, with gold averaging a 10% growth rate and the US dollar averaging 3.7% growth over the past three recessions. These two assets also had the shortest recovery time, averaging around 315 days.

In conclusion, our analysis of three recessions between 2001 and 2020 reveals that there are consistent relationships between certain metrics during economic downturns. The 10-Year Treasury Yield and the S&P 500 tend to move in tandem, the CBOE Volatility Index and the S&P 500 have a strong inverse relationship, and gold and the S&P 500 have an inflection point relationship that changes as the S&P 500 approaches its median value. Our examination of the different equity sectors revealed that the oil futures sector is the riskiest and the healthcare sector is the least risky. Gold and the US dollar emerged as the clear favorites during recessions with the quickest recovery times and positive overall change. Investors can use these findings to make informed investment decisions during economic downturns.

## 4. Project Operations <a name="Operations"></a>

### a. Data Collection and Cleanup <a name="Data"></a>

From the raw csvs, pandas read_csv function was used to import the data. The index column was set to the first data column of each csv. Dates were parsed and standardized amongst each data set using pandas' csv functions. The axis column was renamed and standardized across data sets for ease of concatination, joining, and subsequent analysis. Each file required specific cleaning algorithms. For data files with commas and dashes, looping algorithms were used to go through each column and remove commas and dashes. These looping algorithms were also used to convert the imported string data into floats for subsequent analysis. The pandas .head function was used to visualize columns of the data as they were processed to check correctness of the data and columns. Column renaming functions were used accross data sets in order to standardize and ease analysis and data manipulation. Each set of data was plotted using hvplot in order to check "plotability" before moving on to futher manipulation and analysis. The to_csv pandas function was then used to save the resultant cleaned data as csvs in a directory with a specified path.

### b. Approach <a name="Approach"></a>

Cleaned csv files were converted into pandas dataframe using a for-loop and a python dictionary for automation. Automated code was customized to account for file level differences in formats (eg. the csv for gold index contained only two columns of data as opposed to six in others). Additionally the code was parametrized which allowed for it to be used systematically across all recession periods by simple adjustments of the parameters. 

Resulting dataframes were concatenated to create the master data for analysis of a given period of recession. Pandas `corr` function was used to create a correlation matrix. `hvplot` was used to generate several visualizations for review and analysis. Separate codes were created to build algorithms for calculation of key metrices like steepest decline, overall decline and days to recovery calculations.

The technologies used include:

- Python: the sole development language of the analysis
- pathlib library: to access and import csv files for various processes
- hvplot: for plotting interactive and informative plots
- pandas: for key functions and data manipulation as needed throughout the analysis and processing
- git and github: for local and external version control as well as data storage
- numpy: library was used for data manipulation, analytics and processing

Tasks: 
- **Andrew Bader**: Cleaning data and processing for analysis,setting up github version control
- **Kunal Srinivasan**: Data manipulation, processing and recession analysis
- **Max Accurso**: Project ideation, data collection, recession analysis, Readme
- **Evelyn Nazginov**: Recession analysis and power point presentation

Challenges:
- Finding complete and matching data sets
- managing version control
- developing meaningful analytics and corresponding processing algorithms
- cleaning the data with appropriate algorithms
- assymetric data structure resulted in process errors when the code was deployed for recession periods other than on which it was built

Successes:
- Developed a number of interesting plots describing our findings and analysis
- Found complete sets of data for all desired assets which were successfully cleaned for analysis
- Parametrized code design allowed different users to use the master code uniformly with simple parameters changes 
- Came up with interesting observations and analyses

### c. Data Sources <a name="Sources"></a>

1. Yahoo Finance (https://finance.yahoo.com/)
2. Crude Oil Historical (https://www.investing.com/commodities/crude-oil-historical-data)
3. Sector ETFs (https://www.cnbc.com/sector-etfs/)
4. Gold Historical (https://data.nasdaq.com/data/LBMA/GOLD-gold-price-london-fixing)
5. Past Recessions Overview (https://www.forbes.com/advisor/investing/how-long-do-recessions-last/)
6. Recession Definition (https://www.rba.gov.au/education/resources/explainers/recession.html)
7. Economic Data (https://www.bankrate.com/banking/federal-reserve/economic-indicator-survey-recession-risks-january-2023/)

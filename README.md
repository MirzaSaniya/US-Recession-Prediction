# US-Recession-Prediction


I have formulated my hypothesis for analysis as **whether the US Economy is leading towards a recession**? For this I have identified variables which I feel are good indicators for this study, they are:

S&P 500 (SPY) is a US stock market index that measures the stock performance of 500 large companies listed on the US stock exchanges. It reflects the health of the US stock market and is one of the most commonly followed equity indices in US.

Truck Tonnage Index (TRUCKD11) measures the gross tonnage of freight which is transported by motor carriers in the US. The index serves as an indicator of shipping activity and consumption of goods in the US. Analysts also use the truck tonnage index to determine the state of the US economy as over 70% of all freight tonnage is via truck.
Simple Moving Average (SMA) is an arithmetic moving average calculated by adding recent closing prices of a security and then dividing that by the number of time periods in the calculation average. We do this by pandas rolling method to compute moving averagesFor analysis, SMAs works as a technical indicator to determine the trend of the price of the security. It is used as an analytical tool to identify if there will be an increase or reverse a bull or bear trend. If the SMA is moving up, the trend is up. If the SMA is moving down, the trend is down.

Shorter period SMAs like, 20 Day SMA or 50 Day SMA can be used to determine the shorter term trends. Whereas 200 days SMA has a smoother S&P 500 data which is a good indicator for the long term trend.

Yield Curve or the 10-Year Treasury Constant Maturity Minus 2-Year Treasury Constant Maturity (T10Y2Y) - It is the difference between the yield on 10-year and 2-year US government bonds

Cyclically Adjusted Price-to-Earnings ratio (CAPE) or Shiller P/E - It is a valuation measure usually applied to the US S&P 500 equity market. It is defined as price divided by the average of ten years of earnings (moving average), adjusted for inflation. It is used to gauge whether a stock is undervalued or overvalued by comparing its current market price to its inflation adjusted historical earnings record

Unemployment Rate (UNRATE)- In the last two recessions we witnessed that during recession there was a peak in the rate of unemployed people, which is a factor in the decline of an economy

Gross Domestic Product GDP- It reflects the economic health of an economy as it displays the total goods and services produced in an economy in a financial year

Recession Talks - Through Google Trends we can however see an increase of panick in the US consumers and investors as there have been a lot of talks going on about recession in this year


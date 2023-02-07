# Final-Project-Tableau

## Project/Goals
- Analyse the trend of house prices across Canada in the last 40 years (table housing_price_index).
- Compare the trend after 2005 with actual benchmark prices in table real_estate_prices to see if there are any differences.
- Compare this trend with the trend of office prices. Which one is getting more expensive, faster?
- Create a heatmap of Canada with current house prices for each available district.
- Are the price differences between different districts increasing?
- Compare the trend of house prices with earnings. *In case you want to plot monthly salary, be aware that the earnings value is per week.
- Did people spend more of their earnings in 2014 than they did in 2001?
- There were several economic crises in the world in the last 40 years, including these four: Black Monday (1987), Recession (early 1990s), dot com bubble (2000 - 2002), Financial crisis (2007 - 2009). Show the effect of these crises on:
  - Earnings
  - House prices
  - Office prices
  - House constructions
  - Consumer index
- Plot consumer_index together with housing_price_index and fit the regression line between them. Can we predict consumer_index from the housing_price_index?
- Try to find an interesting pattern, trend, outlier, etc. from the data used in the above questions.
  - HINT : Double check all units in the table before any comparison.

## Process


## Results
In the first part, I analyzed the real estate prices across Canada for last 40 years. The regression line indicates that the prices have consistently increased over the period of time but really spiked after 2020. Apart from trend, I also looked at seasonality and found that the market is seasonal with Q3 being slow quarter. I would have imagined Q4 to be slower.

In the next part, I compared the House Price index with actual benchmark prices. The composite HPI & actual prices are in trend for the range but after 2015 there is a sharp uptick in actual benchmark prices indicating a disconnect.

I then compared the residential and commercial office prices. They follow similar trend over period of time but the regression line indicates that commercial real estate had slightly better returns till 2017.

After this I combined the multiple tabs from real estate price excel using Tableau’s union feature & cleaned the area names. I looked at Sept 2020 for latest numbers. The heat map indicates Oakville Milton, Greater Vancouver and Lower Mainland has highest prices.

I then looked at the prices for all geographies over time and identified that the price increases are not consistent over period of time. Some areas such as Oakville Milton have provided better returns that others.

I also looked into relation between the earnings and house prices for the timeframe between 2005 to 2015. During this time, the income increased but the house prices did not increase as much resulting in income to price ratio to drop from 40% to 30% range.


## Challenges 
Joining the data across multiple datasets as date was the only joining key. The date formats were different plus the data ranges were different creating a challenge for join.
JSON file with earning data was difficult to parse using Tableau.

## Future Goals
Spend more time trying advanced visualizations

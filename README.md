# Magnificent-7 (M7) stocks analysis-volatility, trend and COVID-19 impact

Magnificent 7 comprises the 7 most influential technology stocks which are Apple, Microsoft, Google, Amazon, Nvidia, Meta and Tesla. The term was first used by Bank of America analyst Michael Hartnett to describe these stocks(1). These stocks have provided high returns and have become investor’s favorites in recent years(2). However, there are certain risks associated with these stocks such as overvaluation, future uncertainties, economic risks and regulations (3)(4). Hence, these risks and rewards need to be studied well for a secure investment. Although the past performance of a stock may not accurately predict how it will perform in the future, analyzing its trend, volatility and how it sustained in an adverse time can provide insights into these stock’s risks, rewards and resilience. In this report, I have analyzed the year-wise growth, monthly, quarterly and weekly trends and COVID-19 impact on these Magnificent 7 stocks.

The data for the analysis was obtained from Kaggle(5). The data includes the information on volume and open, close, high, low and adjusted close prices of these M7 stocks from 01/01/2013 to 12/29/2022. The data was analyzed on tableau public. The COVID impact dates were categorized as pre-COVID (2013/1/1-02/02/2020), COVID (02/02/2020-04/01/2022) and post-COVID (04/01/2022-12/29/2022). The category was based on an article on COVID-19 recession in Wikipedia where it is described that COVID 19 recession began in February 2020 and recovery began is April 2022 (6). 

The analysis is summarized on tableau dashboards and the story that can be found at:

https://public.tableau.com/app/profile/laxmi.dhungel/viz/Magnificient7_stock_analysis_Laxmi/M7story

**Results**

**Magnificent 7 stock analysis (overall)**

The screenshot of the report is provided below. The dashboard contains filters for the year and company. Selecting ALL will provide results for all the years combined and all the M7 companies. If interested in a particular year or company, then the filter can be used accordingly.

https://public.tableau.com/app/profile/laxmi.dhungel/viz/M7_overallanalysis/Magnificient7stockanalysis


![Magnificient 7 stock analysis](https://github.com/user-attachments/assets/1d5eaf0f-b46f-4176-b08e-4e4c3d011b65)


Figure 1 in this dashboard describes the highest (bar) and lowest (star) prices for each company throughout the years (2013-2022). Among M7 stocks, Tesla had the highest ($414.50) and lowest ($2.14) open prices. The maximum open price ($152.10) was the lowest for Google (Figure 1). The average open ($155.54) and close ($155.58) price was highest for Meta whereas lowest for Google (open-$59.30, close-$59.32) (Figure 2). Apple (171.35 M) had the highest average volume whereas Meta (29.76 M) had the lowest average volume (Figure 3). 

Figure 4 shows the percentage change in the average open price for each year compared to average open price in 2013. Nvidia had the highest growth (open price change >5000%) followed by Tesla (>3600%). Although Meta had good growth until 2021 (805.21%), it sharply declined in 2022 bringing its price change to 408.05% compared to average open price in 2013. Meta ranked lowest for price change compared to the average open price in 2013. Except for Apple and Tesla, there was a negative growth (open prices) in 2022 compared to 2021. 

Figure 5 shows the volatility of stocks. In this case, volatility is determined based on the maximum change in price (High-low) that occurred in a day for each stock (represented by a bar graph). The line graph represents the maximum percentage change in close price compared to the open price for each stock. Tesla showed the highest volatility with a maximum price change of 23.08% in a day whereas Google was the least volatile. The price change (%) in open and close prices was also highest for Tesla and lowest for Google. 

Calculation 

•	The percentage fluctuation in high-low price:

(([High]-[Low])/(([High]+[Low])/2))*100

•	The percentage change in open-close price:

(([Close]-[Open])/[Open])*100

Figure 6 shows year-wise growth (% change compared to the previous year) for each M7 stock. The maximum growth occurred for Tesla in 2020 (429.4%). The highest negative growth occurred for Meta in 2022 (-43.9%). Except for Apple and Tesla, the growth was negative in 2022 for the remaining stocks. Tesla had negative growth in 2016 (-8.6%) and 2019 (-13.9%). Apple had negative growth in 2016 (-13.04%).  Nvidia had negative growth in 2019 (-25%) and 2022 (-4.8%). The remaining stocks had negative growth only in 2022. **This suggests 2022 to be the worst year for these stocks in terms of yearly growth. Further, these stock prices increased for most of the year suggesting they were a good investment.**


**COVID 19 impact on M7**

The dates were categorized as pre-COVID, COVID and post-COVID based on the time when COVID recession and recovery started. The dashboard contains filters for company and COVID-19 impact time. 

https://public.tableau.com/app/profile/laxmi.dhungel/viz/M7stocks_covidimpact/Covidimpact_M7


![Covid impact _M7](https://github.com/user-attachments/assets/6d4a72c8-2e20-436d-9073-0f21bb38b791)


On average, there was higher volatility (High-low price change % in a day) during post-COVID time (3.72%). However, maximum volatility (23.08%) was recorded during COVID time. The average open price increased for all the M7 stocks in COVID time compared to pre-COVID time. Except for Amazon and Meta, the stock prices increased for the remaining stocks in post-COVID time compared to COVID time (Figure 7). 
Figure 8 (Heatmap) shows the change in average volume during COVID time and post-COVID time compared to the previous era. The average volume decreased for Apple, Google, Meta and Nvidia during COVID time compared to pre-COVID time. However, the average volume increased for Tesla during this time. The average volume for Microsoft (1.07%) and Amazon (3.41%) were similar during COVID and pre-COVID time. However, during post-COVID time the average volume decreased for Amazon, Apple, Google, Microsoft and Tesla but increased for Meta and Nvidia. 

Figure 9 shows the percentage change in closed price compared to the open price for different COVID impact dates. The Gnatt bar represents the average percentage change for each stock whereas different shapes represent maximum percentage change. The average percentage change in the close price compared to open price was negative for Amazon for all COVID impact times. **This suggests that on average the close price was lower than the open price for Amazon. During pre-COVID and COVID time, the remaining stocks had higher close prices than the open price on average.** During post-COVID time, the average change in close price percentage compared to open price was negative for Amazon, Google, Microsoft and Tesla whereas it was positive for Apple, Meta and Nvidia. Tesla had the highest decline (0.49%) in close price compared to the open price on average during the post-COVID time. The maximum percentage change in close price compared to open price was seen in COVID time for Meta, Microsoft, Nvidia and Tesla whereas it was seen in pre-COVID time for Amazon and Apple. Google had a maximum percentage change in close price compared to open price during post-COVID time. 

Figure 10. shows the maximum and average price change (High-low %) in a day during different COVID impact dates. The average price change in a day was highest in post-COVID time for all the M7 stocks. The average price change in a day was the highest for Tesla in all the COVID impact times (pre, COVID and post). The average price change in a day was lowest for Microsoft in post-COVID time (2.62%) whereas it was lowest for Google in pre-COVID (1.66%) and COVID time (2.28%). The highest price change in a day occurred for Tesla in COVID time (23.08%). The maximum price change in a day occurred during pre-COVID time for most of the stocks except for Tesla and Microsoft. For Microsoft, the maximum price change occurred in COVID time. **This result suggests Tesla to be the most volatile stock whereas Google and Microsoft to be the least volatile stock. The highest volatility was observed during post-COVID time**. 



**M7 Trend**

This dashboard contains filters for the company and the COVID impact date. The filter for COVID impact date is set for pre-COVID time, however, it can be changed according to your interest. In this report, the monthly, quarterly and weekly trends will be described for pre-COVID time to prevent COVID-related bias on the trends. 


https://public.tableau.com/app/profile/laxmi.dhungel/viz/M7trend/Trend_M7


![Trend_M7](https://github.com/user-attachments/assets/2c7d0bc7-32e5-4263-90ba-e28b0bd0a817)

**Monthly trend**

Figure 11 shows the percentage change in open price (Average) compared to the previous month. Overall (ALL filter), the highest decline in average open price occurred during February (-12.76%) whereas the highest increase occurred during May (4.78%). The study on individual stocks also showed a similar pattern of the highest percentage decline in February. However, the highest percentage increase varied among stocks (May (Amazon, Meta), June (Tesla), August (Apple, Google, Nvidia), and November (Microsoft)). This suggests that stock prices go down during February and rise higher during the summer months.

Figure 12. shows the percentage change in open price (Average) in each month compared to prices in January. Overall, the prices were lowest in February and highest in November. The trend for the lowest price applied to all the individual companies, however, the trend for the highest price was in December for Tesla, Microsoft and Google. 

**Note: Figures 11 and 12 should not be confused. Figure 11 compares the price between the current month and the previous month whereas Figure 12 compares the price of each month with the price in January. For example, if a stock had a $10 open price in January, then the highest price in that year occurred in November (5.48% increase) with the stock price being $10.548 in the month. However, the stock price reached $9.9 in April (-9.87% compared to January) and jumped the highest (4.78%) to reach $9.95 in May. The trend has its significance based on the type of investment (short-term or long-term). The short-term investor may benefit by investing a month before the highest jump in the price whereas the long-term investor may benefit by investing a month with the lowest price in a year. 
**


Overall, the highest volume was in January and the highest volatility (high-low price fluctuation %) was seen in February. Individual stocks showed a similar trend for the highest volume (Except Google (Feb), Nvidia (Feb) and Tesla (May)). The highest volatility was seen in January for Apple and Meta, May for Tesla, October for Google and December for Microsoft. For most of the stocks, the month with the highest volume had the highest volatility (except Microsoft, Google and Amazon) (Figure 15). 

**Quarterly trend**

Overall, the average open price increased with each quarter. The highest increase in the price was observed in quarter 3 (Q3) (Figure 13). The study on individual stocks showed that average open (bar) and close (star) prices decreased for Apple, Google, Nvidia and Tesla in quarter 2 (Q2). The overall trend of the highest increase in average open and close price applied for Amazon, Google, Nvidia and Tesla. However, Apple and Microsoft had the highest increase in Q4. Overall, volume decreased each quarter. And the price fluctuation was highest in Q1. However, Nvidia had the highest price fluctuation in Q4. The highest volume and price fluctuation was in Q2 for Tesla.

**_Weekly trend_**

Overall, the average open and close price decreased on Tuesday and Wednesday and increased on Thursday and Friday. The prices were lowest on Wednesday and highest on Friday. The open and close price trend of individual stock is summarized in heatmaps below (Figure 18 and 19). Some stocks had a slight increase in open price (Apple, Meta and Nvidia) and close price on Tuesday (Meta, Nvidia). Microsoft had a decrease in open and close prices on Thursday. Tesla had the highest close price on Thursday.

![open price percentage change](https://github.com/user-attachments/assets/06ff0a8b-463b-478d-9db8-fb218fe4415b)

Figure 18. Change in open price (%). Monday is considered the baseline price. Green color represent increase in price whereas red color represents a decrease in price.

![close price percentage change](https://github.com/user-attachments/assets/4fe3ad4b-9eff-4acf-8394-fa5afd0c0d1a)

Figure 19. Change in close price (%). Monday is considered the baseline price. Green color represent increase in price whereas red color represents a decrease in price.


Overall, the volume was highest on Friday and lowest on Tuesday. The volatility was highest on Monday and lowest on Friday. The highest volume on Friday applied for all the stocks (Except Apple (Wednesday), Meta (Thursday) and Tesla (Thursday)). The individual stocks showed a similar trend for volatility (Except Meta, Microsoft and Nvidia). Meta showed the highest volatility on Thursday and the lowest on Friday. Microsoft showed the highest volatility on Friday and the lowest on Tuesday. Nvidia had the highest volatility on Monday and the lowest on Tuesday. 

**Note: (Overall- ALL filters have been used. It provides the average values of all the stocks).** 



**Conclusion**

Based on the growth of stocks, M7 seems a good investment as all the stocks have returned high profits. Tesla is the most volatile and has the greatest risk and reward. Google is the most stable M7 stock, however, has lower growth compared to other M7 stocks (Except Meta). There are negative growths in some years for some of these stocks, however, these stocks have fought these odds and have grown in the long run suggesting a good long-term investment. Despite being an adverse time these stocks performed well during COVID time. Rather, the performance declined, and the volatility was higher in post-COVID time. This suggests that a crisis may not accurately predict stock performances. Sometimes, it may present an opportunity for investors. The stock price was the lowest in February. For a long-term investor, this month may be the best time to invest. However, the prices jumped highest in May. So, short-term investors can invest in April to get the profit from the highest jump in prices. The highest increase in price occurred in Quarter 2. Further, stock prices were the most volatile on Monday. The price was lowest on Wednesday and highest on Friday. These trends can be utilized by short-term investors to get the maximum profits from these stocks. The highest jump in price varied with stocks, hence the company may need to be filtered in the story/dashboard to understand the best month/quarter/days to invest.


**Limitation**


The data ranged from 01-01-2013 to 12-29-2022. The post-COVID time included time after 04-01-2022. Thus, this may not exactly represent a post-COVID time (years) but would represent an initial stage of the recovery. Further, this report provides an analysis of the past performance of these M7 stocks, however past performance does not always accurately predict future performance. However, these stocks have overcome past challenges and grown suggesting higher resilience. 


References
1.	Duggan W, Schultz J. https://money.usnews.com/investing/articles/magnificent-7-stocks-explainer. Magnificent 7 Stocks: What Are They and How They Dominate the Market. 
2.	Mitra M. https://www.wsj.com/buyside/personal-finance/investing/magnificent-7-stocks. What Are the Magnificent Seven Stocks? 
3.	Sebastian A. https://www.thetimes.com/money-mentor/investing/magnificent-seven-stocks. The Magnificent Seven stocks: Still a great opportunity or overpriced and set to fall? 
4.	Pendola R, Curcio P, Tony D. https://www.cnn.com/cnn-underscored/money/magnificent-7-stocks. What are the Magnificent 7 stocks? 
5.	https://www.kaggle.com/datasets/kane6543/most-watched-stocks-of-past-decade20132023?resource=download [Internet]. Most Watched Stocks of Past Decade(2013-2023). 
6.	Wikipedia. https://en.wikipedia.org/wiki/COVID-19_recession. COVID-19 recession. 
 








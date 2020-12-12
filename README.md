# Oil Price Comparison Between COVID-19 and the Crash of 2008
 by Tom Synoground, Kian Ankerson, Zach Fechko, and Elliot Kimsey
## Interest in Topic
We are living in a time of a pandemic that has vastly changed the way our society functions and we lived through the Crash of 2008, so it is interesting to look at other big impacts of these big events. Especially as we are older now and more aware of the economy, it is more interesting to look at how this compares to 2008. 
## Motivating Questions
- How is the crash of 2008 similar to what is happening due to the Coronavirus?  

- What similarities do we see between Oil Prices and the value of Stocks? 

- How does the recovery from the economic impact of COVID compare to the recovery from the 2008 economic crisis?
## Data Process
We downloaded our Oil Price data from (https://www.eia.gov/dnav/pet/pet_pri_gnd_a_epm0_pte_dpgal_w.htm ). We used the data for Price of Oil per Gallon every week from April of 1993 to November 2020. We averaged the data from the East Coast, West Coast and MidWest in the USA to get a good representation of the data. 
We got our Stock Price data from We downloaded our Oil Price data from (https://finance.yahoo.com/quote/%5EGSPC/history/) and used the same time intervals as the Oil data.  

We then cleaned the data in Excel, which just consisted of deleting a few useless rows that did not contain data. Then we converted those files into cleaned up csv’s.  

We imported the csv’s into Python and graphed line plots based on the Average Oil Price of the three regions, and graphed the Stock Prices. We also changed the x and y bounds and made graphs of both Oil and Stocks zoomed in on the Crash of 2008 and the Crash due to COVID-19.

Finally, we cleaned up the x-axes, as the measurements of time were the same units. Then we added labels to the main graphs and added some helpful points of interest. 

We decided that we also wanted to take closer look at the time periods when those large price drops occured, so we could compare their relative drop in price, and how they compared Oil compared to Stocks in that aspect. I used our previous graphs and changed the x and y limits to change our window of view on the data. 

## Analyses and Conclusions
In our analysis we looked at how bad the price crashed in 2008 and 2020 for both the price of Oil Per Gallon in the United States and the price of the S&P 500 market index fund. To do this, we used Excel to locate the highs and low points for the time of each crash.  


For the oil crash in 2008, we used price data from March 2007 to June 2009 and found the highest was  ~$4.24 per gallon before the crash, and the lowest was ~$1.72, during the crash. In 2020, for the period of time from November 2019 to November 2020, we found the highest was ~$2.91 before the crash and the lowest was ~$1.99 during the crash. It’s important to note that before the big oil crash in 2020 from the COVID-19 Pandemic, Oil prices were already decreasing slightly. 


<table> <tr><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/Oil%20Price%20Visualization.png"></td><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/Stocks%20Visualization.png"></td></tr> <tr><td>Timeline of Oil Price (Per Gallon) in the United States</td><td>Timeline of Stock Price in the United States</td></tr> </table>

We did very similar steps in finding the high and low points for the stock price of the S&P 500 during the same time periods. Again using Excel, we found the S&P 500 reached a high of $1565.15 before the crash in 2008, and hit a low of $676.53 during the crash. Before the COVID pandemic in 2020, the highest price of the S&P500 was $3638.35 and during the lowest price was $2237.40. 

Using these numbers we calculated the relative price drops in order to determine the actual severity of both market crashes. After finding the relative price crash percentage, we saw that the market crash in 2008 for both the stock numbers (S&P 500) and Oil prices were worse than the more recent crash in 2020. In 2008 the S&P 500 dropped 56.78% and oil dropped 59.43%, while in 2020 the S&P 500 dropped 38.50% and oil prices fell 31.61%.


<table> <tr><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/ComparisonS%26P500.png"></td><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/ComparisonOil.png"></td></tr> <tr><td>Price Drop Comparison of Stocks in 2008 vs 2020</td><td>Price Drop Comparison of Oil in 2008 vs 2020</td></tr> </table> 

An interesting thing here to note is that while the crash of oil prices was relatively worse in 2008 than 2020, if you account for inflation, the lowest price of oil in 2020 was lower than its worse during the 2008, while doing the same for the S&P 500 was did not show the same behavior. According to the [Bureau of Labor Statistics Inflation Calculator](https://www.bls.gov/data/inflation_calculator.htm) after plugging in the months each low was hit during, we see $1 in December 2008 is equivalent to $1.22 in April 2020. Using these to account for inflation tells us that the worst oil prices in 2020 were almost 10 cents worse than in 2008 ($1.72 2008 and $1.63 in 2020 after reversing inflation).

Taking a closer look at the data, we can see how both the Oil Price and the Stock Price drops vary in each year. We can see for Oil, in both 2008 and 2020 it drops to about 2 dollars a Gallon, but in 2008 it starts at a much higher price before the crash happened. For the Stock market, we notice that the overall price is higher in 2020, but the relative drop we see is larger in 2008 than it is in 2020.

 <table> <tr><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/Oil08Zoomed.png"></td><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/OIL2020Zoomed.png"></td><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/Stocks08Zoomed.png"></td><td><img src="https://github.com/Tomsyno/Data115_Group_Project_Oil_Price_comparison_between_Covid_and_2008/blob/main/Stocks2020Zoomed.png"></td></tr> <tr><td>Oil Price Drop in 2008</td><td>Oil Price Drop in 2020</td><td>Stock Price Drop in 2008</td><td>Stock Price Drop in 2020</td></tr> </table>

It is interesting to look at the Graphs from 1993 to Present, and see just how good of a job they do at showing us when major events in the United States occured. They tell parts of our country's history and can be explained by looking at the data. 

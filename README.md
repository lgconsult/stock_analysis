# stock_analysis

##Overview
The purpose of this project is to analyze a group of stocks based on total daily value and the return. We will refactor our code so that it loops through the data only once to collect the same information, in preparation to use it on a larger data set.

##Results
While my code was able to run faster than the previous code used, I was not able to solve all of the bugging errors to populate the results. I could either run my code and it wouldn't populate the results, or I kept getting an Overflow error in my line of code that calculates the stocks' return.
![error message](https://github.com/lgconsult/stock_analysis/blob/main/error%20message.png)
I spent a significant amount of time trying to debug my code (about 10 hours) including speaking with a Learning Assistant who told me to submit as is. 
The previous code I used also started showing this "Overflow" error message, although I believe the 2018 and 2017 results were calculated correctly. 
![2017 results](https://github.com/lgconsult/stock_analysis/blob/main/2017%20Stock%20Performance.png)
![2018 resuts](https://github.com/lgconsult/stock_analysis/blob/main/2018%20Stock%20Performance.png)
When comparing the results, 2017 was a far better year for returns thans 2018, with all but one stock performing positively. Some tickers even gained over 100% of their value, including your client's parent's stock, DQ, which gained 199.4% in 2017. However, comparing these results to 2018, these stocks seem anything but stable. Only two companies posted positive results in 2018, and many lost double digit percentages, including your client's parent's stock, DQ, which lost -62.6%. These stocks all seem heavily volatile, I would want to look at them over a longer range of time, and in comparison to factors such as energy policy changes (including tax incentives, dicentives for renewables and oil), ecnonomic indicators (including growth and inflation) and market indicators (such as market saturation, commodity prices) to further contextualize the differences in return and volume year over year. There doesn't seem to be much of a correlation between total daily volume and return, and since these are calculated over one year, I did not assume total daily volume would correlate to any factor. If we looked at total daily volume by day, and compared this to the daily price, I bet we might see a closer correlation, or possibly once where an increased number of shares traded per day could merely indicate movement in price, whether it is up or down.

##Summary
One of the main advantages of refactoring code is that it can speed up your processing time when processnig large amounts of data. Another advantage is that refactoring can make reading your code easier as well. The main disadvantage to refactoring code is that it takes more time to write because of its' increased difficulty.
I would have loved to been able to get this code to work and am planning on still working on it. I want it to work because I see it as so beneficial- It would be a tremendous resource to be able to apply this code to other stock lists, or even broader sector categories of the stock market. I hope that once I have more time (the largest drawback to refactoring), I will be able to refactor it properly.

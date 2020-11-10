# Fall of retail shopping, rise of technology stocks? 

## Purpose 
The purpose of this project was to put to practice skills that we have learned through Georgia Tech's Data Analytics bootcamp. We use Python, Matplotlip, Pandas, and API calls to collect, clean and viusalize data

Our group is looking at how the current pandemic, and the overall shift to technology has affected the stock market. There has been a recent trend of retail stores closing, and with the current status where many stores can't open, one could make the assumption that companies that have a stronger base in technology will have a stronger chance of having success. We tie this to the stock market with the idea that people are going to want to bye stocks in companies that are going to succeed, and businesses that might be slowed in uncertain times might scare off investors. 

The thesis is that the technology sector will see the greatest increase and the retail stores in the consumer staples secotr will see the greatest decrease. To test this we chose the top 20 companies in the following sectors based on market cap: technology, consumer staples, financials, real estate, healthcare. We capped it at 20 to ensure that these were well established companies and a less chance of having outliers having an impact on the data. We are looking at the stock data at the begining of each quarter from 2015 to 2019, marking the COVID dates starting around the time of late 2019. 

## Summary 
One of our assumptions going into this was that companies that had a more online presence would have a better chance of seeing growth in the market due to the lack of human interaction. Because of this, we pointed out technology as the sector that should see the most growth. While this is true that the technology sector is one of the leading sectors for 2020, we also see that the real estate sector is tied with technology for a 7.7 ROC over the 2 quarters so far in 2020.

While these two sectors are the biggest cases of doing better than the predicted ROC, all the of the sectors that were studied show to do significantly better, or worse in the case of Health Care, than what was predicted based on past performance.

One trend that all of the sectors do share is that there is a v-shaped recovery after falling in the first quarter of the year. This is an economic term where a market has started to come up after a previous fall, looking like a v on a graph.

Going through the project, one of our biggest problem was trying to figure out which data to use to properly show each sector. Not all stocks are equal in terms of price or volume sold, so we had to find a statistic that would let us compare them equally.

Going through the results we clearly see some interesting things that we weren’t expecting, so with more time we would have wanted to look more into what was happening in certain sectors to allow them have more success than others. We would also want to compare

## Questions to Answer 
1- How did the pandemic affect certain industries? 

2- Did previous trends affect buyers choices after the start of the pandemic? 

3- Do we see any upticks in certain fields after stimulus checks? 

### Data Source 
All data that we used about the different stocks came from [Alpha Vantage](https://www.alphavantage.co/). In order to determine the top 20 stocks for each of the selected setors, we based it off the market shares, shown by [Barchart](https://www.barchart.com/).


### Data Cleaning
After we had brought in all the CSV files for the indiduval stocks, we needed to bring all the data together. We used the Combined_CSV.ipynb file to concact all files to begin the comparisons. From there, we seperated the stocks based on their sector, and got the dates and closing price corresponding to the dates begining the business quarter. With the wanted data selected we were then able to create line graphs for each sector showing each quarter from 2015-2019. 

# 2019-General-Election-Sentiment-Analysis
This project uses tweets extracted with the help of the Twitter API to project the general public sentiment for the 2019 Indian General Elections. With the help of different queries, and parameters such as geographical coordinates, time period and radius, I have extracted tweets for different Leaders and National Parties. Once the sentiment values for positive, negative and neutral tweets is calculated, I have taken the positive values for 30 different cities in India and plotted the values on a map.

# Prerequisites
To be able to execute this project, your require the following besides Python 3 - 
1. Plotly Graphing library
Installation: https://plot.ly/python/getting-started/

2. Tweepy library
Documentation:http://docs.tweepy.org/en/v3.5.0/

3. TextBlob library
Installation: https://textblob.readthedocs.io/en/dev/install.html

4. Your very own Twitter API consumer key and access token
 
# Results 
The statistics are shown below.

The city-wise positive sentiments for Shri Narendra Modi
![The city-wise positive sentiments for Shri Narendra Modi](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/NM.png)

The city-wise positive sentiments for BJP
![he city-wise positive sentiments for BJP](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/BJP.png)

The city-wise positive sentiments for Shri Rahul Gandhi
![The city-wise positive sentiments for Shri Rahul Gandhi](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/RAGA.png)

The city-wise positive sentiments for Indian National Congress
![The city-wise positive sentiments for Indian National Congress](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/INC.png)


I have also tried to assess the impact of the Balakot Airstrike (conducted on the 26th Feb, 2019) on the popularity of Shri Narendra Modi. He clearly gained electorally from the strike.

The city-wise positive sentiments for Shri Narendra Modi before Balakot Airstrike
![Positive sentiments for Shri Narendra Modi before Balakot Airstrike](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/NMBeforeBalakot.png)

The city-wise positive sentiments for Shri Narendra Modi after Balakot Airstrike
![Positive sentiments for Shri Narendra Modi after Balakot Airstrike](https://github.com/Anniebbb/2019-General-Election-Sentiment-Analysis/blob/master/NMAfterBalakot.png)

# Conclusions
It can clearly be seen that the Narendra Modi's popularity rised by 10% on an average after the airstrike and that he and his party, the BJP, were the forerunners in this elections. 


# Author
Ananya Bal

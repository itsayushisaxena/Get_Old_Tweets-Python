# Get_Old_Tweets - Python
This is a repository which contains a script in Python to retrieve the older tweets from Twitter API.

## Description: 

**snscrape is a scraper for social networking services (SNS).Problem**: I was working on a project for which I needed the earlier tweets. But, I noticed that Twitter official API does not allow its normal developers to retrieve tweets of older than a week. There are some pre-built tools for the same but mostly,they are paid ones. I searched for some alternative to get the tweets and I luckily found them but, after trying a lot to troubleshoot the errors, I realised that even the most popular ones are now outdated just after the latest update release of Twitter in September,2020 where it removed its '/i/search/timeline' endpoint. It made scraping the tweets from advanced search window just impossible. I observed that scholars, developers and researchers are facing lot of troubles due to this problem. 

**Solution**: To get the historical tweets, we would have to manage to use the free APIs effectively that are already available to us.  I did some more research and finally ended up with a working solution. Here, I will be sharing it with you all so that all of you can get the benefits.

[Snscrape](https://github.com/JustAnotherArchivist/snscrape) is a scraper for social networking services (SNS). [Tweepy](https://github.com/itsayushisaxena/tweepy) is a library of Python to access Twitter API. 

To install both of these:
    pip3 install snscrape
    
    



*Process: Clone this repository and run this jupyter notebook on your system. 
You will require your credentials. And the further process is simple. With this script, you can successfully retrieve older tweets also. Congratulations!*

## Important:

For retrieving latest tweets(within past 7 days), [check this](https://github.com/itsayushisaxena/Tweet-retrieval-for-Sentiment-Analysis)

Any queries? Mail me at **ayushisaxenamtr@gmail.com**

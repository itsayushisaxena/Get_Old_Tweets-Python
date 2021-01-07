# Get_Old_Tweets - Python
This is a repository which contains a script in Python to retrieve the older tweets from Twitter API.

## Description: 

**Problem**: I was working on a project for which I needed the earlier tweets. But, I noticed that Twitter official API does not allow its normal developers to retrieve tweets of older than a week. There are some pre-built tools for the same but mostly,they are paid ones. I searched for some alternative to get the tweets and I luckily found them but, after trying a lot to troubleshoot the errors, I realised that even the most popular ones are now outdated just after the latest update release of Twitter in September,2020 where it removed its '/i/search/timeline' endpoint. It made scraping the tweets from advanced search window just impossible. I observed that scholars, developers and researchers are facing lot of troubles due to this problem. So, I came up with a solution.

**Solution**: To get the historical tweets, we would have to manage to use the free APIs effectively that are already available to us.  I did some more research and finally ended up with a working solution. Here, I will be sharing it with you all so that all of you can get the benefits.

- Step 1: Install all the requirements. Also, keep your twitter developer account ready alongwith the API keys.

   - [Snscrape](https://github.com/JustAnotherArchivist/snscrape) is a scraper for social networking services (SNS). 
   - [Tweepy](https://github.com/itsayushisaxena/tweepy) is a library of Python to access Twitter API. 

To install both of these:

    pip3 install snscrape
    
Any issues regarding installation of snscrape? Please refer [this](https://github.com/JustAnotherArchivist/snscrape).

After you're done with installing the snscrape and tweepy, scrape the tweets. Refer Step 2.

- Step 2: Open your terminal and copy the following commands. Include changes that you want.

For txt file:
```
snscrape twitter-search "#coronavirus since:2020-01-01 until:2021-01-03" > scraped_tweets.txt
```
for txt file:
```
snscrape --jsonl twitter-search "#coronavirus since:2020-01-01 until:2021-01-03" > scraped_tweets1.json
```
Now, you've got a file (json or txt) which contains the URL of the same tweets that you require.

- Step 3: *Congrats! You've come so close.*

Just Clone this repository and run this jupyter notebook on your system. Don't forget that you need to put your own credentials. And the further process is simple. With this script, you can successfully retrieve older tweets also. A csv file will be created with the older tweets information. Check and carry out your further tasks.

There is a limitation on the number of tweets you can scrape. [It's 100,000 tweets per day](https://developer.twitter.com/en/docs/twitter-api/v1/tweets/timelines/faq). 

 **Congratulations! You're done.**

    
    
### Important:

For retrieving latest tweets(within past 7 days), [check this](https://github.com/itsayushisaxena/Tweet-retrieval-for-Sentiment-Analysis)

Any queries? Mail me at **ayushisaxenamtr@gmail.com** :+1:

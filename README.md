# Mining_Twitter

## Overview

Create a Python script that establish a connection to the Twitter API, analyze trending topics and hashtags regarding a particular ongoing conversation on this platform.

Using pandas and Matplotlib libraries, we create a *WordCloud* and plots that show the frequency of words, emojis and the tweets with the highest number of retweets 

Keep in mind that throughout this project we will be working with the hashtag *#Bitcoin*. Therefore, the results will vary if you decide to work with another hashtag. What will remain the same, is the process to query *any* hastag. So, what is cool about this script is that it can help you query any ongoing conversation given a particular topic you want to analyze.

## Tools

- Twiter API version 2
- Python
- Pandas
- Matplotlib

## Results

Some of the objectives we want to achive are the following:

- #### Worcloud with the most used words in the tweets statuses:
![WC](https://user-images.githubusercontent.com/78564912/148801580-8be3752f-203a-41a7-a47c-874101f54157.png)

- #### A shaped WordCloud :
![twitter1](https://user-images.githubusercontent.com/78564912/148801736-ca1fbedf-5892-42d6-b3d4-d7b7288ec2dd.png)

- #### A DataFrame with the retweeted frequency of a particular hastag query:
![image](https://user-images.githubusercontent.com/78564912/148802360-4faca4a3-900a-4828-b570-64efe7e1c902.png)

Let's begin!

**1) API Keys**

The first step we need to complete is to obtain our API keys from Twitter. You may want to visit the link: 
[Get access to the Twitter API](https://developer.twitter.com/en/docs/twitter-api/getting-started/getting-access-to-the-twitter-api) and start from here.

**2) pip install twitter**

Once you have granted access to the Twitter API, you want to install the twitter library, so you can ```pip install twitter``` form your terminal. You can vist the offical website to install this package: [pypi Twitter](https://pypi.org/project/twitter/)

**3) Import dependencies and Creating OAuth dance**

You will need to install the following dependencies in order to be able to begin our query. Since you want your APIs keys nice and secure, it is important to create a ```config.py``` file in which you will need to store your these (access_token, access_token_secret, api_key, api_secret) and definene them on it, so you can then import the ```config.py```, just like in line 13 in the *Import dependencies* cell in ```Mining_Twitter.ipynb``` Jupyter notbook. See caption below. Again, this way your API keys will be secured in a separeted file from the one you will be working on.

![image](https://user-images.githubusercontent.com/78564912/148799963-e10ba52e-aae3-4455-a082-930a7c457861.png)


*Working on Updating README.md...*

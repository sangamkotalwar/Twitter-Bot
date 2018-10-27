# Create a Twitter Bot in Python Using Tweepy

## Setup

1. Download python and Tweepy
```python
pip install tweepy
```
2. Get credentials for Twitter developer [api](https://www.app.twitter.com)
3. Under your import statements store your credentials within variables and then use the second block of code to authenticate your account with tweepy.
```python
consumer_key = 'consumer key'
consumer_secret = 'consumer secrets'
access_token = 'access token'
access_token_secret = 'access token secret'
```

## The basic twitter bot
This bot is meant to:
* Follow everyone following you.
* Favorite and Retweet a Tweet based on keywords.
* Reply to a user based on a keyword.
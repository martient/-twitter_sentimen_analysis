# curson_emotion_tweet

## Required

### twitter_credentials.py

Add your own keys

```
ACCESS_TOKEN = ""
ACCESS_TOKEN_SECRET = ""
CONSUMER_KEY = ""
CONSUMER_SECRET = ""
```

### Lib tweepy

```
pip install tweepy
```

### Lib pandas

```
pip install pandas
```

### Lib numpy

```
pip install numpy
```

### Lib matplotlib

```
pip install numpy
```


### Lib textblob

```
pip install textblob
```

> https://youtu.be/1gQ6uG5Ujiw?t=2609


``` python
print(np.mean(data_frame['length']))

    print(np.max(data_frame['likes']))
    print(np.max(data_frame['retweets']))
    time_likes = pd.Series(data=data_frame['likes'].values, index=data_frame['date'])
    time_likes.plot(figsize=(16, 4), label="likes", legend=True)
    time_retweets = pd.Series(data=data_frame['retweets'].values, index=data_frame['date'])
    time_retweets.plot(figsize=(16, 4), label="retweets", legend=True)
    plt.show()
```
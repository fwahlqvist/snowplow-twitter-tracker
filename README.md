# snowplow-twitter-tracker

## Installation
```
$ sudo apt-get install python-dev
$ sudo pip install tweepy
$ sudo pip install snowplow-tracker
$ git clone https://github.com/goliasz/snowplow-twitter-tracker.git
```

## Start
```
$ export TWITTER_TOKEN="<HERE TOKEN>" 
$ export TWITTER_TOKEN_SECRET="<HERE TOKEN SECRET>" 
$ export TWITTER_KEY="<HERE KEY>" 
$ export TWITTER_SECRET="<HERE KEY SECRET>"
$ cd snowplow-twitter-tracker
$ sh src/main/script/twitter-miner.sh "2193645284,721938046472581120,799541035466637312" "yes"
```

# License
Apache License, Version 2.0
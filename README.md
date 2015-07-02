Python Retweet Bot
==================

This script retweets all Tweets containing your search term. To limit Twitter requests a savepoint file marks Tweets found before. It's Twitter API v1.1 ready.

How to start:
-------------
* Depends on http://tweepy.github.com/ (pip install tweepy)
* Copy 'config.sample' to 'config'
* Define your hashtag or search query in config
* Add your Twitter app credentials in config
* (Tune some other options if you like)
* $ python retweet.py
* Add this call to your crontab (or something similar) to retweet all new tweets regularly

More info:
---------
* I've left the bot uncustomized, within GitHub, mostly. Obviously, I'm not pushing up my config file. I do have a user blacklist, which [the original](https://github.com/basti2342/retweet-bot) did not.
* [Directions for crontab on a Mac](http://www.maclife.com/article/columns/terminal_101_creating_cron_jobs), though if you aren't on Yosemite, [launchd](https://developer.apple.com/library/mac/documentation/MacOSX/Conceptual/BPSystemStartup/Chapters/CreatingLaunchdJobs.html) is preferred



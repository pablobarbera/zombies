Zombie Outbreak Detector
=============

Source code to build the website at [www.pablobarbera.com/zombies](http://www.pablobarbera.com/zombies).

Summary of .R files
-------

* `functions.R` includes all the functions that are necessary to run the other two R files.
* `get_tweets.R` captures all tweets mentioning the keyword `zombi' in intervals of 60 minutes, transforms them from JSON into a dataframe, and stores them in a mySQL database on localhost.
* `draw_map.R` opens the tweets from the past 24 hours, extracts country of origin using the information on each user's profile and calling the Yahoo Geo API, and finally draws a map using the googleVis package.
* Just practicing pull request

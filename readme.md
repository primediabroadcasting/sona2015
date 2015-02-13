#SONA 2015 Data

A collection of 264464 tweets received from the Twitter Streaming API that contained either \#sona or \#sona2015, from 19:00 SAST to 21:30 SAST 12 Feb 2015.

Currently contains a MySQL dump of a table called tweets:

Interesting fields in the table:

- ```tweet_id``` is the id of the tweet as identified by Twitter.   You can retrieve the full detail about the tweet from the [Twitter API](https://dev.twitter.com/rest/reference/get/statuses/show/%3Aid)
- ```ts``` is a MySQL timestamp of when we received the tweet fom the Twitter API
- ```text``` is the extracted tweet text

Will update the repo later with a MySQL dump containing the full JSON received for each tweet, as well as some more user friendly formats a bit later.

If you do do anything interesting with the data, please let me know.

Pull requests welcome.
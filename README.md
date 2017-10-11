Based on package [twitter-js-client](https://www.npmjs.com/package/twitter-js-client)

## Description
A twitter client written in Javascript

## Usage

    var twitter = new Twitter({
        user: '[twitter-username]',
        consumerKey: '[consumer_key]',
        consumerSecret: '[consumer_secret]',
        accessToken: '[access_token]',
        accessTokenSecret: '[access_token_secret]',
        callBackUrl: '[callback_url]',
        tweet_mode: 'extended',
        tweetCount: 5
    });
    
	twitter.getUserTimeline();
	twitter.getMentionsTimeline();
	twitter.getHomeTimeline();
	twitter.getReTweetsOfMe();
	twitter.getTweet();
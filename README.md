# kai-heart-radio

([Listen to the playlist here](https://open.spotify.com/playlist/4rZUphu6YsAi4k0iNpq484?si=Gx6xxSBVSaSV1jlRdPzI4w))

This is an updated fork desgigned to run on Azure Functions. The script has been updated to work with Python 3, but is otherwise unchanged.

# Original ReadMe Follows

The dog and I listen to Marketplace on APM during our walks to the park. The dog doesn't much care for it, but I love it, especially the music interludes.
Marketplace publishes a list of the songs on their daily broadcasts. I found myself adding the songs to a Spotify playlist I listen to at work. Now kai-heart-radio does it for me.

The app scrapes the Marketplace site for new songs, but the Spotify bits are generally applicable to Spotify search and playlist management. 
The app runs on a t2.nano instance as an hourly cron job.

A template for the config file is provided. To get going, you'll need to first [create a Spotify app](https://developer.spotify.com/my-applications/#!/applications/create) and then follow the [Web API Authorization Code Flow](https://developer.spotify.com/web-api/authorization-guide/#authorization-code-flow) to get yourself an access token.

Now Kai Ryssdal approved:
![https://twitter.com/kairyssdal/status/761617874213408768](http://benradosevich.com/images/kaiheartradio.png)

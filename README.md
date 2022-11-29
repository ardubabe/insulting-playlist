# Playlist made up of Stranger Things Quotes

Using the [Spotify API](https://developer.spotify.com/dashboard/) and the [Stranger Things API](https://github.com/shadowoff09/strangerthings-quotes?ref=publicapis.dev) to create a playlist that makes up the quote via the track names.



## Setup

To get this working you need to input your Spotify API keys into a spotify_keys.json file. You can access your keys by signing up for a [Spotify Developer Account](https://developer.spotify.com/dashboard/). It should look something like this:

{
    "username": "your_username",
    "client_id": "your_client_id",
    "client_secret": "your_client_secret",
    "redirect": "http://google.com/"
}

You will also need to set up a virtual environment and download the libraries listed in the requirements.txt file. 
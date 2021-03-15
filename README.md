# Spotify Billboard Playlist Creator

The purpose of this application is to create a spotify playlist of the top 100 songs on Billboard on a any given date. 

## How It Works

The application prompts the user to enter any date the user wishes to put in. Once that data has been collected, the application then uses web scrapping techniques to grab all top 100 songs from that user specified date on the Billboard website. After retrieving that data, the application then uses the Spotify API, to authenticate the user, create a new playlist, then add the songs from the list the application collected earlier.

## How To Run It

In order to run this application, make sure that Python3 is installed on your computer. Once installed, download the entire spotifyBillboardPlaylist folder. You will first need to get your Spotify API keys and then when you run the application for the first time(python3 main.py) it will redirect you to an empty website with your authentication token. You will then be able to place that token in your token.txt file, if its not there then create one. Once all is authenticated it, you can run the application again using python3 main.py and then input the specific date you are looking for. You will tehn be able to find that playlist on your Spotify account.

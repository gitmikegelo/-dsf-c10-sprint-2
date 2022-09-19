# Getting started

This repository contains materials for Eskwelab's Music Streaming Analytics sprint. Follow the instructions below for the initial setup:

## 0. Setting up your spotify credentials
Follow the instructions at the [Spotify for Developers Quick Start page](https://developer.spotify.com/documentation/web-api/quick-start/) and follow up to the *Set Up Your Account* section. Alternatively, you may follow this [tutorial](https://developer.spotify.com/documentation/general/guides/authorization-guide/)

Make a new app and copy the Client ID and Secret Code.

## 1. D1N1_Set_Spotify_Credentials.ipynb

Install the [`keyring`](https://keyring.readthedocs.io/en/latest/) package
````
pip install keyring 
````
The Python keyring library provides an easy way to access the system keyring service from python. It can be used in any application that needs safe password storage. 

Run the notebook. Keyring will ask for your Spotify Client ID and Secret Code and safely hold it in your device.

For the notebooks below, please also install the [`spotipy`](https://spotipy.readthedocs.io/en/2.12.0/) python module 
````
pip install spotipy
````
## 2.  D1N2_Get_Spotify_Track_Artist_Data.ipynb
Use this notebook to get Spotify track data for the tracks ranking in the daily charts data

## 3. D5N1_Get_Spotify_Playlists_Data.ipynb
Use this notebook to get spotify playlists based on a spotipy query object 



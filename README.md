# billboard-spotify-playlist

This Python script scrapes Billboard's Hot 100 songs for a given date and automatically creates a Spotify playlist using the Spotify API.

## Features
- Generates a Spotify playlist based on any Billboard Hot 100 chart date.
- Scrapes Billboard's website for the top 100 songs.
- Searches for the songs on Spotify and adds them to a playlist.
- Automates the entire process with minimal user input.

---

## Installation and Setup

### 1. Clone the Repository

git clone https://github.com/yourusername/billboard-spotify-playlist.git
cd billboard-spotify-playlist

2. Install Dependencies
pip install -r requirements.txt

3. Set Up Spotify API Credentials
Create a Spotify Developer Account at Spotify Developer Dashboard.
Create an app and retrieve the Client ID and Client Secret.
Set environment variables for authentication.
Windows (Command Prompt)

setx SPOTIFY_CLIENT_ID "your_client_id"
setx SPOTIFY_CLIENT_SECRET "your_client_secret"
setx SPOTIFY_USERNAME "your_username"


Usage
To create a playlist, run the script and enter a date in YYYY-MM-DD format.




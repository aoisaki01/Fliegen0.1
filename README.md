# Fliegen Discord Bot

Multi-purpose Discord bot powered by Google Gemini 2.0 Flash, voice channel audio streaming, and Spotify integration.

## Features

* Conversational AI integration using Google Gemini 2.0 Flash
* Audio playback in voice channels via `yt-dlp` and `FFmpegPCMAudio`
* Spotify metadata resolution through `spotipy`
* Web content parsing with BeautifulSoup4
* Asynchronous request handling via `aiohttp`

## Tech Stack

* Python 3.10+
* discord.py 2.0
* google-generativeai
* yt-dlp
* spotipy
* BeautifulSoup4

## Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Set environment variables:

```ini
DISCORD_API_KEY=your_discord_bot_token
GEMINI_API_KEY=your_gemini_api_key
SPOTIPY_CLIENT_ID=your_spotify_client_id
SPOTIPY_CLIENT_SECRET=your_spotify_client_secret
```

3. Run the bot:

```bash
python bot.py
```
# YouTube Playlist Extractor

A client-side web app that extracts and displays public playlists from any YouTube channel using the YouTube Data API v3.

## Features
- Supports multiple YouTube URL formats (`@handle`, `/channel/`, `/user/`, `/c/`)
- Automatically filters playlists with too many private or deleted videos
- Displays up to 4 valid playlists with their latest videos
- Shows video thumbnails, titles and duration
- ISO 8601 duration parsing (PT1H30M20S → 1 hora, 30 minutos, 20 segundos)

## Tech Stack
- Vanilla JavaScript
- Axios
- YouTube Data API v3
- Bootstrap

## Setup
1. Clone the repo
2. Add your YouTube Data API v3 key in the `key=` fields inside `script.js`
3. Open `index.html` in your browser

## Requirements
- YouTube Data API v3 key ([Get one here](https://console.cloud.google.com/))


# PRODIGY_WD_05 — Weather App

A responsive weather dashboard for city search or current-location forecasts, with current conditions and a five-day outlook.

## Features
- Search for a city using Open-Meteo geocoding
- Optional browser location lookup (requires permission and a secure context such as HTTPS or localhost)
- Current temperature, feels-like temperature, wind, humidity, UV index, and sunrise
- Five-day forecast
- Loading and error states

## Run locally
Open `index.html` in a modern browser. For geolocation, serve the folder from localhost or deploy it over HTTPS. City search uses the public Open-Meteo APIs.

## API and credentials
The app uses the public [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api) and [Forecast API](https://open-meteo.com/en/docs). The current implementation requires no API key, account, or secret credential. Do not add private tokens or passwords to this public repository.

## Files
- `index.html` — weather dashboard interface
- `styles.css` — responsive styles
- `app.js` — geocoding, forecast requests, and rendering

## License
Provided for learning and portfolio use.

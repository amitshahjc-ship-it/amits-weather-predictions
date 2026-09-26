# Amit's Weather Predictions

A mobile-first weather dashboard for the Upper East Side, New York, with location search for other places. Live current conditions, 48 hourly forecast points and a seven-day forecast use Open-Meteo. No build step, server, account, API key or tracking is needed.

## Run

Open `index.html` in a static web server. For example, `python3 -m http.server 8000` then visit `http://localhost:8000`. The forecast requires a network connection. Publish `index.html`, `styles.css` and `app.js` to a static host.

## Sources and limits

[Open-Meteo Forecast API](https://open-meteo.com/en/docs) and [Geocoding API](https://open-meteo.com/en/docs/geocoding-api) provide the data, licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Open-Meteo's free API is limited to non-commercial use and rate limits. This site does not claim higher accuracy than other weather providers. Weather can change, so consult [NWS](https://www.weather.gov/) for severe weather alerts.

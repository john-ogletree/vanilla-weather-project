# Weather Dashboard ☀️

A simple, lightweight weather utility that uses your device's location to display real-time weather information. No API keys required.

## What is Weather Dashboard?

Weather Dashboard is a minimal web application that:

- **Detects your location** using the browser's Geolocation API
- **Fetches current weather** from the free Open-Meteo API
- **Displays temperature and wind speed** in a clean interface
- **Requires no API keys** or sign-ups

## Key Features

- **Location Detection:** Automatically finds your coordinates
- **Real-Time Weather:** Fetches live data from Open-Meteo
- **Temperature:** Displays in Fahrenheit
- **Wind Speed:** Shows current wind speed in mph
- **No API Keys:** Uses free, open weather data
- **Privacy Focused:** Location data stays on your device
- **Clean UI:** Minimal dark theme design

## How to Use

1. **Open the page** in your browser
2. **Click "Get My Local Weather"**
3. **Allow location access** when prompted
4. **View your current weather** (temperature and wind speed)

## How It Works

1. **Geolocation API:** Gets your current latitude and longitude
2. **Open-Meteo API:** Fetches weather data for your coordinates
3. **Data Display:** Shows temperature and wind speed in real-time

### API Used

- **Open-Meteo:** Free, open-source weather API
  - No API key required
  - Supports latitude/longitude queries
  - Returns temperature, wind speed, and more

## Technology Stack

- **HTML5:** Structure
- **CSS3:** Dark theme styling
- **Vanilla JavaScript:** Geolocation and API calls
- **Open-Meteo API:** Free weather data
- **Geolocation API:** Browser location detection

## Project Structure

```
weather-dashboard/
├── index.html          # Single-file application
└── README.md           # Project documentation
```

## Browser Support

Works on modern browsers that support the Geolocation API:
- Chrome (desktop + mobile)
- Firefox (desktop + mobile)
- Edge
- Safari (desktop + mobile)

**Note:** Location access must be granted by the user.

## Privacy Statement

Your location data is only used to fetch weather information. It is never stored or shared. The Open-Meteo API receives your coordinates to provide accurate weather data. 

# Weather Dashboard

A real-time weather web app with a **5-day forecast**, city search, animated weather icons, and a clean dark-mode terminal aesthetic. Powered by the [OpenWeatherMap API](https://openweathermap.org/api).

## 🚀 Features

- 🔍 Search any city worldwide
- 🌡️ Current temp, feels like, humidity, wind speed, UV index
- 📅 5-day hourly forecast with animated icons
- 🌓 Auto dark/light mode based on local time
- 📍 Geolocation — auto-detect user's city on load
- 💾 Recent searches saved to localStorage

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — CSS variables, grid layout, smooth animations
- **Vanilla JavaScript** — fetch API, async/await, DOM manipulation
- **OpenWeatherMap API** — weather + forecast data
- **Deployed on** — GitHub Pages

## 📂 Project Structure

```
weather-dashboard/
├── index.html
├── style.css
├── app.js
├── assets/
│   └── icons/            # Animated SVG weather icons
└── README.md
```

## ⚙️ Getting Started

```bash
# Clone
git clone https://github.com/farhansayyedd/weather-dashboard.git
cd weather-dashboard

# Add your API key
# In app.js, replace:
const API_KEY = 'YOUR_OPENWEATHERMAP_API_KEY';

# Open in browser
open index.html
# Or use Live Server extension in VS Code
```

## 🌐 Live Demo

[farhansayyedd.github.io/weather-dashboard](https://farhansayyedd.github.io/weather-dashboard)

## 📄 License

MIT © Farhan Sayyed

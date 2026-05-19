# 🌦️ Weather App

A simple weather application built with **HTML, CSS, and JavaScript** using the OpenWeatherMap API.

## Features

- 🔍 Search weather by city name
- 🌡️ Current temperature
- ☁️ Weather condition & icon
- 💧 Humidity
- 🌬️ Wind speed
- 📱 Responsive design
- ⌨️ Press **Enter** to search

## Screenshot

Add a screenshot here later:

```txt
/screenshot.png
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/weather-app.git
```

### 2. Open the project folder

```bash
cd weather-app
```

### 3. Run the app

Open `index.html` in your browser.

No installation required.

---

## API Setup

This project uses the **OpenWeatherMap API**.

1. Create an account at OpenWeatherMap
2. Generate an API key
3. Replace the API key in `script.js` or `index.html`

Find this line:

```javascript
const API_KEY = "YOUR_API_KEY";
```

Replace it with:

```javascript
const API_KEY = "your_api_key_here";
```

---

## Project Structure

```txt
weather-app/
│── index.html
│── README.md
│── screenshot.png (optional)
```

---

## Example Usage

Search for cities like:

- London
- Sofia
- New York
- Tokyo

The app will display:

- Temperature
- Weather description
- Humidity
- Wind speed

---

## Common Issues

### "City not found"

Possible causes:

- API key is not activated yet  
  (can take 5–30 minutes)

- Misspelled city name

- Invalid API key

### API key error

Test your API key in browser:

```txt
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

If working, you should see JSON weather data.

---

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- OpenWeatherMap API

---

## Future Improvements

- 📍 Current location weather
- 🌙 Dark mode
- 📅 5-day forecast
- 🎨 Better UI animations

---

## License

This project is open-source and free to use.

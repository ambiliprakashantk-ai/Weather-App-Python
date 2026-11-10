# 🌦️ Weather App using Python & API

A Python weather application that retrieves live weather information for any city. Enter a city name and the app fetches the current temperature, humidity, and weather conditions from a weather API and displays them in a clear format.

---

## 📌 Features

- Accepts a city name as user input
- Sends a request to a weather API using the `requests` library
- Parses the JSON response
- Displays temperature, humidity, and weather conditions clearly
- Gracefully handles:
  - Invalid city names
  - Missing or invalid API keys
  - Network and connection errors
- API key is kept out of the source code (stored in a `.env` file)

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** `requests`, `python-dotenv`
- **API:** OpenWeatherMap (or the weather API you used)

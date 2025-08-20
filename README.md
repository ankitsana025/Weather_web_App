# Weather App with AI Chatbot

A lightweight, responsive web application that shows real-time weather information for your current location and includes an interactive chatbot powered by the Gemini API. The chatbot can answer questions while referencing live weather conditions.

---

## ✨ Features

* **Real-Time Weather:** Displays current temperature, city, weather description, humidity, and wind speed.
* **Automatic Geolocation:** Detects the user’s location (with permission) to fetch accurate weather data.
* **AI Chatbot:** Integrated chatbot powered by Gemini, capable of answering questions and incorporating current weather into responses.
* **Responsive UI:** Optimized layout for both desktop and mobile devices.
* **Typing Indicator:** Shows when the chatbot is generating a response for a smoother conversation experience.

---

## 🛠️ Tech Stack

* **HTML5** – Page structure
* **Tailwind CSS (via CDN)** – Styling and responsive design
* **JavaScript (Vanilla)** – Core logic, API calls, and interactivity
* **OpenWeatherMap API** – Provides real-time weather data
* **Gemini API** – Powers the chatbot responses

---

## 🚀 Getting Started

### 1. Get API Keys

* **OpenWeatherMap**: Sign up and generate a free API key from [OpenWeatherMap](https://openweathermap.org/).
* **Gemini**: Use the Gemini API key provided in your environment. If you have your own, replace the placeholder in the code.

### 2. Add Your Keys

In `index.html` (inside the `<script>` tag), update the following line:

```js
const API_KEY = 'YOUR_API_KEY'; // Replace with your OpenWeatherMap key
```

### 3. Run the App

* Open `index.html` in any modern browser.
* Allow location access when prompted.

---

## 💡 How to Use

1. The weather card loads automatically with the weather for your current location.
2. Click the blue chat button (bottom-right) to open the chatbot.
3. Type your query in the chat input. The chatbot will reply with insights that consider the current weather.

---

## 🔮 Future Enhancements

* **Weather Forecasts:** Display multi-day forecasts.
* **City Search:** Option to search weather by city name.
* **Settings Panel:** Toggle between Celsius and Fahrenheit.
* **Smarter Chatbot:** Improved memory and context handling across conversations.

# 🌦️ Weather Forecast App

A simple and elegant **Weather Forecast App** built using **HTML**, **CSS**, and **JavaScript**.  
This app allows users to search for any city and view real-time weather conditions along with a 5-day forecast. It uses the **SheCodes Weather API** to fetch accurate and up-to-date data.

---

## 🚀 Features

- 🌍 Search for weather by **city name**
- 🌡️ View **current temperature**, humidity, wind speed, and conditions
- 🗓️ Displays **local date and time** for the searched location
- 📅 **5-day forecast** with weather icons and daily temperature range
- ⚡ Powered by **Axios** for API calls
- 💅 Clean, responsive design using **CSS Flexbox**

---

## 🧠 Technologies Used

| Category        | Tools                                                   |
| --------------- | ------------------------------------------------------- |
| **Frontend**    | HTML5, CSS3, JavaScript (Vanilla JS)                    |
| **API**         | [SheCodes Weather API](https://www.shecodes.io/weather) |
| **HTTP Client** | Axios                                                   |
| **Hosting**     | Netlify                                                 |
| **Fonts**       | Google Fonts – Roboto                                   |

---

## 🗂️ Project Structure

````plaintext
📦 Weather-Forecast-App
├── index.html
└── src/
    ├── style.css
    └── index.js


---

## ⚙️ How It Works

1. The user enters a **city name** in the search bar.
2. The app sends a request to the **SheCodes Weather API** using Axios.
3. The API returns current weather and forecast data.
4. JavaScript dynamically updates the DOM to display the weather information.

---

## 🖥️ Live Demo

🔗 [View Hosted App on Netlify](https://vanillaforecastapp.netlify.app/)
🔗 [View Source Code on GitHub](https://github.com/Khanyi2/Vanilla-Weather-Forcast)

---

## 🧩 Example API Request

```js
let apiKey = "your_api_key";
let city = "Cape Town";
let apiUrl = `https://api.shecodes.io/weather/v1/current?query=${city}&key=${apiKey}&units=metric`;
axios.get(apiUrl).then(refreshWeather);

💡 Future Improvements

🌈 Add dark mode toggle

📍 Detect current location automatically using Geolocation API

📱 Make layout more responsive on mobile

📊 Add temperature unit toggle (°C ↔ °F)

👩🏽‍💻 Developer
Khanyi Sefalane
````

# 🌤️ WeatherApp

A simple and responsive **Android Weather Application** built with **Java** and **Gradle (Kotlin DSL)**.  
This app fetches real-time weather data from an external API and displays the current weather conditions with a clean and user-friendly interface.

---

## 🚀 Features
- 🌎 Search weather by city name
- 📍 Location-based weather (GPS integration)
- 🌡️ Displays temperature, humidity, wind speed, and conditions
- 📅 Shows current day with background visuals
- ⚡ Fast API integration using Retrofit/HTTP requests
- 🎨 Intuitive UI designed with XML layouts

---

## 🛠️ Tech Stack
- **Language**: Java  
- **Build System**: Gradle (Kotlin DSL)  
- **Frameworks & Tools**: Android SDK, Android Studio  
- **API Integration**: OpenWeatherMap API (or similar)  
- **UI**: XML layouts, Vector Drawables  

---

## 📂 Project Structure
Weatherapp/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/example/weatherapp/ # App source code (MainActivity.java etc.)
│ │ │ ├── res/ # Layouts, drawables, colors, icons
│ │ │ └── AndroidManifest.xml
│ ├── build.gradle.kts
│ └── proguard-rules.pro
├── build.gradle.kts
├── settings.gradle.kts
└── gradle.properties

yaml
Copy code

---

## ⚙️ Setup Instructions
1. Clone this repository or extract the zip:
   ```bash
   git clone https://github.com/yourusername/WeatherApp.git
Open the project in Android Studio.

Get a free API key from OpenWeatherMap.

Add your API key in the app’s MainActivity.java (or config file where the API is called):

java
Copy code
private final String API_KEY = "YOUR_API_KEY_HERE";
Build and run the app on an emulator or physical device.


🏆 Achievements
Built as part of learning Android development.

Implements real-time REST API integration.

Designed for cross-device compatibility.

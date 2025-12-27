# 🌤️ WeatherCast - Android Weather App

A feature-rich Android weather application that provides real-time weather information, air quality index, humidity levels, and weather news. Built with Java and modern Android development practices.

## ✨ Features

- **Real-time Weather Data**: Get current weather conditions for any city
- **Temperature Tracking**: View current, minimum, and maximum temperatures with real feel
- **Air Quality Index (AQI)**: Monitor air quality levels in your location
- **UV Index (UVI)**: Track UV radiation levels for sun protection
- **Humidity & Wind Speed**: Detailed atmospheric conditions
- **Location-based Weather**: Automatic weather updates based on your GPS location
- **Weather News**: Stay updated with latest weather-related news
- **Multi-language Support**: Available in English, Hindi (हिन्दी), and French (Français)
- **Beautiful UI**: Modern, intuitive interface with animated splash screen
- **Bottom Navigation**: Easy navigation between different weather metrics
- **Side Navigation Drawer**: Quick access to all app features

## 📱 Screenshots

<!-- Add your app screenshots here -->
<!-- ![Home Screen](screenshots/home.png)
![AQI Screen](screenshots/aqi.png)
![Settings](screenshots/settings.png) -->

## 🛠️ Built With

- **Java** - Primary programming language
- **Android SDK** - Android development framework
- **Material Design Components** - Modern UI components
- **Location Services** - GPS-based weather tracking
- **View Binding** - Type-safe view access
- **Lottie** - Animated splash screen

## 📋 Prerequisites

- Android Studio Arctic Fox or later
- Android SDK (API level 19+)
- JDK 8 or higher
- Internet connection for weather data

## 🚀 Getting Started

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SarthakSingh-96/Weather-app.git
   cd Weather-app
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the cloned directory and select it

3. **Sync Gradle**
   - Android Studio will automatically sync Gradle files
   - Wait for the process to complete

4. **Run the app**
   - Connect an Android device or start an emulator
   - Click the "Run" button (▶️) in Android Studio
   - Select your device and click OK

### API Setup

To use weather data, you may need to add your API key:
1. Obtain an API key from your weather data provider
2. Add it to your project configuration
3. Update the relevant code files with your API key

## 📱 Minimum Requirements

- **Minimum SDK**: Android 4.4 (API 19)
- **Target SDK**: Android 12 (API 31)
- **Permissions Required**:
  - Internet Access
  - Location Access (Fine & Coarse)
  - Network State

## 🎨 Features Breakdown

### Temperature Fragment
- Current temperature display
- Minimum and maximum temperature
- Real feel temperature
- Weather condition descriptions

### AQI Fragment
- Air Quality Index monitoring
- UV Index tracking
- Health recommendations based on AQI levels

### Humidity Fragment
- Current humidity percentage
- Wind speed information
- Atmospheric pressure details

### News Fragment
- Latest weather-related news
- Weather alerts and warnings

### Settings
- Language selection (English, Hindi, French)
- App preferences and configurations

## 🌍 Supported Languages

- 🇺🇸 English
- 🇮🇳 हिन्दी (Hindi)
- 🇫🇷 Français (French)

## 📂 Project Structure

```
Weather_App/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/myapplication123/
│   │   │   │   ├── MainActivity.java
│   │   │   │   ├── SplashScreen.java
│   │   │   │   ├── TemperatureFragment.java
│   │   │   │   ├── AqiFragment.java
│   │   │   │   ├── HumidityFragment.java
│   │   │   │   ├── NewsFragment.java
│   │   │   │   └── SettingsFragment.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   └── menu/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── gradle/
└── build.gradle
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Sarthak Singh**

- GitHub: [@SarthakSingh-96](https://github.com/SarthakSingh-96)

## 🙏 Acknowledgments

- Weather data providers
- Material Design team for UI components
- Android community for inspiration and support

## 📞 Support

If you have any questions or need help, please open an issue in the GitHub repository.

---

⭐ Star this repository if you find it helpful!

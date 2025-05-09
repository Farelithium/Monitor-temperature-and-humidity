# IoT Project - Temperature and Humidity Monitoring with DHT22 and ESP32 WROOM 🌡️💧

## Description 📜
This project uses the DHT22 sensor connected to an ESP32 WROOM to monitor temperature and humidity in real-time 🌡️💧. The data is sent to the Blynk app for display and monitoring 📱.

## Features ⚡
- Real-time monitoring of temperature and humidity 🌡️💧
- Data display on the Blynk app 📱
- Feedback on Blynk connection status 🌐

## Tools and Materials 🛠️
- **ESP32 WROOM** 🧑‍💻
- **DHT22 Sensor** 🌡️💧
- **Blynk Application** 📱
- **USB cable to connect ESP32 to the computer** 🔌
- **Blynk Token to link the app to ESP32** 🔑

## Steps 🔧

### 1. Set Up the Hardware 🖧
- Connect the DHT22 sensor to the ESP32 as follows:
  - **VCC** to **3V3** pin on ESP32 💡
  - **GND** to **GND** pin on ESP32 🔋
  - **Data** to **GPIO 23** (or another GPIO pin) 🔌

### 2. Install Libraries 📚
Make sure to install the following libraries:
- **ESP32 Library**: Select **Tools > Board > ESP32 Dev Module**.
- **DHT Sensor Library**: Install the **DHT sensor library** in Arduino IDE.

### 3. Set Up Blynk App 📱
- Download the Blynk app for iOS/Android 📲.
- Create a new project, select **ESP32** and **Wi-Fi** 🌐.
- Copy your **Auth Token** from the app and save it for the code 🔑.


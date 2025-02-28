# 🌱 IoT-Based Smart Agriculture System

## 📌 Introduction
This project focuses on **real-time water monitoring** in agriculture using IoT. The system utilizes **Arduino Uno, ESP8266, DHT11, pH sensor, and soil moisture sensor** to collect environmental data and transmit it to **ThingSpeak** for remote monitoring and analysis.

## 🔥 Features
- 📊 Real-time monitoring of soil moisture, temperature, humidity, and pH levels.
- 📡 Wireless data transmission using ESP8266.
- 🌍 Remote data visualization on **ThingSpeak**.
- ⚡ Energy-efficient and easy to implement.
- 🚀 Scalable for larger agricultural applications.

## 🛠️ Components Used
- Arduino Uno
- ESP8266 Wi-Fi Module
- DHT11 Temperature & Humidity Sensor
- Soil Moisture Sensor
- pH Sensor (PO)
- Jumper Wires & Breadboard

## 📷 System Architecture
```
[Soil Moisture Sensor] ---|
[DHT11 Sensor] ---------|---> [Arduino Uno] ---> [ESP8266] ---> [ThingSpeak]
[pH Sensor (PO)] -------|
```

## 📌 Installation & Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Smart-Agriculture-IoT.git
   cd Smart-Agriculture-IoT
   ```

2. **Install Arduino Libraries**
   - ESP8266WiFi
   - DHT
   - ThingSpeak
   - LiquidCrystal_I2C (if using an LCD display)

3. **Circuit Connection**
   - Connect **DHT11** → Digital Pin 2
   - Connect **Soil Moisture Sensor** → Analog Pin A0
   - Connect **pH Sensor (PO)** → Analog Pin A1
   - Connect **ESP8266** → Serial Pins (TX/RX)

4. **Update WiFi Credentials in Code**
   ```cpp
   const char* ssid = "Your_WiFi_SSID";
   const char* password = "Your_WiFi_Password";
   ```

5. **Upload the Code to Arduino Uno**
   - Open `smart_agriculture.ino` in the Arduino IDE.
   - Select the correct **board** and **port**.
   - Upload the code.

6. **Monitor Data on ThingSpeak**
   - Create a **ThingSpeak** account.
   - Get your **API Key** and update it in the code.
   - Visualize real-time data on your **ThingSpeak dashboard**.

## 📈 Data Visualization
ThingSpeak allows graphical representation of:
- 🌡️ Temperature & Humidity
- 💧 Soil Moisture Level
- 🏞️ pH Value

## 🏆 Future Enhancements
- 🌿 Automated irrigation system based on soil moisture data.
- 📲 Mobile app for real-time alerts.
- 🔋 Solar-powered implementation for energy efficiency.

## 🤝 Contributing
Feel free to **fork** this repository, create a new branch, and submit a pull request!



## 📩 Contact
📧 Email: [bhanjujoshi@gmail.com](mailto:bhanjujoshi@gmail.com)  
💻 GitHub: [prabhanjan26](https://github.com/prabhanjan26)

---
**"Empowering Agriculture with IoT for a Smarter Future!"** 🚀🌿


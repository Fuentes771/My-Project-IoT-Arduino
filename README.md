# 🌐 IoT Project: Smart Home Monitoring System

Welcome to the **Smart Home Monitoring System** repository!  
This project is part of our exploration into the Internet of Things (IoT) and demonstrates how to monitor and control home environments using sensors and microcontrollers.

## 🚀 Project Overview

This IoT system is designed to collect real-time data from various sensors (temperature, humidity, motion, etc.) and display it on a web dashboard. It also allows remote control of home appliances through actuators.

Key Features:
- Real-time sensor monitoring
- Web-based dashboard (using Node.js/React/Firebase)
- Remote control via mobile/web
- Notification alerts (email/Telegram)
- Low-power and efficient architecture

## 🧰 Technologies Used

- **Microcontroller**: ESP32 / Arduino Uno
- **Sensors**: DHT11 (temperature/humidity), PIR (motion), MQ-2 (gas)
- **Communication**: Wi-Fi (MQTT or HTTP)
- **Backend**: Firebase / Node.js
- **Frontend**: React / HTML + CSS + JavaScript
- **Mobile App (optional)**: MIT App Inventor / Flutter


## 🛠️ Installation & Setup

### Microcontroller Setup
1. Install Arduino IDE or PlatformIO.
2. Connect your ESP32/Arduino and upload the code from `firmware/`.
3. Configure your Wi-Fi credentials and MQTT/HTTP server in the code.

### Dashboard
```bash
cd dashboard/
npm install
npm start




#include <ESP8266WiFi.h>
#include <BlynkSimpleEsp8266.h>

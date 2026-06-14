# LiFi-Wireless-Data-Transmission
# Efficient and Secure High-Speed Data Transmission Using LiFi

## 📌 About
A hybrid LiFi-WiFi communication system capable of transmitting 
text, audio, and image data using visible light. 
Academic Project - B.E. ECE, P.S.R. Engineering College (2026)

## 🔧 Components Used
- ESP32 Devkit V1 (Transmitter)
- NodeMCU ESP8266 (Receiver)
- Laser Module
- LDR Sensor Module
- Solar Panel (Audio receiver)
- OLED Display
- PAM8403 Audio Amplifier
- 18650 Battery + TP4056 Charging Module

## ⚙️ How It Works
- Text → Mobile App → ESP32 → Laser → LDR → NodeMCU → OLED
- Audio → Audio Jack → Laser → Solar Panel → Amplifier → Speaker
- Image → Web Interface → ESP32 → WiFi → NodeMCU → Display

## 🛠️ Software Used
- Arduino IDE
- Custom Mobile App (Text Transmission)
- ESP32 Web Server (Image Transmission)
- Libraries: WiFi.h, ESP8266WiFi.h, OLED Display Library

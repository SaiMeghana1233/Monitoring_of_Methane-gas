# Methane Gas Detection System

## Description
This project monitors **methane gas**, **temperature**, and **humidity** in real-time using an **ESP8266**, **DHT11 sensor**, and a **buzzer**. Sensor data is sent to the **Blynk IoT app**, allowing remote monitoring and notifications. The system also triggers a local buzzer alarm if methane levels exceed a safety threshold.

**Use Case:**  
Ideal for home safety or small-scale industrial environments to detect methane leaks and prevent accidents.

---

## Features
- Real-time methane gas detection (ppm).
- Temperature and humidity measurement using DHT11.
- Sends data to Blynk virtual pins:  
  - **V1:** Gas level  
  - **V2:** Humidity  
  - **V3:** Temperature
- Local buzzer alarm for gas leakage alerts.
- Remote Blynk notifications if gas exceeds threshold (≥200 ppm).

---

## Hardware Required
- ESP8266 (NodeMCU/ESP-12E)  
- Methane gas sensor (analog output)  
- DHT11 temperature & humidity sensor  
- Buzzer  
- Jumper wires  
- Breadboard  

---

## Software Required
- [Arduino IDE](https://www.arduino.cc/en/software) or [VS Code + PlatformIO](https://platformio.org/)  
- Blynk App (iOS/Android)  

---

## Wiring
| Component       | ESP8266 Pin |
|-----------------|------------|
| Gas sensor analog output | A0         |
| DHT11 data      | D1         |
| Buzzer          | D2         |

---

## Installation
1. Clone the repository:
```bash
git clone https://github.com/username/Methane-Gas-Detection.git

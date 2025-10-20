# Weather-Monitoring-System-Project-

# 🌦️ IoT-Based Weather Monitoring System

An **IoT-based Weather Monitoring System** that measures environmental parameters such as **temperature, humidity, and light intensity** using the **ESP8266**, **DHT11 sensor**, and **LDR sensor**, and uploads the data to **ThingSpeak** for real-time monitoring.

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Components Used](#components-used)
- [Circuit Diagram](#circuit-diagram)
- [Working Principle](#working-principle)
- [Software Requirements](#software-requirements)
- [Output](#output)
- [Future Enhancements](#future-enhancements)
- [Team Members](#team-members)
---

## 🔍 Overview

This project monitors weather conditions by collecting temperature, humidity, and light data and uploads them to an IoT cloud platform. Users can view real-time environmental data and visualize trends using graphs on ThingSpeak.

---

## ✨ Features
- Real-time monitoring of weather parameters  
- IoT-based data visualization using ThingSpeak  
- Low-cost and energy-efficient system  
- Easy to set up and modify  
- Can be expanded with more sensors (e.g., rain, air quality)

---

## 🧰 Components Used
| Component | Quantity | Description |
|------------|-----------|-------------|
| ESP8266 NodeMCU | 1 | Wi-Fi module and microcontroller |
| DHT11 Sensor | 1 | Measures temperature & humidity |
| LDR Sensor | 1 | Measures light intensity |
| Jumper Wires | — | For connections |
| Breadboard | 1 | Prototyping platform |
| USB Cable | 1 | For power and programming |

---

## 🔌 Circuit Diagram

Below is the circuit used for this project:

![Circuit Diagram](Circuit%20Diagram.jpeg)

---

## ⚙️ Working Principle
1. The **DHT11 sensor** reads the temperature and humidity values.  
2. The **LDR sensor** measures light intensity based on resistance.  
3. The **ESP8266** collects the data and connects to Wi-Fi.  
4. The collected data is sent to **ThingSpeak** using its API key.  
5. Users can monitor live updates and view graphs on the ThingSpeak dashboard.

---

## 💻 Software Requirements
- **Arduino IDE**
- **ESP8266 Board Package**
- **DHT Sensor Library**
- **WiFi Library (ESP8266WiFi.h)**
- **ThingSpeak Library**

---

## 📊 Output
- Real-time values shown in Arduino Serial Monitor  
- Graphs visible on ThingSpeak dashboard for:
  - Temperature (°C)
  - Humidity (%)
  - Light Intensity (LDR Value)

---

## 🔮 Future Enhancements
- Add **rain sensor** or **BMP180** for pressure and altitude.  
- Integrate with **mobile app** or **Blynk dashboard**.  
- Enable **data logging** to SD card.  
- Implement **alert notifications** using IFTTT.

---

## 👩‍💻 Team Members
- **Fidah Fathima**  
- **Aleena Reni**  
- **Afaf Nourin Rizwan** 

---

## 💡 Inspiration
>**“IoT connects not just devices, but ideas — bringing real-time insights to life.”**

Google Drive Link For Demonstration Video : https://drive.google.com/file/d/1uXkWBRzC61p6PD0UDy1x7pJ3MHIJaBIT/view?usp=drive_link

---
 One attachment
  •  Scanned by Gmail

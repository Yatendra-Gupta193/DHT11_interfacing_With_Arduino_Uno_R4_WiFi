# 🌡️ DHT11 Temperature & Humidity Sensor using Arduino Uno R4 WiFi

## 📌 Project Overview -

This project demonstrates how to interface a **DHT11 sensor** with the **Arduino Uno R4 WiFi** to measure 
real-time **temperature** and **humidity** of the surrounding environment.

The sensor data is read using Arduino and displayed on the **Serial Monitor**.

---

## 🛠️ Components Used - 

- Arduino Uno R4 WiFi
- DHT11 Temperature & Humidity Sensor
- Jumper Wires
- Breadboard 

---

## 🔌 Circuit Connections -

| DHT11 Pin | Arduino Connection |
|----------|------------------|
| VCC      | 5V               |
| GND      | GND              |
| DATA     | Pin 2            |

---

## 💻 Code Explanation -

- The `DHT` library is used to interact with the sensor.
- Sensor is initialized in the `setup()` function.
- In the `loop()`:
  - Humidity and temperature values are read.
  - If values are invalid → error message is shown.
  - Otherwise, values are printed to Serial Monitor.

---

## 📷 Sample Output - 

- Humidity: 45% | Temperature: 28°C
- Humidity: 46% | Temperature: 29°C

---

## 🚀 Features -

- Real-time monitoring
- Error handling for sensor failure
- Simple and beginner-friendly implementation

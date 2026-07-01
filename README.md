  # ☀️ ESP32-Based Smart Solar Energy Management & Monitoring System

## 📌 Overview

This project is an IoT-based Smart Solar Energy Management and Monitoring System developed using the ESP32 microcontroller. The system provides real-time monitoring of solar and battery parameters while enabling intelligent energy management through a responsive web dashboard accessible from any smartphone connected to the ESP32 hotspot.

The project is designed for small off-grid solar power systems and demonstrates the integration of renewable energy, embedded systems, IoT, and automation.

---

# ✨ Features

* 📊 Real-Time Battery Monitoring

  * Battery Voltage
  * Battery Current
  * Battery Power
  * Battery Percentage

* ☀️ Real-Time Solar Monitoring

  * Solar Panel Voltage
  * Solar Panel Current
  * Solar Panel Power

* 🌐 ESP32 Wi-Fi Hotspot

  * No external router required
  * Mobile-friendly web dashboard

* 🔄 Dual Operating Modes

  * Manual Mode
  * Automatic Mode

* 🔋 Smart Battery Protection

  * Automatic inverter shutdown when battery level falls below the configured threshold.

* 💡 Smart Lighting System

  * Automatic day/night detection using an LDR sensor.
  * Motion-based lighting using a PIR sensor.
  * Automatic light control during nighttime.

* ⚡ Relay Control

  * Relay 1 – Inverter Control
  * Relay 2 – Smart Light Control

* 📱 Responsive Web Dashboard

  * Live system monitoring
  * Manual relay control
  * Battery status display
  * Solar status display
  * Environment monitoring

---

# 🛠 Hardware Used

* ESP32 Development Board
* 100W Solar Panel
* 20A Solar Charge Controller
* 12V Lead Acid Battery
* 2 × ACS712 Current Sensors
* 2 × 0–25V Voltage Sensor Modules
* PIR Motion Sensor
* LDR Light Sensor Module
* 2-Channel Relay Module (5V)
* DC-DC Buck Converter (12V to 5V)
* 12V Wi-Fi Router
* DC Fuse Distribution Board
* Connecting Wires and Terminal Blocks

---

# 💻 Software Used

* Arduino IDE
* C++
* HTML
* CSS
* JavaScript
* ESP32 Web Server Library

---

# ⚙️ System Operation

1. Solar energy charges the battery through the 20A solar charge controller.

2. The ESP32 continuously monitors battery and solar parameters.

3. Sensor data is processed and displayed on a mobile-friendly web dashboard.

4. Users can manually control the inverter and smart lighting.

5. In Automatic Mode:

   * The inverter is automatically disconnected when the battery level falls below the configured threshold.
   * The smart light turns ON only when it is dark and motion is detected.

---

# 📊 Parameters Monitored

* Battery Voltage (V)
* Battery Current (A)
* Battery Power (W)
* Battery Percentage (%)
* Solar Voltage (V)
* Solar Current (A)
* Solar Power (W)
* Motion Detection
* Day/Night Status
* Relay Status
* Operating Mode

---

# 🚀 Future Improvements

* Live data graphs
* SD card data logging
* Cloud monitoring
* Mobile application
* Notifications and alerts
* OTA firmware updates
* MPPT performance analysis
* AI-based energy optimization

---

# 📷 Project Preview

* Hardware Prototype
* Circuit Diagram
* Web Dashboard
* Mobile Interface
* Demonstration Video

---

# 👨‍💻 Author

**Theekshana Pradeep**

Electrical & Electronic Engineering Undergraduate

---

## ⭐ If you found this project useful, please consider giving it a star!

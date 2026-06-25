# CAN-CONTROLLED-AUTOMOTIVE-INFO-DISPLAY
Designed and implemented an embedded automotive monitoring system to display engine temperature, fuel level, and indicator status. The system uses the CAN protocol for reliable communication between sensor nodes and the dashboard display, providing a robust, scalable, and real-time vehicle monitoring solution.
# 🚗 Automotive Parameter Monitoring System Using CAN Protocol

An embedded automotive monitoring system developed using the **LPC2129 ARM7 microcontroller** and the **Controller Area Network (CAN) protocol**. The system enables reliable communication between multiple sensor nodes and a central dashboard to display critical vehicle parameters such as engine temperature, fuel level, and turn indicator status in real time.

---

## 📌 Project Overview

The Automotive Parameter Monitoring System is designed to simulate a vehicle dashboard using the CAN protocol for communication between distributed electronic control units (ECUs). Each node collects specific vehicle information and transmits it over the CAN bus to the main dashboard node, where the data is processed and displayed on an LCD.

This project demonstrates the implementation of a reliable in-vehicle communication network using embedded systems.

---

## ✨ Features

- Real-time Engine Temperature Monitoring
- Fuel Level Monitoring
- Left and Right Indicator Status Display
- Multi-node CAN Communication
- LCD-Based Dashboard Display
- Fault-tolerant and Reliable Data Transmission
- Low Latency Communication
- Modular Embedded Software Design

---

## 🛠 Hardware Requirements

- LPC2129 ARM7 Microcontroller (3 Nodes)
- MCP2551 CAN Transceiver
- DS18B20 Temperature Sensor
- Fuel Level Sensor (Potentiometer/ADC)
- 16x2 LCD Display
- LEDs (Left & Right Indicators)
- Push Buttons
- CAN Bus Wiring
- Power Supply
- USB-UART Converter

---

## 💻 Software Requirements

- Keil µVision IDE
- Flash Magic
- Embedded C
- Proteus (Optional for Simulation)

---

## 🏗 System Architecture

```

Temperature Sensor ──┐
│
Fuel Sensor ─────────┼──► CAN BUS ───► Dashboard Node ───► LCD Display
│
Indicator Switches ──┘

```

---

## 📡 CAN Network Configuration

| Node | Function |
|------|----------|
| Node 1 | Dashboard Display |
| Node 2 | Indicator Status |
| Node 3 | Engine Temperature & Fuel Level |

---

## ⚙ Working Principle

1. Sensors acquire vehicle parameters.
2. Individual nodes process sensor data.
3. CAN messages are transmitted over the CAN bus.
4. The dashboard node receives all CAN frames.
5. Vehicle information is displayed on the LCD in real time.

---

## 📷 Displayed Parameters

- Engine Temperature (°C)
- Fuel Level (%)
- Left Indicator Status
- Right Indicator Status

---

## 📂 Project Structure

```

Automotive-Parameter-Monitoring/
│
├── Main Node
│   ├── main.c
│   ├── can.c
│   ├── lcd.c
│
├── Sensor Node
│   ├── temperature.c
│   ├── fuel.c
│
├── Indicator Node
│   ├── indicator.c
│
├── Drivers
│   ├── can.h
│   ├── lcd.h
│   ├── ds18b20.h
│
└── README.md

```

---

## 🚀 Applications

- Automotive Dashboard Systems
- Vehicle Health Monitoring
- Industrial CAN Networks
- Embedded Communication Projects
- Automotive ECU Development

---

## 🔮 Future Enhancements

- Speed Monitoring
- RPM Display
- OBD-II Integration
- Bluetooth Connectivity
- Mobile Application Support
- GPS-Based Vehicle Tracking
- Data Logging to SD Card

---

## 📚 Technologies Used

- Embedded C
- ARM7 LPC2129
- CAN Protocol
- MCP2551 CAN Transceiver
- DS18B20 Sensor
- LCD Interfacing

---

## 🎯 Learning Outcomes

- ARM7 Programming
- CAN Bus Communication
- Embedded Driver Development
- Sensor Interfacing
- Real-Time Embedded Systems
- Automotive Communication Networks

---

## 👨‍💻 Author

**Nayeni Tagore**

Electronics and Communication Engineering  
Embedded Systems Enthusiast

---

## 📄 License

This project is intended for educational and learning purposes.

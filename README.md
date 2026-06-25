# CAN-CONTROLLED-AUTOMOTIVE-INFO-DISPLAY
Designed and implemented an embedded automotive monitoring system to display engine temperature, fuel level, and indicator status. The system uses the CAN protocol for reliable communication between sensor nodes and the dashboard display, providing a robust, scalable, and real-time vehicle monitoring solution.
# 🚗 CAN AUTOMOTIVE INFO DISPLAY System Using CAN Protocol

An embedded automotive monitoring system developed using the **LPC2129 ARM7 microcontroller** and the **Controller Area Network (CAN) protocol**. The system enables reliable communication between multiple sensor nodes and a central dashboard to display critical vehicle parameters such as engine temperature, fuel level, and turn indicator status in real time.

---

## 📌 Project Overview

The AUTOMOTIVE INFO DISPLAY System is designed to simulate a vehicle dashboard using the CAN protocol for communication between distributed electronic control units (ECUs). Each node collects specific information and transmits it over the CAN bus to the main dashboard node, where the data is processed and displayed on an LCD.

This project demonstrates the implementation of a reliable in-vehicle communication network using embedded systems.

---

## BLOCK DIAGRAM
<img width="979" height="712" alt="Blockdiagram" src="https://github.com/user-attachments/assets/3a48db0d-55dd-43c1-bc1f-33f127f9c032" />

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
- Fuel Level Sensor
- 16x2 LCD Display
- LEDs
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

## 📡 CAN Network Configuration

| Node | Function |
|------|----------|
| Node 1 | Dashboard Display & Engine Temp |
| Node 2 | Indicator node |
| Node 3 | Fuel Level node |

---

## ⚙ Working Principle

1. Sensors acquire vehicle parameters.
2. Individual nodes process sensor data.
3. CAN messages are transmitted over the CAN bus.
4. The dashboard node receives all CAN frames.
5. Vehicle information is displayed on the LCD in real time.

---

## CAN Network
<img width="960" height="1280" alt="CAN" src="https://github.com/user-attachments/assets/d54ce311-7736-442f-a1bb-b8162423826c" />

---

## Hardware Setup
<img width="972" height="590" alt="Hardware_setup" src="https://github.com/user-attachments/assets/47d10e06-e82b-4a05-ace8-dcc967613140" />

---

## 📷 Displayed Parameters

- Engine Temperature (°C)
- Fuel Level (%)
- Left Indicator Status
- Right Indicator Status

---

## 📂 Project Structure

```

CAN AUTOMOTIVE INFO DISPLAY/
│
├── MAIN NODE
│   ├── MainNode.c
│   ├── can.c
│   ├── lcd.c
│   ├── EXTINT.c
│   ├── ds18b20.c
│   ├── delay.c
│
├── FUEL NODE
│   ├── FuelNode.c   
│   ├── FUEL.c   
│   ├── can.c
│   ├── delay.c 
│
├── Indicator Node
│   ├── IndicatorNode.c
│   ├── INDICATOR.c
│   ├── delay.c
│   ├── can.c
│
├── Drivers
│   ├── can.h
│   ├── lcd.h
│   ├── ds18b20.h
│   ├── types.h
│   ├── delay.h
│   ├── can_defines.h
│   ├── fuel.h
│   ├── indicator.h
│   ├── lcd_defines.h
│
└── README.md

```

## LCD OUTPUT
<img width="1280" height="590" alt="lcd_output (1)" src="https://github.com/user-attachments/assets/1e3a7048-1af5-4a85-a59d-66c0fea7669e" />

---

## 🚀 Applications

- Automotive Dashboard Systems
- Vehicle Health Monitoring
- Industrial CAN Networks
- Embedded Communication Projects
- Automotive ECU Development

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

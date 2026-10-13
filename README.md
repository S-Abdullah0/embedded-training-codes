
# embedded-training-codes

Embedded Training Codes

A collection of embedded systems and IoT projects developed using ESP32, wireless communication, RTOS concepts, and cloud-connected dashboards. This repository contains practical firmware examples covering device communication, sensor integration, task scheduling, and IoT application development.

Repository Overview

This repository serves as a collection of hands-on embedded programming projects, focusing on firmware development, hardware interfacing, wireless communication, and real-time embedded applications.

Projects

1. LoRa Communication Using ESP32

File: "LORA communication.ino"

Demonstrates wireless communication between two ESP32 boards using LoRa transceiver modules. The ESP32 communicates with the LoRa module over SPI to transmit and receive messages without requiring Wi-Fi or an internet connection.

Key concepts:

- LoRa wireless communication
- SPI-based hardware interfacing
- Transmitter and receiver implementation
- Bidirectional message exchange
- Serial Monitor debugging

2. CAN Module Communication

File: "CAN module communicating.ino"

Explores communication between embedded devices using the Controller Area Network (CAN) protocol with a compatible CAN controller module.

Key concepts:

- CAN bus communication
- Embedded device networking
- Message transmission and reception
- Hardware interface configuration

3. IoT Using MQTT Web Dashboard

File: "IOT using mqtt webdashboard.ino"

Demonstrates an IoT communication workflow using MQTT messaging and a web dashboard for monitoring or controlling connected devices.

Key concepts:

- MQTT publish/subscribe messaging
- IoT device connectivity
- Remote monitoring and control
- Dashboard integration

4. Adafruit Dashboard

File: "Adafruit dashboard.ino"

Explores connecting embedded hardware to an Adafruit-based dashboard for remote monitoring and device interaction.

Key concepts:

- IoT dashboard integration
- Connected-device monitoring
- Remote control
- Cloud-connected embedded applications

5. RTOS Using Task Priority

File: "RTOS using task priority.ino"

Demonstrates task-based firmware design using an RTOS-capable microcontroller environment, focusing on task priorities and concurrent execution.

Key concepts:

- Real-time operating system fundamentals
- Task creation and scheduling
- Task priorities
- Concurrent embedded processing

6. Voice Control in Adafruit

File: "voice control in adafruit.ino"

Explores voice-based interaction with an IoT dashboard or connected embedded device.

Key concepts:

- Voice-driven device interaction
- IoT control interfaces
- Embedded-device integration
- Remote operation

Technologies and Concepts

- Microcontrollers: ESP32 and compatible development boards
- Programming: Arduino C/C++
- Wireless communication: LoRa
- Communication protocols: SPI, CAN, MQTT
- Embedded software: RTOS task scheduling and prioritization
- IoT platforms: Adafruit dashboard and web dashboards
- Debugging: Arduino Serial Monitor

The exact hardware, libraries, network configuration, and platform requirements vary by project.

Getting Started

Requirements

- Arduino IDE
- ESP32 board support package, where applicable
- Required libraries for each individual project
- Compatible development boards and communication modules
- USB cables and jumper wires
- Internet access for projects that use cloud dashboards or MQTT brokers

Setup Instructions

1. Clone or download this repository.
2. Open the required ".ino" file in Arduino IDE.
3. Install the libraries required by that sketch.
4. Select the appropriate development board and COM port.
5. Configure the required pins, network credentials, broker details, or dashboard settings.
6. Upload the program to the development board.
7. Open Serial Monitor and select the baud rate configured in the sketch.
8. Test the project's functionality using its corresponding hardware.

Learning Objectives

This repository supports practical learning in:

- Embedded firmware development
- Microcontroller peripheral interfacing
- Wireless device-to-device communication
- IoT messaging and dashboard integration
- Real-time task scheduling
- Hardware debugging and system integration

Future Improvements

- Add wiring diagrams and hardware photographs for each project.
- Document library dependencies and configuration steps.
- Include sample outputs and testing results.
- Add error handling and communication reliability features.
- Expand the collection with firmware security and embedded networking projects.

Repository Structure

embedded-training-codes/
├── Adafruit dashboard.ino
├── CAN module communicating.ino
├── IOT using mqtt webdashboard.ino
├── LORA communication.ino
├── RTOS using task priority.ino
├── voice control in adafruit.ino
└── README.md

Author

S-Abdullah0

GitHub: "@S-Abdullah0" (https://github.com/S-Abdullah0)

License

A license has not yet been specified. Add a "LICENSE" file if you want to define how others may use, modify, and distribute these projects.
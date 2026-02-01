# Project Plan Presentation (PPP)

## Project Title
Smart Parking Availability System (IoT-Based)

---

## Problem Statement

Students using parking garages often waste time driving through multiple levels trying to find an available parking spot. There is currently no system that informs users whether a garage is full before they enter. This results in wasted time, increased traffic congestion, and frustration.

---

## Project Goal

The goal of this project is to design an IoT-based system that collects sensor data and transmits it wirelessly to a backend system, where it can be processed and displayed to users as parking availability information.

---

## Project Context (Provided IoT Skeleton)

This project uses the provided IoT hardware skeleton:

- **Arduino Nano** as the main controller
- **ESP32-C6** for WiFi/BLE communication
- **TMP102 I2C Temperature Sensor** as the sensing component

The temperature sensor will be used as a **representative sensor** to simulate parking-related data for system design, data flow, and communication purposes.

---

## Proposed Solution

The system will collect sensor data using the TMP102 sensor, process it using the Arduino Nano, and transmit the data wirelessly through the ESP32-C6 module. The data will then be sent to a backend server, which determines availability status and makes it accessible to users through a web-based interface.

---

## Key Features

1. Sensor data collection using TMP102
2. Microcontroller-based data processing
3. Wireless data transmission using ESP32-C6
4. Backend system for data handling
5. Web interface to display availability status

---

## Technologies (Planned)

### Hardware
- Arduino Nano (controller)
- ESP32-C6 (WiFi/BLE)
- TMP102 I2C Temperature Sensor

### Software
- Arduino C/C++
- Node.js with Express (backend)
- MongoDB (database)
- React (frontend)

---

## Architecture Overview

1. TMP102 sensor collects environmental data
2. Arduino Nano reads and processes sensor data
3. ESP32-C6 transmits data via WiFi/BLE
4. Backend server processes incoming data
5. Frontend application displays availability status

(Architecture diagram will be added later.)

---

## Project Plan & Milestones

### Sprint 1
- Understand IoT hardware and setup
- Define requirements and data flow
- Basic sensor communication testing

### Sprint 2
- Wireless data transmission
- Backend API development
- Frontend interface creation

### Sprint 3
- Integration testing
- System refinement
- Final documentation

---

## Progress Tracking & Metrics

Progress will be tracked using:
- GitHub commits
- Sprint milestone completion
- Successful sensor data transmission
- System integration checkpoints

---

## Risks & Mitigation

### Risks
- Learning curve with IoT hardware
- Wireless communication issues
- Time constraints

### Mitigation Strategies
- Use AI tools for troubleshooting and learning
- Simulate data where needed
- Incremental testing of each system component

---

## PPP Readiness Statement

All planning and system design information has been documented in this repository.  
The project is ready for PPP discussion, review, and feedback.

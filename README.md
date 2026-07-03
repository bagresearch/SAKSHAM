# SAKSHAM

## Smart Adaptive Knowledge-based Soil Hydration & Automation Module

> **Developed by Saswata Bag**\
> **SB.Chetak Innovation**

------------------------------------------------------------------------

## Overview

SAKSHAM is an IoT-enabled smart irrigation system that monitors soil
moisture, temperature, humidity, rainfall, and ambient light to automate
irrigation. The platform uses embedded sensing and adaptive control
logic to prevent overwatering, reduce freshwater consumption, improve
plant health, and support sustainable irrigation practices.

## Features

-   Automatic irrigation control
-   Soil moisture monitoring
-   Temperature & humidity sensing
-   Rain detection
-   Ambient light sensing
-   Relay-controlled water pump
-   LCD status display
-   IoT-ready architecture
-   Low-cost and scalable

## Hardware

-   ESP32 / Arduino
-   Soil Moisture Sensor
-   DHT11/DHT22
-   Rain Sensor
-   LDR
-   Relay Module
-   Water Pump
-   LCD Display

## Software

-   Arduino IDE
-   Embedded C/C++
-   ESP32 Framework

## Architecture

``` mermaid
graph LR
A[Soil Sensor]-->E[ESP32]
B[DHT]-->E
C[Rain]-->E
D[LDR]-->E
E-->F[Relay]
F-->G[Pump]
E-->H[LCD]
```

## Workflow

``` mermaid
flowchart TD
A(Start)-->B(Read Sensors)
B-->C{Need Water?}
C--Yes-->D(Pump ON)
C--No-->E(Pump OFF)
D-->F(Update LCD)
E-->F
F-->B
```

## Applications

-   Smart Irrigation
-   Home Gardens
-   Greenhouses
-   Nurseries
-   Research
-   Education

## Future Scope

-   Mobile App
-   Cloud Dashboard
-   AI Prediction
-   Weather Integration
-   LoRa Connectivity

## Repository Structure

``` text
SAKSHAM/
├── Firmware/
├── Hardware/
├── Circuit_Diagram/
├── Documentation/
├── Images/
├── LICENSE
└── README.md
```

## License

Copyright © 2026 **SB.Chetak Innovation**

Licensed under the BagResearch License.

## Developer

**Saswata Bag**

Embedded Systems Engineer \| IoT Developer \| Hardware Innovator

Website: https://www.bagresearch.co.in Email: projects@bagresearch.co.in

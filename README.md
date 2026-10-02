# ESP32 Environmental Monitoring System

## Overview

This project is an ESP32-based temperature and humidity monitoring system using a DHT22 sensor. The firmware periodically reads environmental data and displays the measured temperature and humidity through the Serial Monitor.

The complete system was developed and validated using the Wokwi online hardware simulator.

## Objectives

- Interface a DHT22 sensor with an ESP32.
- Acquire temperature and humidity data.
- Process sensor readings using Embedded C/C++.
- Display real-time sensor readings through serial communication.
- Validate the embedded firmware using simulation.

## Hardware Used

- ESP32 Development Board
- DHT22 Temperature and Humidity Sensor

## Software and Tools

- Embedded C/C++
- Arduino Framework
- Wokwi Simulator
- Serial Monitor

## Circuit Connections

| DHT22 Pin | ESP32 |
|---|---|
| VCC | 3V3 |
| DATA | GPIO 15 |
| NC | Not Connected |
| GND | GND |

## Working

The DHT22 sensor is connected to GPIO 15 of the ESP32. The ESP32 periodically reads the temperature and humidity values from the sensor and sends the readings to the Serial Monitor at 115200 baud.

The sensor is sampled every 2 seconds.

## Sample Output

```text
ESP32 Environmental Monitoring System
------------------------------------
Temperature: 24.00 °C
Humidity: 40.00 %
------------------------------------
Temperature: 24.00 °C
Humidity: 40.00 %
------------------------------------

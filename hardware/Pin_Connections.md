# ESP32 Pin Connections

This document describes the GPIO pin connections used in the ESP32-based Smart Farming Robot.

| Component | ESP32 Pin | Description |
|-----------|-----------|-------------|
| DHT22 Sensor | GPIO 4 | Temperature and humidity sensing |
| Soil Moisture Sensor | GPIO 34 (ADC) | Reads soil moisture level |
| Water Level Sensor | GPIO 32 (ADC) | Monitors water tank level |
| Ultrasonic Sensor (Trigger) | GPIO 5 | Sends ultrasonic pulse |
| Ultrasonic Sensor (Echo) | GPIO 18 | Receives ultrasonic signal |
| Relay Module | GPIO 23 | Controls the water pump |
| Soil Arm Servo | GPIO 15 | Moves the soil moisture sensor arm |
| Ultrasonic Servo | GPIO 2 | Rotates the ultrasonic sensor |
| Seed Dispensing Servo | GPIO 19 | Controls the seed dispensing mechanism |
| Left Motor Enable (ENA) | GPIO 25 | Controls left motor speed (PWM) |
| Right Motor Enable (ENB) | GPIO 33 | Controls right motor speed (PWM) |
| Motor Driver IN1 | GPIO 26 | Left motor direction |
| Motor Driver IN2 | GPIO 27 | Left motor direction |
| Motor Driver IN3 | GPIO 14 | Right motor direction |
| Motor Driver IN4 | GPIO 12 | Right motor direction |

## Communication

- Wi-Fi (ESP32 Access Point)
- ESP32 Web Server

## Development Environment

- Arduino IDE
- ESP32 Board Package

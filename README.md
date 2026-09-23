# Real-Time Player Tracking IoT

An IoT-based real-time player tracking system designed for monitoring and tracking player movements using ESP8266, sensors, and wireless communication.

## Overview

This project combines computer vision, IoT hardware, and a web-based dashboard to track player movement in real time.

The system uses an ESP8266-based hardware setup with servo motors and an OLED display, while a Python Flask backend handles player tracking, communication, and system control.

## Features

- Real-time player position tracking
- Computer vision-based player detection
- ESP8266-based IoT control
- Servo motor control
- WebSocket communication between the Python server and ESP8266
- Real-time camera feed
- Multiple training modes
- Custom servo controls
- Voice feedback and coaching
- OLED display for system status
- Web-based control dashboard

## Technologies Used

### Hardware
- ESP8266
- Servo motors
- OLED display
- Sensors

### Software
- Python
- Flask
- OpenCV
- MediaPipe
- WebSocket
- HTML
- CSS
- JavaScript

## Project Structure

```text
Real-Time-Player-Tracking-IoT/
│
├── player_tracking.ino
├── server.py
├── README.md
│
└── templates/
    └── index.html

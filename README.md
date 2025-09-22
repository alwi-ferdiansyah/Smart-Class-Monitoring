# 🏫 Smart Class Monitoring System

## Overview
Integrated smart classroom monitoring system using Python, DHT22 sensors, UV sensor, relays, and YOLOv4-tiny.  
Monitors temperature, humidity, UV, and detects people to control lighting automatically.  
Data is published to MQTT broker for real-time monitoring.

## Features
- Real-time temperature, humidity, and UV monitoring
- People detection with YOLOv4-tiny
- Automatic lighting control based on occupancy
- MQTT integration for remote data monitoring

## Hardware
- Raspberry Pi / compatible board
- DHT22 sensor
- UV sensor
- Relay-controlled lights
- Webcam or Pi Camera

## Software
- Python 3.x
- OpenCV, Numpy
- Adafruit DHT library
- Paho MQTT

## Author
Mohammad Alwi Ferdiansyah Alfarizi

## Usage
1. Install required libraries: `pip install -r requirements.txt`
2. Connect sensors and relays to board pins
3. Place YOLO model files in `models/`
4. Run: `python src/smart_class.py`

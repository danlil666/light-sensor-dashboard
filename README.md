# Light Sensor Dashboard

A real-time light sensor monitoring system using:
- Seeed XIAO ESP32S3
- VEML7700 light sensor
- CircuitPython
- Web dashboard

## Hardware Setup
- Seeed XIAO ESP32S3
- VEML7700 Light Sensor Breakout

## Software Requirements
Required CircuitPython libraries:
- adafruit_veml7700
- adafruit_httpserver
- adafruit_bus_device

## Installation
1. Connect the VEML7700 to XIAO ESP32S3
2. Copy the required libraries to CIRCUITPY/lib
3. Copy code.py to CIRCUITPY drive
4. Update WiFi credentials in code.py

## Usage
1. Power up the device
2. Connect to the device's IP address
3. View real-time light sensor data

## Project Structure
- `device/code.py`: CircuitPython code for XIAO ESP32S3
- `website/index.html`: Web dashboard

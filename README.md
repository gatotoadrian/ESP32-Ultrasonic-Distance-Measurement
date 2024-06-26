# ESP32 Ultrasonic Distance Measurement

This project demonstrates how to use an ESP32 with an ultrasonic sensor (HC-SR04) to measure distances. The measured distance is displayed in both centimeters and inches on the Serial Monitor.

## Requirements

- ESP32 board (NodeMCU-32S or similar)
- HC-SR04 Ultrasonic Sensor
- Arduino IDE with ESP32 board support

## Libraries

Make sure to install the necessary libraries via the Arduino Library Manager:
- None specific are needed beyond the built-in ESP32 and Arduino core libraries.

## Hardware Setup

1. **Ultrasonic Sensor Connections:**
   - VCC to 5V
   - GND to GND
   - Trig to GPIO 5
   - Echo to GPIO 18


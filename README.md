IoT-Based Smart Parking System using NodeMCU (ESP8266)

Project Overview:---->
The Smart Parking System is an IoT project that helps monitor parking slot availability automatically. It uses NodeMCU (ESP8266), IR sensors, an ultrasonic sensor, and servo motors to detect vehicles, control the parking gate, and display parking status through the ThingSpeak cloud platform.

The system automatically detects vehicle entry and exit, monitors parking slot availability, controls the parking gate, and uploads real-time parking data to the ThingSpeak Cloud. Users can monitor parking status remotely through the cloud dashboard and receive instant notifications via a Telegram Bot.This project aims to reduce traffic congestion, save fuel and time, minimize manual supervision, and improve parking efficiency through IoT-based automation. It is a low-cost, scalable, and eco-friendly solution suitable for smart cities and modern parking infrastructure.

Objectives:--->

- Detect vehicle entry and exit automatically.
- Monitor parking slot availability in real time.
- Upload parking data to the cloud using Wi-Fi.
- Automate gate operation using servo motors.
- Reduce traffic congestion and fuel consumption.
- Improve parking management through IoT technology.

 Hardware Components---->
 - NodeMCU ESP8266
- Ultrasonic Sensor (HC-SR04)
- IR Sensors
- Servo Motors
- RFID RC522 Module
- Breadboard
- Jumper Wires
- USB Cable
- External 5V Power Supply.
Working Principle---->
1. A vehicle approaches the parking entrance.
2. The ultrasonic sensor detects the vehicle.
3. NodeMCU checks the availability of parking slots.
4. If a parking slot is available:
   - The servo motor opens the gate.
   - The vehicle enters the parking area.
5. IR sensors detect whether parking slots are occupied or empty.
6. NodeMCU sends the parking data to the ThingSpeak Cloud.
7. Users can monitor parking availability remotely through the cloud dashboard.
8. The Telegram Bot can notify users about available and occupied parking slots.


 Applications-->

- Smart Cities
- Shopping Malls
- Hospitals
- Airports
- Universities
- Office Buildings
- Residential Apartments

 Advantages-->

- Real-time parking monitoring
- Automatic gate control
- Reduces traffic congestion
- Saves fuel and time
- Low-cost implementation
- Easy to expand for large parking areas
- User-friendly interface

This project demonstrates how IoT can be used to automate parking management by providing real-time parking slot monitoring and gate control. It offers a simple, low-cost, and scalable solution that can be further enhanced with advanced features in the future.

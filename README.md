# Obstacle Avoiding Robot Car with Remote and Voice Control

## Introduction
This project showcases an IoT-enabled **Obstacle Avoiding Robot Car**, designed to be controlled remotely via Bluetooth using a smartphone or tablet. The robot autonomously navigates by avoiding obstacles and can also be controlled using voice commands like "Turn Left" or "Move Forward." 

The project combines hardware components, Arduino programming, and mobile app integration to demonstrate practical applications of IoT in robotics.

---

## Features
- **Autonomous Navigation**: Detects and avoids obstacles using an ultrasonic sensor.
- **Bluetooth Control**: Pair and control the robot remotely through a mobile app.
- **Voice Commands**: Responds to spoken instructions for navigation.
- **Compact Design**: Powered by a lightweight battery system.

---

## Components Used
1. **Arduino Uno**: Microcontroller unit for processing commands and controlling sensors and motors.
2. **HC-05 Bluetooth Module**: Enables communication with the mobile app.
3. **HC-SR04 Ultrasonic Sensor**: Detects obstacles in the robot’s path.
4. **Motor Driver Shield**: Controls four DC motors for movement.
5. **Servo Motor**: Rotates the ultrasonic sensor for enhanced obstacle detection.
6. **4 x Motors**: Drives the robot’s wheels.
7. **2 x 3.7V Batteries**: Provides power to the components.
8. **Remote Controller Mobile App**: Custom-built APK file for controlling the robot.

---

## Getting Started

### Prerequisites
- **Arduino IDE**: To upload the provided Arduino code to the microcontroller.
- **Bluetooth-enabled Smartphone or Tablet**: For pairing and remote control.
- **Motor Shield**: For driving the DC motors.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

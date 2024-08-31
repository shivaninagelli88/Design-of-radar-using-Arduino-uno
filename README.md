# Design-of-radar-using-Arduino-uno

# Radar Design Using Arduino Uno

This project is a radar system designed using an Arduino Uno, an ultrasonic sensor, and a servo motor. The radar can detect objects within a certain range and display the detected distance on a processing unit software using Java.

## Table of Contents

- [Project Overview](#project-overview)
- [Components Used](#components-used)
- [Circuit Diagram](#circuit-diagram)
- [Code](#code)
- [Installation](#installation)
- [Usage](#usage)
- [Challenges Faced](#challenges-faced)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

## Project Overview

The radar system is designed to simulate the functionality of a basic radar using Arduino. It rotates the ultrasonic sensor using a servo motor, measures the distance to an object, and displays the data on a visual interface developed using Processing (Java-based environment).

## Components Used

- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90)
- Jumper Wires
- Breadboard
- USB Cable (for connecting Arduino to the computer)

## Circuit Diagram
https://techatronic.com/wp-content/uploads/2021/01/Radar-System-new.jpg

### Connections:
- **Ultrasonic Sensor:**
  - VCC to Arduino 5V
  - GND to Arduino GND
  - Trig to Arduino Pin 9
  - Echo to Arduino Pin 8
- **Servo Motor:**
  - VCC to Arduino 5V
  - GND to Arduino GND
  - Signal to Arduino Pin 10

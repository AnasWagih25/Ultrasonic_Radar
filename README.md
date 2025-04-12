# Ultrasonic Sensor with Arduino Uno and Servo Motor

This project demonstrates how to use an **ultrasonic sensor (HC-SR04)** with an **Arduino Uno** to detect the distance of nearby objects and control a **servo motor** based on that distance.

## 📦 Components Required

- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 or MG996R Servo Motor
- Breadboard and jumper wires
- USB cable for programming the Arduino
- (Optional) External power supply for high-torque servos

## 🔌 Wiring Overview

### Ultrasonic Sensor (HC-SR04):
- **VCC** ➜ 5V (Arduino)
- **GND** ➜ GND (Arduino)
- **TRIG** ➜ Digital Pin 9 (Arduino)
- **ECHO** ➜ Digital Pin 10 (Arduino)

### Servo Motor:
- **VCC** ➜ 5V (Arduino or external power source)
- **GND** ➜ Common GND with Arduino
- **Signal** ➜ Digital Pin 11 (Arduino)

> ⚠️ Note: For more reliable servo operation, consider using a dedicated power source for the motor to avoid voltage drops on the Arduino.

## 🧠 How It Works

1. The ultrasonic sensor emits an ultrasonic pulse and waits for it to bounce back from an object.
2. The time it takes for the echo to return is used to calculate the distance.
3. The Arduino processes this data and sends a signal to the servo motor.
4. The servo motor rotates to a position based on the measured distance — closer objects can result in different angles of rotation.

## 🌟 Applications

- Basic obstacle detection systems
- Robotic arms or turrets that follow motion
- Object tracking and radar-like systems
- Educational tools for learning electronics and Arduino

## 📁 Project Status

✅ Fully working prototype  
⚙️ Can be expanded with additional features like:  
- Buzzer/LED indicators  
- OLED display for showing distance  
- Sweep scanning with dynamic servo movement  

## 📄 License

This project is open source and available under the MIT License.

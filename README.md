# Arduino Smart Vacuum Robot 

An **Arduino-based smart vacuum cleaner robot** capable of operating in both **autonomous mode** and **Bluetooth-controlled manual mode**.  
The system uses sensors and wireless communication to reduce human effort in floor cleaning.

---

##  Project Overview

This project presents the design and implementation of a **smart robotic vacuum cleaner** using an **Arduino microcontroller**.  
The robot can clean floors automatically by detecting obstacles using an ultrasonic sensor or can be manually controlled through an **Android smartphone via Bluetooth**.

The main objective of this project is to demonstrate the integration of **embedded systems, robotics, sensors, and wireless communication** in a real-world automation application.

---

##  Features

-  Dual operation modes: **Automatic & Manual**
-  Android smartphone control using **Bluetooth (HC-05)**
-  Obstacle detection using **Ultrasonic sensor**
-  Autonomous navigation and obstacle avoidance
-  Integrated mini vacuum fan for dust suction
-  DC motor speed and direction control using motor driver

---

##  Hardware Requirements

- Arduino Uno
- HC-05 Bluetooth Module
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- DC Gear Motors
- Motor Driver (L298N / Arduino Motor Shield)
- Mini Vacuum Fan
- Battery
- Jumper Wires
- Robot Chassis and Wheels

---

##  Software Requirements

- Arduino IDE
- Android Bluetooth Controller App

---

##  System Architecture

- The **Arduino** acts as the main controller of the system
- The **Bluetooth module** enables wireless communication with an Android phone
- The **ultrasonic sensor** detects obstacles and assists in autonomous navigation
- The **motor driver** controls the direction and speed of the DC motors
- The **vacuum fan** performs dust suction during movement

---

##  Working Modes

###  Automatic Mode
- Activated via Bluetooth command
- Robot moves autonomously
- Ultrasonic sensor detects obstacles
- Automatically changes direction to avoid collisions
- Vacuum fan runs continuously

###  Manual Mode
- Robot controlled using an Android smartphone
- User can send commands for movement
- Suitable for targeted cleaning areas

---

##  Bluetooth Command Mapping

| Command | Action |
|-------|--------|
| `A` | Enable Automatic Mode |
| `M` | Enable Manual Mode |
| `F` | Move Forward |
| `B` | Move Backward |
| `L` | Turn Left |
| `R` | Turn Right |
| `S` | Stop |

---

##  Flow of Operation

1. System power ON
2. Bluetooth connection established with Android app
3. User selects **Automatic** or **Manual** mode
4. Robot performs cleaning based on selected mode
5. Obstacle avoidance handled automatically in Auto mode

---

##  Applications

- Smart home automation
- Robotic cleaning systems
- Embedded systems learning
- Academic mini and final-year projects
- Robotics research fundamentals


# Quadruped Robot Dog version1

A Bluetooth-controlled quadruped robot dog built using an ESP32 microcontroller and SG90 servo motors.

The robot features 1 degree of freedom (DOF) per leg and is controlled wirelessly through a smartphone using the Dabble application. It can perform basic locomotion and interactive actions such as walking, turning, sitting, laying down, handshaking, and jumping.

The robot was first designed in Onshape and then built as a physical prototype to explore robotics, embedded systems, gait generation, and wireless control.

---

## Features

* Forward movement
* Backward movement
* Left turn
* Right turn
* Sit
* Lay down
* Handshake
* Jump
* Wireless smartphone control using Dabble

---

## Hardware Used

* ESP32 Development Board
* 4 × SG90 Servo Motors
* External Power Supply
* Custom Chassis
* Smartphone for Wireless Control

---

## Software Used

* Arduino IDE
* ESP32Servo Library
* DabbleESP32 Library
* Onshape (CAD Design)

---

## Servo Connections

| Servo       | ESP32 Pin |
| ----------- | --------- |
| Front Right | 22        |
| Front Left  | 21        |
| Back Right  | 18        |
| Back Left   | 19        |

---

## CAD Design

The robot was first designed and modeled in Onshape before building the physical prototype.

(Add CAD image here)

---

## Project Images

(Add images of the physical robot here)

---

## Demonstration

(Add walking and action videos here)

---

## What I Learned

Through this project I gained hands-on experience with:

* Embedded Systems
* ESP32 Programming
* Servo Control
* Bluetooth Communication
* Gait Generation
* CAD Design using Onshape
* Robotics Prototyping
* Hardware Debugging

---

## Future Improvements

* Increase the degrees of freedom (DOF) of each leg for more natural and stable movement.
* Integrate a robotic arm on the quadruped platform for object manipulation tasks.
* Add Computer Vision using OpenCV.
* Implement object tracking and autonomous navigation.
* Improve gait generation and walking efficiency.
* Design and manufacture a stronger chassis using 3D printed parts.

---

## Repository Structure

```text
Quadruped-Robot-Dog/
│
├── code/
│   └── RobotDog.ino
│
├── images/
│   ├── CAD_Model.png
│   └── Robot_Photos.jpg
│
├── videos/
│   └── Demo.mp4
│
└── README.md
```

## Author

Samyak Kambale

First-year EEE Student | Robotics & Computer Vision Enthusiast

Building quadruped robots, robotic arms, and computer vision projects using ESP32, Python, OpenCV, and Onshape.

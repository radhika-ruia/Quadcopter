
### Smart Glove-Controlled Drone with Autonomous Return Home

This project is a gesture-controlled drone system designed to be:
- Intuitive to fly via a **glove controller**
- Safe with real-time **obstacle avoidance**
- Resilient through a **fail-safe protocol**
- Intelligent via a **return-to-home feature powered by a smart pathfinding algorithm**

---

## Features

1. **Glove-Based Control** – Control the drone via hand gestures using accelerometers and NRF24.
2. **Obstacle Avoidance** – Ultrasonic sensors detect and avoid obstacles mid-flight.
3. **Fail-Safe Protocol** – On signal loss or critical battery, drone hovers or lands safely.
4. **Return-to-Home Optimizer** – Uses a pathfinding algorithm to autonomously find its way back, avoiding barriers.

---

## Demo

> Add demo GIFs/videos here

---

## Algorithms Used

- Bug2 Algorithm (for return home navigation)
- Basic PID stabilization (optional)
- Glove gesture recognition via accelerometer thresholding

---

## Tech Stack

- Microcontrollers: Arduino Nano, ATmega328P
- Communication: NRF24L01
- Sensors: Ultrasonic (HC-SR04), Accelerometer (MPU6050)
- Power: LiPo Battery, ESCs, Brushless Motors
- Software: Arduino IDE, Python (for simulation), Fritzing

---

## Repo Structure

See full directory tree above in this README.

---

## Simulations

Check `/algorithms` and `/simulations` for Python-based demos of the smart return-home pathfinder.

---

## Getting Started

See [`docs/setup-guide.md`](docs/setup-guide.md) for circuit diagrams and upload instructions.

---

## Credits

Created by Radhika Ruia — part of a 3-month passion project to showcase embedded intelligence in flight systems.

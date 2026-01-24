# 🤖 WRO 2026 Autonomous Robot

Autonomous robot developed for the **World Robot Olympiad (WRO) 2026** season.  
This project focuses on precise motion control, sensor fusion, and reliable autonomous decision-making.

---

## 📌 Overview

This robot is designed to:
- Navigate the WRO 2026 competition field autonomously
- Perform accurate movements using **DC motors with encoders**
- Execute task logic based on sensor input
- Maintain repeatability and reliability under competition conditions

The system uses **closed-loop control** to achieve stepper-like precision from DC gear motors.

---

## 🧠 Key Features

- ⚙️ **Encoder-based position control**
- 🔄 PID control for smooth and accurate motion
- 📏 Stepper-like movement using DC motors
- 🧭 Modular software architecture
- 🧪 Tunable parameters for rapid testing
- 🧯 Failsafe motor stop logic

---

## 🧰 Hardware Components

| Component | Description |
|--------|------------|
| Microcontroller | ESP32 |
| Motors | 12V N20 DC Gear Motors with Hall Encoders |
| Motor Driver | TB6612FNG |
| Encoders | Quadrature Hall sensors |
| Power | Li-ion / LiPo Battery Pack |
| Chassis | Custom / LEGO / 3D Printed (configurable) |
| Sensors | *(To be defined based on WRO 2026 rules)* |

---

## 📐 Motion Control Strategy

Unlike traditional stepper motors, this robot uses **DC motors with encoders** to achieve:

- Absolute position control
- Encoder count–based movement
- Software-defined “steps”
- No missed steps due to feedback correction

**Encoder resolution:**

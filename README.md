# Mobile Charging Port using Silicon Controlled Rectifier (SCR)
This project is a mini project for the course Fundamentals of Electronic Devices and Circuits 
It demonstrates an SCR-based mobile charging circuit, that converts AC to regulated DC for safe, efficient charging. It prevents overcharging, ensures stable output, and was tested via simulation and PCB prototype, with scope for smart upgrades and multi-port use.

## 📌 Project Overview
- Converts **AC to regulated DC** for mobile charging.
- Uses an **SCR as a controlled switch** to regulate current flow and prevent overcharging.
- Incorporates supporting components such as a transformer, rectifier, Zener diode, and TIP122 transistor.
- Designed, simulated, and tested using both **Falstad Circuit Simulator** and **hardware prototype (PCB)**.

## ⚡ Features
- Stable DC output for safe mobile charging.
- Overcharge protection via SCR-based control.
- Compact PCB implementation with neat soldering.
- Scalable design that can be extended for:
  - Higher-capacity batteries
  - Multi-port mobile charging stations
  - Integration with microcontrollers (Arduino/ESP32) for smart charging

## 🔧 Components Used
- SCR (Silicon Controlled Rectifier)
- TIP122 Power Transistor
- Transformer (230V → 9V, 2A)
- Diodes (Bridge Rectifier)
- Zener Diode (Voltage Regulation)
- Capacitor (Filtering)
- Resistors

## 🖥️ Software Simulation
- **Tool Used:** [Falstad Circuit Simulator](https://falstad.com/circuit/)  
- Simulated the circuit design to verify stability, output characteristics, and component functionality before hardware implementation.

## 🛠️ Hardware Implementation
- Tested the circuit on a breadboard.
- Assembled on a **PCB** for durability and long-term use.
- Verified by charging small devices (mobile phones, rechargeable batteries).
- Created a 3D-printed mobile charging cover to neatly enclose and protect the model, making it portable and user-friendly.


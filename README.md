# Window Comparator Using IC741

![Platform](https://img.shields.io/badge/Platform-Analog%20Electronics-blue)
![IC](https://img.shields.io/badge/IC-741-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Tool](https://img.shields.io/badge/Designed%20Using-LTspice-orange)

---

## 📖 Overview

The **Window Comparator Using IC741** is an analog electronics project designed to determine whether an input voltage lies **below**, **within**, or **above** a predefined voltage range.

The circuit employs **two IC741 operational amplifiers** configured as open-loop voltage comparators. By comparing the input voltage against independently generated upper and lower reference voltages, the circuit provides visual indication through two LEDs.

- **LED 1 ON** → Input voltage is above the upper threshold.
- **LED 2 ON** → Input voltage is below the lower threshold.
- **Both LEDs OFF** → Input voltage lies within the specified voltage window.

This project demonstrates the practical application of operational amplifiers in voltage monitoring, analog signal conditioning, industrial protection systems, and battery management applications.

---

## 🎯 Objectives

- Design a Window Comparator circuit using two IC741 operational amplifiers.
- Detect whether the input voltage is below, within, or above a predefined voltage window.
- Generate upper and lower threshold voltages using a resistor voltage divider network.
- Indicate overvoltage and undervoltage conditions using LED indicators.
- Understand the practical application of operational amplifiers in voltage monitoring systems.
- Reinforce concepts of comparator circuits, voltage dividers, and threshold detection.

---

## ✨ Features

- Dual IC741 Operational Amplifier Design
- Upper and Lower Voltage Threshold Detection
- LED-Based Status Indication
- Adjustable Input Voltage using Potentiometer
- Simple Analog Circuit Design
- Breadboard Implementation
- Cost-Effective Solution

---

## ⚙️ Working Principle

The circuit uses two IC741 operational amplifiers configured as open-loop voltage comparators.

- The first comparator continuously compares the input voltage with the upper reference voltage.
- The second comparator compares the same input voltage with the lower reference voltage.
- When the input voltage exceeds the upper threshold, the first comparator activates LED1.
- When the input voltage falls below the lower threshold, the second comparator activates LED2.
- If the input voltage remains between both thresholds, both LEDs remain OFF, indicating that the input lies within the specified voltage window.

---

## 🔧 Components Required

| Component | Quantity |
|-----------|---------:|
| IC741 Operational Amplifier | 2 |
| Red LED | 2 |
| 10kΩ Resistors | 3 |
| 470Ω Resistors | 2 |
| 10kΩ Potentiometer | 1 |
| Breadboard | 1 |
| ±12V Dual Power Supply | 1 |
| Jumper Wires | As Required |

---

## 💻 Software & Tools

- LTSPICE
- Analog Electronics Laboratory Equipment

---

## 📂 Repository Structure

```
Window-Comparator-Using-IC741
│
├── README.md
├── LICENSE
├── Images
│   ├── Circuit.png
│   ├── Breadboard.jpg
│   ├── Output1.jpg
│   └── Output2.jpg
│
├── Documentation
│   └── Project Report.pdf
│
├── Circuit Diagram
│   └── Circuit.pdf
│
└── Simulation
    └── LTSpice Project
```

---

## 📊 Expected Output

| Input Voltage | LED 1 | LED 2 | Status |
|---------------|-------|-------|--------|
| Above Upper Threshold | ON | OFF | Overvoltage |
| Within Voltage Window | OFF | OFF | Normal Condition |
| Below Lower Threshold | OFF | ON | Undervoltage |

---

## 🎯 Applications

- Battery Management Systems (BMS)
- Voltage Monitoring
- Industrial Protection Circuits
- Analog Signal Conditioning
- Sensor Threshold Detection
- Electronic Measurement Systems

---

## 📈 Learning Outcomes

Through this project, I gained practical knowledge of:

- Operational Amplifiers
- Analog Comparator Circuits
- Voltage Divider Networks
- Threshold Voltage Detection
- Breadboard Circuit Assembly
- Analog Circuit Testing
- Engineering Documentation

---

## 🚀 Future Improvements

- Replace IC741 with low-power operational amplifiers.
- Add an audible buzzer for fault indication.
- Integrate digital display for voltage monitoring.
- Interface the circuit with a microcontroller for real-time monitoring.
- Design and fabricate a dedicated PCB version.

---

---

## 🙏 Acknowledgements

This project was completed as a team project for the Analog and Linear Electronic Circuits Laboratory at SRM Institute of Science and Technology.

Special thanks to my teammates for their collaboration throughout the project.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Kishen Vetharth M**

B.Tech Electronics and Communication Engineering (Data Science)

SRM Institute of Science and Technology

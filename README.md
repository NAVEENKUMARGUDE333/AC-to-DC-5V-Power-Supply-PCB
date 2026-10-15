# 🔌 AC to DC 5V Power Supply PCB

## 📌 Project Overview

This project is an **AC to DC 5V power supply PCB** designed using **EasyEDA**. It converts 240V AC input into a regulated 5V DC output using a step-down transformer, bridge rectifier, filter capacitors, and a 7805 voltage regulator.

This project is part of my **30-Day PCB Design Challenge**, where I am improving my PCB design, component placement, routing, and circuit design skills.

## ⚙️ Components Used

- Step-down transformer (240V AC to 12V AC)
- 2W10 bridge rectifier
- 7805 voltage regulator (TO-220)
- C1: 100µF / 25V capacitor
- C2: 10µF / 10V capacitor
- R1: 560Ω resistor
- LED: Power indicator
- P1: AC input terminal
- P2: DC output terminal

## 🔄 Working Principle

1. **Step-down:** The transformer reduces the AC input voltage to approximately 12V AC.
2. **Rectification:** The bridge rectifier converts AC into pulsating DC.
3. **Filtering:** Capacitors smooth the rectified DC voltage.
4. **Voltage Regulation:** The 7805 regulator provides a nominal 5V DC output.
5. **Power Indication:** The LED indicates the presence of output voltage.

## 🛠️ Design Tools

- **EDA Software:** EasyEDA
- **PCB Type:** Single-layer PCB
- **Design Process:** Schematic design, component placement, PCB routing, and 3D visualization.

## 📂 Repository Contents

- `README.md` – Project documentation
- `schematic.png` – Circuit schematic
- `pcb_layout.png` – PCB layout and routing
- `pcb_3d.png` – 3D PCB view
- `gerber/` – Manufacturing files

## 🎯 Learning Outcomes

- Understanding AC-to-DC conversion
- Learning bridge rectifier and voltage regulator circuits
- Practicing single-layer PCB routing
- Improving component placement and board layout
- Exploring 3D PCB visualization in EasyEDA


`PCB Design` `EasyEDA` `AC to DC Converter` `Power Supply` `Electronics` `7805` `Circuit Design` `ECE` `30 Days PCB Challenge`

# Embedded System Basics Projects 🛠️

Welcome to my personal repository for embedded systems engineering. This collection documents my journey from basic microcontroller programming to designing industrial-grade PCBs with integrated power management.

## 🎯 Philosophy
> "Learning by Doing, Building by Standards."
Every project here focuses on modular design, clean code architecture, and professional hardware safety standards.

## 🚀 Current Flagship Project: Smart Mini Cooler (Peltier-Based)
A fully autonomous temperature control system designed for small-scale cooling applications (beverages, chocolates, medicines). Unlike hobbyist setups, this system features an **integrated internal power supply** directly on the main PCB, mimicking real-world consumer electronics manufacturing.

### Key Features:
- **Integrated AC-DC Power Stage:** On-board 220V to 12V/5V conversion with galvanic isolation.
- **Dual-Mode Control:** Automatic PID/Hysteresis regulation & Manual user override via Keypad.
- **Safety First Design:** Hardware-level thermal cutoffs, current monitoring, and surge protection.
- **Modular Firmware:** Clean C architecture with separated drivers, logic, and HMI layers.

## 📂 Project Structure
| Module | Description | Status |
| :--- | :--- | :--- |
| **Power Management** | Internal AC-DC conversion, voltage regulation, and protection circuits |  In Progress |
| **Control Core** | STM32F103C6 based processing unit with ADC sensing | ✅ Completed |
| **HMI Interface** | LCD I2C Display + 4x4 Keypad for user interaction | ✅ Completed |
| **Actuator Drivers** | MOSFET-based switching for Peltier modules and cooling fans | ⏳ Planned |
| **Safety Layer** | Independent hardware watchdog and thermal fuses | ⏳ Planned |

## 🛠️ Tech Stack
- **Hardware:** KiCad (Schematic & PCB), STM32F103C6, LM35/DS18B20, TEC1-12706
- **Firmware:** Embedded C, Modular Architecture, Git Version Control
- **Tools:** VS Code, GCC, STM32CubeIDE, Proteus (Simulation)

##  Project Gallery
*(Place the generated image here)*

## 🤝 Mentorship & Learning
This repository is built under the guidance of a structured mentorship program focusing on deep-dive learning through practical implementation and "smart collision" with engineering challenges.

---
*Built with precision by Abdelfattah | Mechanical/Mechatronics Engineering Student*

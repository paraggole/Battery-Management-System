## BQ7692000 and BQ78350-R1

Features
- Voltage, current, and temperature monitoring for each cell
- Over-voltage and under-voltage protection
- Passive cell balancing
- UART-based communication for data logging
- Fault detection and shutdown logic
- Modular firmware written in C/C++ (PlatformIO or Arduino compatible)
- Real-time logging support
  
<img width="662" height="497" alt="Screenshot 2025-07-15 210111" src="https://github.com/user-attachments/assets/6d05ae20-da39-4e15-940d-01c5d23675eb" />

FR4 4-layer PCB (72mm × 60mm)
- High-current handling: **80A continuous**, **150A surge**
- Based on **BQ7692000PW** (AFE) and **BQ78350DBTR** (Fuel Gauge) from Texas Instruments
- Integrated protections: overvoltage, undervoltage, overcurrent, short-circuit, thermal
- Passive cell balancing with precision voltage and temperature sensing

Applications
- Electric Vehicles (EVs)
- Autonomous Underwater/Unmanned Aerial Vehicles (AUV/UAV)
- Energy storage systems
- Robotics power platforms

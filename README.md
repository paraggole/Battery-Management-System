## TI BQ7692000 and BQ78350-R1 - with great power !

## Design Highlights
- **5S Li-ion Support**: Designed for Li-ion battery packs with flexibility for 3S/4S/5S configurations.
- **Current Handling**: 80A continuous, 150A surge — tested with thermal simulations and high-current traces.
- **Low RDS(on) FETs**: Integrated CSD17501Q5A for minimal power loss and high switching efficiency.
- **Analog Precision**: High-accuracy (0.1%) voltage dividers and current sense resistors for clean measurements.
- **Monitoring Interface**: Real-time monitoring capability through BQ78350 SMBus/I2C output.
- **Thermal Shutdown**: Integrated thermistor input and analog thermal protection logic.
- **Status Indicators**: Configurable LEDs to indicate fault, charging, and balancing states.
- **Protection Layering**: Hardware-based over/under-voltage, overcurrent, short-circuit protections (<250μs response).

<img width="662" height="497" alt="Screenshot 2025-07-15 210111" src="https://github.com/user-attachments/assets/6d05ae20-da39-4e15-940d-01c5d23675eb" />

## Features
- Voltage, current, and temperature monitoring for each cell
- Over-voltage/current and under-voltage, short circuit, sleep, etc. protection
- All sorts of protection features programmed
- UART-based communication for data logging
- Fault detection and shutdown logic
- Modular firmware
- Real-time logging support
  
## FR4 4-layer PCB (72mm × 60mm)
- High-current handling: **80A continuous**, **150A surge**
- Based on **BQ7692000PW** (AFE) and **BQ78350DBTR** (Fuel Gauge) from Texas Instruments
- Integrated protections: overvoltage, undervoltage, overcurrent, short-circuit, thermal
- Passive cell balancing with precision voltage and temperature sensing

## Applications
- Electric Vehicles (EVs)
- Autonomous Underwater/Unmanned Aerial Vehicles (AUV/UAV)
- Energy storage systems
- Robotics power platforms

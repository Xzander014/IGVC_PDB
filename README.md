# IGVC_PDB

## Overview
This project is a KiCad-based Power Distribution Board (PDB) designed for the IGVC competition.
## Features
- **XT-60 Connectors**: Used for all 24V outputs.
- **Molex Connectors**: For both 5V and 3.3V outputs.
- **LED Indicators**: Each stepper motor, Cytron motor driver, and 5V/3.3V output has an LED for status indication.

## Current Sensing
The board includes multiple current sensors to monitor power consumption across different loads:

- **Stepper Motors**:
  - **IC**: ACS730KLCTR-20AB-T
  - **Max Rating**: 20A per stepper motor
  - **Shunt Resistor**: External WSL4026L5000FEB.

- **Main Battery Input**:
  - **IC**: ACS770LCB-100U-PFF-T
  - **Max Rating**: 100A 

- **Cytron Motor Drivers**:
  - **IC**: ACS72981LLRATR-050B5
  - **Max Rating**: 50A for each Cytron motor driver

## Voltage Regulation
- **AMS1117 Voltage Regulator**: Provides stable 3.3V output.
- **5V Outputs**: Available via Molex connectors.

## Repository Contents
- **KiCad Schematic Files**: Contains the complete circuit design.

## License
This project is open-source and can be modified as needed. Contributions and improvements are welcome!

---


# PID Based Temperature Controller

## Project overview
This project implements a PID (Proportional–Integral–Derivative) temperature control system for industrial heating applications. It combines hardware PID (op-amp circuits) with a software-based controller on an **ESP32**, and uses **MATLAB/Simulink** for process modeling and tuning. Simulations were validated in **Tinkercad** and final integration includes thermocouple sensing (MAX6675), relay-based actuator control, and data logging capabilities.

## Key technologies & tools
- **Microcontroller:** ESP32 (Arduino IDE, Embedded C)  
- **Sensors / HW:** Thermocouple + MAX6675, relays, MOSFETs  
- **Simulation & tuning:** MATLAB / Simulink, process reaction curve analysis  
- **Circuit validation:** Tinkercad (op-amp PID circuits)  
- **Version control & repo:** Git + GitHub

## Repository structure

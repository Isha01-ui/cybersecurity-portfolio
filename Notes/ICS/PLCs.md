# PLCs (Programmable Logic Controllers)

## Overview
- PLCs are specialized computers used to control industrial processes.
- They interact with sensors, actuators, and control networks.

## Components
- **CPU** – processes the control logic
- **Input Modules** – read signals from sensors
- **Output Modules** – send signals to actuators
- **Communication Ports** – connect to SCADA or other PLCs

## Control Logic
- Programs usually written in **Ladder Logic** or **Function Block Diagrams**
- Executes in a loop: read inputs → execute logic → write outputs

## Common Vulnerabilities
- Weak/default passwords
- Unauthenticated access
- Control logic injection
- Network protocol weaknesses (e.g., Modbus, S7)

## Best Practices
- Strong authentication and role-based access
- Network segmentation
- Regular firmware updates
- Monitoring and anomaly detection

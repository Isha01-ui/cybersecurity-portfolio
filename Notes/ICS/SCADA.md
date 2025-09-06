# SCADA Systems (Supervisory Control and Data Acquisition)

## Overview
- SCADA systems monitor and control industrial processes at a high level.
- They collect data from PLCs, sensors, and actuators, and allow operators to control processes remotely.

## Components
- **HMI (Human-Machine Interface)** – graphical interface for operators  
- **SCADA Server** – collects, processes, and stores data from field devices  
- **RTUs / PLCs** – Remote Terminal Units / PLCs interface with sensors and actuators  
- **Communication Network** – connects SCADA server, PLCs, and HMIs

## Common Vulnerabilities
- Weak authentication or default credentials  
- Unencrypted communication  
- Lack of network segmentation  
- Remote access without proper safeguards

## Security Best Practices
- Enforce strong authentication and user roles  
- Encrypt communication channels  
- Monitor traffic for anomalies  
- Regularly patch servers and field devices

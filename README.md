# OTA Software Update Simulator

## Overview
This project simulates how modern vehicles receive and install software updates wirelessly using Over-The-Air (OTA) technology.

The simulator demonstrates the complete ECU firmware update process including package download, checksum validation, firmware installation, event logging, and automatic rollback in case of failure.

## Features
- OTA firmware update simulation
- ECU software version management
- SHA-256 checksum validation
- Secure firmware installation process
- Event logging and monitoring
- Automatic rollback protection
- Interactive automotive-style dashboard

## Workflow
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/1cd25be2-409e-4b39-8b19-8340f49cb6f7" />

1. ECU checks for available updates
2. Update package is downloaded wirelessly
3. Checksum validation verifies package integrity
4. Firmware is installed to ECU memory
5. Update status is reported
6. Rollback is triggered if installation fails

## Technologies Used
- Replit
- TypeScript
- Web-based UI
- Automotive OTA Concepts

## Project Motivation
Modern Software Defined Vehicles (SDVs) from manufacturers such as BMW, Mercedes-Benz, and other OEMs rely heavily on OTA updates to deliver new features, security patches, and performance improvements without requiring a service center visit.

This project demonstrates the core principles behind such systems in a simplified simulation environment.

## Screenshots

### OTA Dashboard
<img width="1348" height="598" alt="ota dashboard" src="https://github.com/user-attachments/assets/c0cec417-76dc-493f-adc6-ba6da30ea635" />
<img width="1344" height="657" alt="ota dashboard1" src="https://github.com/user-attachments/assets/636f2a6d-0a34-4ca0-8984-6440c8eb6bfa" />
<img width="1345" height="597" alt="ota dashboard3" src="https://github.com/user-attachments/assets/e367149d-dd50-4378-8c69-e1784ad41918" />

### Successful Update
<img width="1122" height="597" alt="sucessfull update1" src="https://github.com/user-attachments/assets/536fae4f-15c2-44b8-b1b3-94fd625514ca" />
<img width="1025" height="646" alt="successful update2" src="https://github.com/user-attachments/assets/d84c3e88-7037-4a76-af8c-277c8f3de4e9" />

### Rollback Simulation
<img width="1273" height="591" alt="rollback1" src="https://github.com/user-attachments/assets/96d0eadb-bd0d-48f9-a351-78c7be77228f" />
<img width="1003" height="617" alt="rollback2" src="https://github.com/user-attachments/assets/e6fe2f9b-185a-424b-aa48-3c13042de3e0" />


## Future Improvements
- Digital signature verification
- Multi-ECU update support
- CAN communication simulation
- AUTOSAR Adaptive integration concepts

  ##Dashboard link
  https://2757ce20-fe58-4af5-b154-45ea413716e4-00-1qxcujm3sil33.pike.replit.dev/
  

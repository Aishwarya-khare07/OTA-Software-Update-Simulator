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
<img width="1348" height="598" alt="ota dashboard" src="https://github.com/user-attachments/assets/fca79b77-959f-4110-933e-b7c0b1123872" />

### Successful Update
<img width="1025" height="646" alt="successful update2" src="https://github.com/user-attachments/assets/3f02d72b-5a56-4ed1-acf5-1d6a1e8655a9" />

### Rollback Simulation
(Add screenshot here)

## Future Improvements
- Digital signature verification
- Multi-ECU update support
- CAN communication simulation
- AUTOSAR Adaptive integration concepts

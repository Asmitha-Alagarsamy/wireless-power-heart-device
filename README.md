# Wireless Power Transfer for Heart Assist Devices

This repository contains the source code and project report for a WPT-based medical device aimed at supporting heart assist systems. This project focuses on improving battery rechargeability and reducing surgical risks in implantable devices using inductive wireless power transmission.

## Report
- [`WPT Project Report`](docs/WPT%20Project%20report.pdf): Detailed project documentation, including system design, block diagrams, component explanations, and results.

## Features
- **Inductive Coupling** for wireless energy transfer
- **Arduino Uno with Atmega328** for control
- **Royer Oscillator** to generate high-frequency AC
- **Flow and Pulse Sensors** to monitor patient vitals
- **Wi-Fi Module (ESP8266)** for IoT-based data tracking
- **Charging automation** with switching circuit using CD4066

## Code
Arduino source code for:
- Measuring and transmitting pulse and flow rate
- IoT integration for ThingSpeak
- Battery charging automation and cutoff

See [`code/main_wpt.ino`](code/WPT Project code.pdf)

## System Overview

- **Transmitter Side**: Power supply → Voltage Regulator → Royer Oscillator → Primary Coil
- **Receiver Side**: Secondary Coil → Rectifier → Regulator → Battery + Microcontroller + Sensors

## Motivation
Surgical procedures to replace heart assist device batteries pose health risks. This system reduces surgical intervention by wirelessly transferring power and monitoring health metrics in real time.

## Future Scope
- Increase energy transfer efficiency
- Design smaller, implantable coil units
- Improve range and reduce heating

## Contributors
- [Patent: Wireless Power Transfer for Heart Assist Devices](https://ipindiaservices.gov.in/publicsearch) (Application No: 202241050359 A)

---



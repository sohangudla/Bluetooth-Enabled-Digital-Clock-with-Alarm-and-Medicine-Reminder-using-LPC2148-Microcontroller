# Bluetooth-Enabled-Digital-Clock-with-Alarm-and-Medicine-Reminder-using-LPC2148-Microcontroller
# Bluetooth-Enabled Digital Clock with Alarm and Medicine Reminder using LPC2138

## Overview

This project presents a Bluetooth-enabled Digital Clock with Alarm and Medicine Reminder system developed using the LPC2138 ARM7 microcontroller. The system integrates Real-Time Clock (RTC), LCD display, keypad interface, buzzer alerts, and UART communication to provide accurate timekeeping and medicine reminder notifications.

The project was implemented and simulated using Proteus Design Suite and Embedded C programming in Keil uVision.

---

## Features

* Real-Time Clock (RTC) based digital clock
* Multiple medicine alarm support
* LCD-based time and notification display
* Keypad-based time and alarm editing
* UART communication support
* Buzzer alert system
* Interrupt-driven embedded system
* Bluetooth/UART notification support
* Real-time alarm triggering

---

## Components Used

* LPC2138 ARM7 Microcontroller
* 16x2 LCD Display
* 4x4 Matrix Keypad
* Buzzer
* UART Module / Virtual Terminal
* Crystal Oscillator
* Power Supply Circuit
* Proteus Simulation Environment

---

## Software & Tools

* Embedded C
* Keil uVision
* Proteus Design Suite
* LPC2138 ARM7 Controller

---

## Working Principle

The LPC2138 internal RTC maintains current time and continuously checks alarm conditions. Users can configure alarm timings using the keypad interface. When the configured medicine reminder time matches the RTC time, the system:

* Displays an alert message on LCD
* Activates buzzer notification
* Sends UART/Bluetooth message notification

The system uses interrupt-driven programming for efficient real-time performance.

---

## Project Modules

* RTC Initialization
* LCD Interface
* Keypad Interface
* UART Communication
* Alarm Management
* Interrupt Service Routines (ISR)
* Buzzer Control

---

## Applications

* Medicine Reminder Systems
* Embedded Healthcare Devices
* Smart Reminder Systems
* Real-Time Monitoring Systems
* IoT-based Alert Systems

---

## Future Improvements

* Mobile App Integration
* Bluetooth Notification Enhancement
* GSM-based SMS Alerts
* EEPROM-based Alarm Storage
* Real Hardware Deployment
* Voice Alert System

---

## Conclusion

The project successfully demonstrates an interrupt-driven embedded medicine reminder system using LPC2138. The system efficiently integrates RTC, LCD, keypad, UART, and alarm mechanisms to provide reliable real-time medicine reminder functionality suitable for healthcare and reminder applications.

---

## Team Members

* A. Kuladeep Sai
* G. Sohan
* K.R. Sujan Krishna
* N. Manikanta Eswar Reddy

Department of Electronics and Communication Engineering
Amrita School of Engineering, Bengaluru

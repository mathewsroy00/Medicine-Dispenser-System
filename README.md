# Smart Medicine Dispenser and Alarm System

## Overview
This project is a smart medicine dispensing system designed to help users take medicines at the correct time and dosage. The system uses an ESP32 microcontroller along with a Real-Time Clock (RTC) module to schedule and trigger medicine dispensing automatically.

## Project Type
Group Project (Academic)

## My Involvement
This was a team-based project. While my direct contribution during development was limited, I have since:

- Studied the complete system architecture
- Understood the embedded C code and control logic
- Analyzed how GPIO is used for hardware interfacing
- Reviewed timing and scheduling using RTC
- Rebuilt and modified parts of the logic to strengthen my understanding

## Features
- Scheduled medicine dispensing using RTC
- Alarm/notification system for reminders
- Hardware control using ESP32 GPIO
- Mobile app integration for setting schedules (if applicable)

## System Architecture
- ESP32 Microcontroller
- RTC Module for time tracking
- Actuator mechanism for dispensing medicine
- GPIO-based hardware interfacing
- Optional mobile application interface

## Technologies Used
- Embedded C
- ESP32
- GPIO interfacing
- Real-Time Clock (RTC)
- Basic IoT integration

## How It Works
1. The user sets medicine timings using the system (or mobile app).
2. The RTC module keeps track of real-time.
3. When the scheduled time is reached:
   - The ESP32 triggers the dispensing mechanism
   - An alert/notification is generated
4. GPIO pins are used to control hardware components.

## Learning Outcomes
- Understanding of embedded systems design
- GPIO control and hardware interfacing
- Basics of real-time scheduling using RTC
- System-level thinking in embedded applications

## Future Improvements
- Add buzzer or LED alert system
- Improve user interface
- Add IoT-based remote monitoring
- Enhance reliability and fault handling

## Disclaimer
This project was developed as part of a group. The code and design were collaboratively created. This repository reflects my understanding, study, and improvements based on the original project.

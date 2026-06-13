# Smart-Agricare-System
Smart agriculture solution that reduces water and energy consumption through automated irrigation and lighting systems.

# Overview
Smart Agricare System is an IoT-based urban farming solution designed to reduce water and energy consumption through automated irrigation and lighting control.

The system uses sensors connected to M5Stack controllers to monitor temperature, soil moisture, and light intensity. Based on sensor readings, irrigation and artificial lighting are activated only when necessary.

## Features
### Smart Irrigation System
- Monitors soil moisture and temperature
- Automatically activates irrigation when required
- Audio and visual status indication
- Real-time LCD display monitoring

### Smart Light Detector
- Monitors ambient light intensity
- Automatically activates artificial lighting when natural light is insufficient
- Visual status indication using RGB LEDs

## System Logic

### Irrigation System
- Soil Moisture < 400 AND Temperature > 29°C → Water Pump ON
- Soil Moisture > 400 AND Temperature < 29°C → Water Pump OFF

### Light Detector
- Light Intensity < 250 → Artificial Light ON
- Light Intensity > 250 → Artificial Light OFF

## Goal

The goal of the Smart Agricare System is to design an automated and sustainable urban farming solution that optimizes resource usage in small-scale agricultural environments.

This project aims to:
- Reduce water wastage by implementing a smart irrigation system that activates only when soil moisture levels are low and temperature conditions require it.
- Reduce energy consumption by controlling artificial lighting based on ambient light intensity.
- Provide real-time environmental monitoring using sensors connected to an embedded system.
- Demonstrate how IoT and automation can improve efficiency in urban farming setups.
- Create a scalable and user-configurable system suitable for different crop requirements.

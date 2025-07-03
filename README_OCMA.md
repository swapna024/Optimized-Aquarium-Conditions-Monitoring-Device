# Optimized Aquarium Conditions Monitoring Device (OCMA)

A smart Arduino-based system that automatically monitors and regulates aquarium conditions for healthy aquatic life.

## Overview

The **OCMA** is an aquarium monitoring project that uses sensors and automated controls to manage:
- Water temperature (via LM35 sensor)
- Fish safety near oxygen pump (via Ultrasonic sensor)
- Visual status (via LEDs and LCD)
- Heater and cooler regulation
- Real-time insights on an LCD display

Developed as part of our Sensors Technology course project.

## Team
- Lakshita K J – 22BEC1001  
- Radhika P – 22BEC1051  
- Swapna S – 22BEC1232  
- S Lakshitha – 22BEC1302  

## Components Used
- Arduino Uno
- LM35 temperature sensor
- Ultrasonic sensor (HC-SR04)
- LCD Display (16x2)
- Relay SPDT
- Breadboard, Wires, Resistors, Potentiometer
- 9V Battery
- LEDs (Red, Green, Blue)
- Fan (Cooling), Light bulb (Heater)
- Water pump (for oxygen supply)

## Functionality
- **Temperature Range:**
  - Below 15°C: Heater on, Blue LED
  - Between 15–28°C: Idle, Green LED
  - Above 28°C: Fan on, Red LED
- **Fish Proximity Safety:**
  - If fish is closer than 20cm (via ultrasonic sensor), oxygen pump is turned off.

## Simulation & Testing
- Basic simulation shows LED changes and fan/heater control.
- Advanced simulation incorporates fish detection via ultrasonic sensor and motor control for pump.

## How to Run
1. Connect components as per the schematic.
2. Upload the `OCMA.ino` code to Arduino Uno.
3. Monitor LCD output and LED indications.
4. Observe temperature-based and fish proximity-based automation.

## License
Open-source under MIT License.
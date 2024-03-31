# Arduino-Light-System

## Overview
The Arduino-Light-System is a project aimed at creating an automated night light system using Arduino Uno, a photoresistor, and a PIR (Passive Infrared) sensor. This system is designed to detect low light conditions and motion within its vicinity, activating the LED light to provide illumination when needed, thus enhancing convenience and energy efficiency.

## Components Required
- Arduino Uno
- LED bulb
- Photoresistor (LDR)
- PIR Sensor
- Resistors
- Jump wires
- Breadboard (optional)

## Installation and Setup
<img src="https://github.com/lauspence/Adruino-Light-System/assets/64370903/eef88bb3-8daa-42d0-b38f-6f61cecab4d3" width="400" alt="Night Light System">

1. Connect the components as per the circuit diagram provided in the project documentation.
2. Upload the Arduino code provided in the repository to the Arduino Uno board using the Arduino IDE.
3. Ensure proper placement of the photoresistor and PIR sensor in the desired location for effective detection.
4. Power up the Arduino board and observe the system's functionality.
### Circuit Diagram
<img src="https://github.com/lauspence/Adruino-Light-System/assets/64370903/c9d1068b-04b9-49af-8dba-fdc29a72bd7b" width="400" alt="Schemantics">

## How It Works
- The photoresistor continuously monitors ambient light levels.
 <img src="https://github.com/lauspence/Adruino-Light-System/assets/64370903/2cffe725-6212-4f50-a346-f3674e9a8b90" width="400" alt="System Lighting">
- The PIR sensor detects motion within its detection range.
- When both low light conditions and motion are detected, the LED bulb is activated to provide illumination.
- The system includes a delay mechanism to allow a grace period for subsequent motion detection before turning off the light.
  
## Usage
- Place the Arduino-Light-System in the desired location where automated lighting is required, such as hallways, bedrooms, or bathrooms.
- Ensure the system is powered on and properly configured for optimal functionality.
- Experience the convenience of automatic lighting as the system responds to changes in ambient light and motion.

## Contributors
- David Mungai
- Ian Munene
- Lawrence Marete
- Joan Wanja
- Faiz Ashraf
- Erick Ochola

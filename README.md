# Automatic Street Light Controller

## Overview
This project demonstrates an automatic street light system using an LDR (Light Dependent Resistor) and Arduino. The system automatically switches street lights ON/OFF based on the surrounding light intensity. This project aims to provide a simple, energy-efficient solution for controlling street lights.

## Features
- **Energy-efficient design**: Automatically turns off lights during daylight hours.
- **Fully automatic operation**: No manual intervention required.
- **Simple and easy to build**: Suitable for beginners in electronics and Arduino programming.

## Components Required
- Arduino Uno
- Light Dependent Resistor (LDR)
- 10kΩ Resistor
- LED (to simulate street light)
- Breadboard and connecting wires

## Setup Instructions
1. Connect the LDR and 10kΩ resistor in series to form a voltage divider.
2. Connect one end of the LDR to the 5V pin on the Arduino.
3. Connect the other end of the LDR to an analog input pin (e.g., A0) on the Arduino.
4. Connect the 10kΩ resistor to the same analog input pin (A0) and ground.
5. Connect the LED's anode to a digital output pin (e.g., pin 9) on the Arduino.
6. Connect the LED's cathode to ground through a suitable current-limiting resistor (e.g., 220Ω).

## Usage
- Place the LDR in the desired location.
- The Arduino will continuously read the light intensity and turn the LED on/off based on the threshold value.
- Adjust the threshold value in the sketch to suit your specific environment.


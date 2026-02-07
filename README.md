# 3-Phase Inverter ESC for BLDC Motors

!project video: https://www.linkedin.com/feed/update/urn:li:activity:7425070753647095808/

## Overview
This repository contains the design, code, and documentation for a high-performance 3-phase inverter Electronic Speed Controller (ESC) designed to drive BLDC motors in e-bikes. Built for a client requirement, it handles efficient power delivery and motor control. Key features include precise switching, high current handling, and scalability for electric vehicles.

## Features
- Efficient 3-phase control for BLDC motors.
- High/low-side driving with IR2110 ICs.
- Robust power stage with IRFZ44 MOSFETs.
- Programmable via Arduino Uno.
- Tested for reliability in e-mobility applications.

## Components Used
- 3x IR2110 Driver ICs
- 6x IRFZ44 MOSFETs
- 100nF and 22uF Capacitors
- 4x 1kΩ Resistors
- 2x 10Ω Resistors
- Arduino Uno (for control and testing)

## Wiring Diagram
![WhatsApp Image 2026-01-28 at 4 54 42 PM](https://github.com/user-attachments/assets/e3f7a77a-bbfe-4e29-8bcc-fd0690b44fbc)



## Installation and Setup
1. Assemble 3 times the circuit as per the diagram.
2. Download and Upload the Arduino code .
3. Test with a BLDC motor (start with low voltage).


## Usage
- Power up the circuit.
- Use Arduino Serial Monitor to adjust speed and monitor performance.
- Scale for larger motors by upgrading components.

## Contributing
Fork and PR your improvements! Ideas: Add sensor feedback or PWM modulation.


Built by Shahid Rafiq (@shahid407). Open to collaborations in robotics/EV!

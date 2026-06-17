# KiCad DRV8833 Motor Driver

A custom dual H-Bridge motor driver PCB based on the Texas Instruments DRV8833 motor driver IC. Designed in KiCad for robotics, embedded systems, and small DC motor control applications.

## Features

- Dual DC motor control
- DRV8833 dual H-Bridge motor driver
- Sleep mode support
- Fault monitoring output
- Onboard power indicator LED
- Power supply decoupling capacitors
- Compact PCB design
- Easy connector-based interfacing

## Hardware Specifications

| Parameter | Value |
|------------|---------|
| Motor Driver IC | DRV8833 |
| Motor Channels | 2 |
| Motor Supply Voltage | 2.7V – 10.8V |
| Logic Interface | 3.3V / 5V Compatible |
| Control Inputs | AIN1, AIN2, BIN1, BIN2 |
| Fault Output | FAULT |
| Sleep Control | SLEEP |

## Schematic

The design includes:

- DRV8833 motor driver IC
- Power filtering capacitors
- Status LED
- Motor output connectors
- Control signal connectors
- Fault monitoring output

## Pinout

### Control Header

| Pin | Signal |
|------|---------|
| 1 | AIN1 |
| 2 | AIN2 |
| 3 | VCC |
| 4 | GND |
| 5 | BIN1 |
| 6 | BIN2 |

### Motor Header

| Pin | Signal |
|------|---------|
| 1 | SLEEP |
| 2 | AOUT1 |
| 3 | AOUT2 |
| 4 | BOUT1 |
| 5 | BOUT2 |
| 6 | FAULT |

## Applications

- Mobile robots
- Line follower robots
- Autonomous vehicles
- Embedded motor control systems
- Educational robotics projects
- Small DC motor applications

## Design Tools

- KiCad 9
- DRV8833 Datasheet

## Future Improvements

- Current sensing support
- Reverse polarity protection
- Screw terminal connectors
- Test points for debugging

## License

This project is released under the MIT License.

## Author

Abhishek B Kumbar  
ECE Student | PCB Design | Embedded Systems 

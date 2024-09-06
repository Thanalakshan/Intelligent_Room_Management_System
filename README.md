# Intelligent Room Management System using LabVIEW and DAQmx

This project showcases an Intelligent Room Management System developed using LabVIEW and a DAQmx card. The system automates room conditions by controlling fan speed and light intensity, making it energy-efficient and user-friendly.

## Features

- **Fan Speed Control**: A PWM signal is generated using LabVIEW to adjust the fan speed based on the room's temperature.
- **Adaptive Lighting**: The light intensity is automatically adjusted according to the ambient light levels, providing optimal lighting conditions.
- **Occupancy Detection**: A custom sensor setup with two LDRs and two lasers detects the number of occupants in the room. The system automatically turns off the fan and lights when no one is present, conserving energy.

## Overview

This project demonstrates the integration of sensors and control systems for smart room management, highlighting the potential for automation in everyday environments.

## Technologies Used

- **LabVIEW**: For developing the control system and interfacing with hardware.
- **DAQmx Card**: Used for acquiring data from sensors and controlling the outputs.
- **Sensors**: LDRs and lasers for occupancy detection, and temperature sensors for fan control.

## How It Works

1. **PWM Signal Generation**: LabVIEW generates a PWM signal to control the fan speed based on temperature input.
2. **Light Intensity Adjustment**: Ambient light is measured, and the system adjusts room lighting accordingly.
3. **Occupancy Management**: Sensors detect the presence of people, turning off all systems when the room is empty.

## Future Enhancements

- Integration with IoT for remote monitoring and control.
- Advanced algorithms for more precise occupancy detection.
- Expansion to manage additional room conditions such as humidity.

## Conclusion

This Intelligent Room Management System provides an effective solution for automating room conditions, improving comfort while conserving energy.

## Download LabVIEW and Related Software

For LabVIEW and related software, please download from the following link:

[Download LabVIEW and Related Software](https://bit.ly/NI-GD){:target="_blank"}

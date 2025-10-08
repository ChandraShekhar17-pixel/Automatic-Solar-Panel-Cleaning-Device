# Automatic Solar Panel Cleaning Device

This project implements an automatic cleaning system for solar panels to combat efficiency loss caused by sand accumulation, particularly in desert areas. The system uses Arduino, IR sensors, and servo motors to detect and wipe off sand from solar panels without human intervention.

## Project Overview

Sand accumulation on solar panels significantly reduces power output by blocking sunlight and reducing current generation. This system automatically detects sand presence on panels and cleans them using motorized wiping arms controlled by an Arduino. The cleaning activates only when sand is detected to optimize power use.

## Components

- **Arduino Uno:** Processes IR sensor input and controls servo motors.
- **Infrared (IR) Sensor:** Detects presence of sand on the panel by measuring reflected IR waves.
- **Servo Motors:** Operate the wiping arms to clean the panel surface.
- **Solar Panel (Prototype):** Small size panel used for testing.
- **Other:** Jumper wires, breadboard for circuit assembly.

## Working Principle

- The IR sensor emits IR light and detects the reflected waves from the panel surface.
- When sand or any obstruction is detected (IR reflection changes), the sensor signals Arduino.
- Arduino activates servo motors to run the wiping arms across the solar panel surface to clean off the sand.
- The wiping action runs only if obstruction stays continuously for more than 5 seconds to avoid false triggers.
- The system operates autonomously, requiring no manual intervention.

## Results

- Measured output voltage and short circuit current of the solar panel with varying sand accumulation.
- Efficiency dropped approximately 50% due to sand coverage, mainly driven by decreased current.
- The power consumption by servo motors (~3.5 watts) is lower than power lost due to sand, making the cleaning system energy-efficient.
- Cleaning restored power output close to clean panel levels.

## Future Enhancements

- Integrate solar tracking system to optimize panel orientation along with automatic cleaning.
- Add rain sensing or weather conditions to disable wiping during rain.
- Improve wiper design using soft, non-damaging materials.
- Minimize system size and package for easier installation.
- Refine sensing and control algorithms to avoid false cleaning cycles.

## Learnings

- Gained practical understanding of IR sensor working and limitations.
- Experienced Arduino programming and sensor integration.
- Understood impact of external factors on solar panel efficiency and mitigation techniques.

## Circuit and Implementation

- Circuit diagram and clean hardware setup achieved using Arduino, IR sensors, and servo motors.
- The project includes code to interface IR sensor input and control servo actions optimally.

---

Developed by Chanchal Yadav, Chandra Shekhar, and Chandrabhan Patel  
Indian Institute of Technology Gandhinagar  


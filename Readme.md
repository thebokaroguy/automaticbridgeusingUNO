# Flood Emergency Bridge System

## Overview

This project involves creating a flood emergency bridge system using Arduino Uno, an ultrasonic sensor, and a servo motor. The system detects water levels using the ultrasonic sensor and lifts the bridge using the servo motor when the water level exceeds a set threshold. This allows vehicles to pass safely during flood emergencies.

## Hardware Requirements

- Arduino Uno
- Ultrasonic sensor (HC-SR04)
- Servo motor
- Jumper wires
- Power supply

## Wiring

Connect the hardware components according to your specific setup:

- Connect the trigPin and echoPin of the ultrasonic sensor to the corresponding pins on the Arduino.
- Connect the servoPin to the control pin of the servo motor.
- Power up the system.

## Arduino Code

1. Copy and paste the provided Arduino code into the Arduino IDE.
2. Upload the code to your Arduino Uno.
3. Adjust the thresholdDistance variable based on your specific requirements.

## Usage

1. Power up the system.
2. The ultrasonic sensor continuously measures the water level.
3. If the water level exceeds the set threshold, the servo motor lifts the bridge.
4. Adjust the delay in the liftBridge and lowerBridge functions to ensure proper bridge movement.
5. Ensure proper calibration and testing before deploying the system in a real-life scenario.

## Notes

- The ultrasonic sensor measures distance in centimeters.
- Calibrate the thresholdDistance based on the desired water level for bridge activation.
- Test the system thoroughly to ensure reliability during emergencies.
- Consider using a power backup system for uninterrupted operation during power outages.

Stay safe and use the flood emergency bridge system responsibly!

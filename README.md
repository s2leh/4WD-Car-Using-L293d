# Automated-4WD-Car-Using-L293d

## Components Used
Arduino Uno

L293D Motor Shield 

4x DC Motors

Ultrasonic Sensor

Servo Motor

Battery pack

Chassis

## How It Works
1-The servo motor sweeps the ultrasonic sensor from side to side.

2-The sensor checks for obstacles in front, left, and right directions.

3-Based on the distance, the Arduino:

Moves forward if the path is clear.

## Code Overview
Libraries Used:

AFMotor.h: Used to control the 4 DC motors via the L293D motor driver shield

Servo.h: Controls the servo motor that rotates the ultrasonic sensor

stdlib.h: Provides random() functionality to make movement decisions less predictable when obstacles are detected on both sides

## Video



https://github.com/user-attachments/assets/c5f1bff2-a6bd-4afa-a0fb-22cad111abc3



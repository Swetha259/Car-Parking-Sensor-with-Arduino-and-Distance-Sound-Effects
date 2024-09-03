Car Parking Sensor with Arduino and Distance Sound Effects
This project implements a Car Parking Sensor using an Arduino, featuring distance-based sound effects. The system helps drivers park safely by emitting varying sound frequencies as the car approaches an obstacle. The closer the car gets to the obstacle, the faster the beeps, providing a clear indication of proximity.

Features
Real-Time Distance Measurement: Uses an ultrasonic sensor to measure the distance between the car and an obstacle.
Variable Sound Alerts: The buzzer emits different sound frequencies based on the distance to the obstacle:
Very Close Proximity: Fast beeps (less than 10 cm).
Close Proximity: Medium beeps (10 cm to 30 cm).
Mid Proximity: Slow beeps (30 cm to 60 cm).
Far Proximity: Very slow beeps (60 cm to 120 cm).
Components Needed
Arduino (any model with at least 3 digital I/O pins)
Ultrasonic Sensor (HC-SR04)
Buzzer
Jumper wires
Breadboard (optional)
Circuit Diagram
Buzzer: Connect to digital pin 7 and GND.
Ultrasonic Sensor:
VCC: Connect to 5V on Arduino.
GND: Connect to GND on Arduino.
Trig Pin: Connect to digital pin 8 on Arduino.
Echo Pin: Connect to digital pin 4 on Arduino.

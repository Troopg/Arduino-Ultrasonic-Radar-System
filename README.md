# Arduino-Ultrasonic-Radar-System
This project demonstrates a radar-like obstacle detection system using an Arduino Nano, HC-SR04 Ultrasonic Sensor, SG90 Servo Motor, and Processing IDE.  The ultrasonic sensor scans a 180° field of view by rotating on a servo motor. Distance and angle data are transmitted to a computer through serial communication.
Features
180° scanning range
Real-time obstacle detection
Radar-style visualization
Serial communication between Arduino and Processing
Low-cost implementation
Hardware Components
Component	Quantity
Arduino Nano	1
HC-SR04 Ultrasonic Sensor	1
SG90 Servo Motor	1
Jumper Wires	As required
USB Cable	1
Connections
HC-SR04	Arduino Nano
VCC	5V
GND	GND
TRIG	D2
ECHO	D3
Servo Motor	Arduino Nano
Signal	D9
VCC	5V
GND	GND
Software
Arduino IDE
Processing 4
Working Principle
The servo rotates the ultrasonic sensor from 15° to 165°.
Distance measurements are taken at each angle.
Data is transmitted through serial communication.
Processing visualizes the scanning area and detected objects.
Project Images
Connection Diagram

(Add image here)

Radar Interface

(Add image here)

Future Improvements
Multiple target tracking
LiDAR integration
ESP32 implementation
Wireless telemetry
Drone detection prototype
Author

Surisetti Venu

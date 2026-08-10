# Mocando-Project-
# Automatic Dustbin using Arduino and Ultrasonic Sensor

## Overview
This project is an automatic touchless dustbin that opens its lid automatically when a hand or object is detected nearby, and closes it after a short delay. It uses an HC-SR04 ultrasonic distance sensor to detect proximity and a servo motor to control the lid, all driven by an Arduino microcontroller.

## How It Works
1. The HC-SR04 ultrasonic sensor continuously measures the distance to any object in front of it by sending out ultrasonic pulses and measuring the time taken for the echo to return.
2. When an object (e.g. a hand) comes within a set threshold distance (e.g. 10 cm), the Arduino detects this and sends a signal to the servo motor.
3. The servo motor rotates to lift the dustbin lid open.
4. After a short delay (e.g. 3-5 seconds), if no object is detected, the servo rotates back to close the lid.

## Bill of Materials (BOM)

 Component | Quantity | Approximate Cost |

Arduino Uno | 1 | — |
HC-SR04 Ultrasonic Sensor | 1 | — |
SG90 Servo Motor | 1 | — |
Jumper Wires (M-M, M-F) | ~10 | — |
Breadboard (optional) | 1 | — |
9V Battery / USB Power Source | 1 | — |
Dustbin (with lid) | 1 | — |
Double-sided tape / glue / screws (for mounting) | — | — |

*(Fill in actual costs based on where you purchased your components.)*

## Circuit Diagram / Pin Connections

**HC-SR04 Ultrasonic Sensor → Arduino Uno**
| HC-SR04 Pin | Arduino Pin |
|---|---|
| VCC | 5V |
| GND | GND |
| Trig | D9 |
| Echo | D10 |

**SG90 Servo Motor → Arduino Uno**
| Servo Wire | Arduino Pin |
|---|---|
| Red (VCC) | 5V |
| Brown/Black (GND) | GND |
| Orange (Signal) | D6 |


## Author
[Your Name]
Date: [Project completion date]

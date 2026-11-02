# Smart Open Manhole Detection System

## Project Overview

The Smart Open Manhole Detection System is an Arduino-based safety monitoring system designed to detect open manhole conditions and identify potential human falls. The system uses multiple sensors to monitor manhole conditions, detect nearby human movement, identify possible falls, and monitor environmental parameters.

It provides immediate alerts through LEDs and a buzzer to improve public safety and reduce the risk of accidents.

## Objectives

- Detect open or displaced manhole covers.
- Identify potential human falls into manholes.
- Detect nearby human movement.
- Monitor temperature and humidity conditions.
- Generate alerts using LEDs and a buzzer.
- Improve public safety through an affordable sensor-based monitoring system.

## Hardware Components

| Component | Purpose |
|---|---|
| Arduino Uno | Main controller |
| HC-SR04 Ultrasonic Sensor | Detects manhole cover position |
| IR Sensor | Helps identify potential human falls |
| PIR Sensor | Detects nearby human movement |
| DHT11 Sensor | Measures temperature and humidity |
| Yellow LED | Indicates open manhole condition |
| Red LED | Indicates emergency condition |
| Buzzer | Provides audio alerts |
| Breadboard | Circuit connections |
| Jumper Wires | Electrical connections |

## Working Principle

The system uses multiple sensors connected to an Arduino Uno to monitor the manhole environment.

1. **Manhole Cover Detection:** The HC-SR04 ultrasonic sensor measures the distance to the manhole cover and identifies changes that may indicate an open or displaced cover.

2. **Human Fall Detection:** The IR sensor helps detect a possible human fall based on its sensing output.

3. **Human Movement Detection:** The PIR sensor detects the presence of nearby human movement.

4. **Temperature and Humidity Monitoring:** The DHT11 sensor measures the surrounding temperature and humidity.

5. **Alert System:** The Arduino processes the sensor inputs and activates the yellow LED, red LED and buzzer according to the detected conditions.

## Sensor Integration

- HC-SR04 – Manhole cover monitoring.
- IR Sensor – Potential fall detection.
- PIR Sensor – Human movement detection.
- DHT11 – Environmental monitoring.

## Alert Conditions

| Condition | Indication |
|---|---|
| Normal condition | No emergency alert |
| Manhole cover open | Yellow LED ON |
| Potential emergency | Red LED and buzzer ON |
| Environmental monitoring | Temperature and humidity readings |

## Technologies Used

- Embedded Systems
- Arduino IDE
- Embedded C/C++
- Sensor Integration
- Electronic Circuit Design

## Applications

- Smart City Infrastructure
- Public Safety Monitoring
- Underground Drainage Systems
- Manhole Safety Monitoring
- Accident Prevention Systems

## Expected Outcome

The proposed system aims to provide an affordable and efficient method of monitoring manhole safety by combining multiple sensors. It helps identify potentially dangerous conditions and provides alerts to reduce the risk of accidents.

## Future Enhancements

- GSM-based emergency notifications.
- GPS-based location tracking.
- IoT-based remote monitoring.
- Real-time sensor data visualization.
- Cloud-based monitoring and alert system.

## Project Domain

Electronics and Communication Engineering (ECE)

## Contributors

Project Team – Smart Open Manhole Detection System

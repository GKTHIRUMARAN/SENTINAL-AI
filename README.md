SENTINAL-AI

Automated Swing Door System with Smart Lighting Control
A Raspberry Pi–powered automation system that intelligently controls a swing door and lighting using face recognition and presence detection. Designed for convenience, security, and energy efficiency.

Overview

SENTINEL-AI* combines computer vision, PIR sensors, and motor control to automate door opening and lighting systems:
- Detects people using a PIR motion sensor and face recognition.
- Automatically opens and closes a swing door using a swing motor.
- Turns lights ON/OFF based on presence and movement.
- Uses Python and GPIO control on Raspberry Pi.

Features

- Face recognition using `face_recognition` + OpenCV  
- Motorized swing door with linkage arm mechanism  
- PIR sensor for presence detection  
- Smart lighting automation  
- Intelligent control logic for entry/exit  
- Python + Raspberry Pi GPIO integration  

Technologies & Tools Used

- Python
- OpenCV
- face_recognition lib
- RPi.GPIO pins
- PIR Sensor
- Power Window Motor & Limiter switchs
- Relay Module & Smps
- Raspberry Pi 5

System Flow

1. Entry:
   - PIR sensor detects movement.
   - Face recognition validates identity.
   - Door opens automatically.
   - Light turns on.
2. Exit:
   - Door opened manually.
   - PIR detects no presence.
   - Light turns off automatically.

Future Enhancements

- Voice-controlled door access  
- Web UI for managing recognized faces  
- Unknown face detection alerts  
- Ultrasonic sensor for better presence tracking  

Developers:

Thirumaran GK, Vishnusarathi V, Giriprasath S
B.Tech - Artificial Intelligence & Data Science
[LinkedIn--https://www.linkedin.com/in/thirumarangk-ai]

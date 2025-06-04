# SENTINAL-AI

Automated Swing Door System with Smart Lighting Control
* This project is an automated swing door system enhanced with presence detection and smart lighting control for improved convenience and energy efficiency. It uses a combination of face recognition (OpenCV + face_recognition) and PIR sensors to detect a person approaching the door. When a person is recognized entering, the system:
* Automatically opens the door using a power window motor with a string-type linkage arm.
* Turns on the light to illuminate the area.
* Closes the door automatically using an online door closer.
* When the person leaves:
* The door is opened manually.
* The system detects departure using the PIR sensor.
* The light is turned off automatically as the door closes.
The entire system is controlled using GPIO-based devices and Python, offering a seamless integration of automation and intelligent control.

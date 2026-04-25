# Smart Glasses for Visually Impaired People
Using Arduino Nano and Ultrasonic Sensor

Faculty of Engineering  
Department of Communications & Computers  

---

## 1. Introduction
This project introduces a smart wearable electronic system designed to assist visually impaired people during movement.  
The system aims to improve safety and independence using low-cost embedded components.

---

## 2. Problem Statement
Visually impaired people face challenges in detecting obstacles while walking.  
Traditional tools like white canes rely on physical contact and have limited range.  
There is a need for a system that detects obstacles before collision and provides instant feedback.

---

## 3. Project Objectives
- Design a wearable obstacle detection system  
- Convert distance into audio alerts  
- Provide a low-cost and compact solution  
- Improve user safety and independence  

---

## 4. System Overview
- Ultrasonic sensor detects obstacles  
- Arduino Nano processes distance data  
- Buzzer provides audio alerts  
- System is mounted on glasses for hands-free use  

---

## 5. Hardware Components
- Arduino Nano  
- HC-SR04 Ultrasonic Sensor  
- Active Buzzer (5V)  
- 9V Battery  
- Power Switch  
- Jumper Wires  
- Glasses Frame  

---

## 6. Working Principle
The ultrasonic sensor sends sound waves and receives reflections from obstacles.  
Arduino calculates the distance based on time delay.  
If the object is within a safety range, the buzzer is activated.

---

## 7. Distance Formula
Distance = (Time × Speed of Sound) / 2  

The division by 2 accounts for the wave traveling to the object and back.

---

## 8. Audio Alert System
The buzzer provides immediate sound alerts when an obstacle is detected.  
This replaces visual feedback with audio feedback for the user.

---

## 9. Multivibrator Concept
Arduino generates periodic signals similar to an astable multivibrator.  
These signals control the buzzer frequency based on distance.

---

## 10. Audio Amplifier Concept
The Arduino provides control signals while the buzzer internally amplifies them.  
No external amplifier is required.

---

## 11. Advantages
- Low cost  
- Easy to implement  
- Portable and wearable  
- Real-time detection  
- Simple user interface  

---

## 12. Applications
- Assisting visually impaired people  
- Indoor and outdoor navigation  
- Educational embedded systems projects  

---

## 13. Limitations
- Limited sensor range  
- Reduced accuracy on soft surfaces  
- Affected by object angle  
- Audio feedback may be unclear in noisy environments  

---

## 14. Conclusion
The system provides an effective and low-cost solution for obstacle detection.  
It enhances mobility and safety for visually impaired users using embedded systems.

---

## 15. Thank You
Thank you for your attention.  
Any Questions?

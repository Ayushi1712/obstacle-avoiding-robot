# 🤖 Arduino Obstacle Avoiding Robot  

An **autonomous obstacle-avoiding robot** built using **Arduino Uno, Ultrasonic Sensor (HC-SR04), Servo Motor, and Adafruit Motor Shield**.  
The robot continuously scans its surroundings, detects obstacles, and makes decisions to move **forward, left, right, or turn around** to avoid collisions.  

---

## ✨ Features  
- 🚗 Autonomous navigation without human control  
- 📡 Obstacle detection using **HC-SR04 ultrasonic sensor**  
- 🔄 Servo motor scanning for left/right distance measurement  
- ⚡ Smooth motor speed control with **PWM**  
- 🛑 Adjustable collision threshold distance  

---

## 🛠 Hardware Required  

- **Arduino Uno** (or compatible board)  
- **Adafruit L293D Motor Driver Shield** (`AFMotor` library)  
- **2x DC Motors with wheels**  
- **1x Ultrasonic Sensor (HC-SR04)**  
- **1x Servo Motor (SG90 / MG90S)**  
- **Robot chassis + castor wheel**  
- **Battery pack** (7.4V–12V Li-ion / LiPo recommended)  
- Jumper wires  

---

## 📌 Circuit Connections  

| Component         | Arduino Pin |
|-------------------|-------------|
| Ultrasonic TRIG   | A0          |
| Ultrasonic ECHO   | A1          |
| Servo Signal      | D10         |
| Motors            | Motor Shield M1–M4 |
  

---



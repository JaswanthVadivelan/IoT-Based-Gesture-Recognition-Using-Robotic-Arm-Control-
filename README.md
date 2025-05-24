# IoT-Based Gesture Recognition System for Robotic Arm Control

## 📌 Project Overview
A real-time system that controls a 3D-printed robotic arm using hand gestures, integrating:
- **Computer Vision** (YOLOv5 for gesture recognition)  
- **IoT** (MQTT/ThingSpeak for remote monitoring)  
- **Embedded Systems** (Raspberry Pi + NodeMCU)  

Designed for applications in automation, healthcare, and assistive technologies.

---

## 🚀 Key Features
| Feature | Description |
|---------|-------------|
| **Real-Time Gesture Recognition** | YOLOv5 model for high-accuracy hand detection |
| **Wireless Control** | MQTT protocol for low-latency communication |
| **6-DOF Robotic Arm** | 3D-printed arm with 6 servo motors |
| **Cloud Monitoring** | ThingSpeak integration for servo data visualization |
| **Low-Cost Hardware** | Raspberry Pi 4 + ESP8266 + PCA9685 servo driver |

---

## 🛠️ Hardware Components
1. **Raspberry Pi 4** (Central processing unit)  
2. **USB Camera or Raspberry pi cam** (Gesture capture)  
3. **NodeMCU (ESP8266)** (Wireless communication)  
4. **PCA9685 Servo Driver** (Controls 6 servos)  
5. **3D-Printed Robotic Arm** (Custom design)  
6. **Power Supply** (Batteries for Pi/NodeMCU/servos)  

---

## 💻 Software Stack
- **Raspberry Pi OS**  
- **Python 3** (YOLOv5 + OpenCV)  
- **Arduino IDE** (NodeMCU firmware)  
- **ThingSpeak API** (Cloud monitoring)  

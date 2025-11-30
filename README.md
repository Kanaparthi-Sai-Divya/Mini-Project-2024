# 🚗 Speed and Pothole Detection System – Enhancing Road Safety

# 📌 Project Overview
Road safety issues such as potholes and overspeeding contribute to frequent accidents and significant vehicle damage.
This project presents a low-cost IoT-based system that detects potholes using ultrasonic sensors and monitors vehicle speed using IR sensors. When abnormalities are detected, the system provides real-time alerts using a buzzer, helping the driver take immediate action.

# 🔍 Introduction
Increasing population demands better and safer road infrastructure.
Potholes and overspeeding are major contributors to road accidents.
Existing centralized road monitoring systems require high infrastructure and often lack real-time feedback.
This project proposes a simple IoT-based solution for real-time detection and alerting.

# ⚠️ Problem Statement
Potholes and overspeeding pose high risks to passengers and vehicles.
There is a need for a simple, affordable, real-time system that detects potholes, monitors speed, and alerts drivers instantly.

# 🏚️ Existing System
Existing systems rely heavily on:
GPS-based monitoring
Cloud data processing

Limitations:
Expensive
Requires strong connectivity
No immediate feedback for drivers
Ineffective in rural areas

# 🆕 Proposed System
The proposed system uses:
Ultrasonic Sensor (HC-SR04) → Detects potholes
IR Sensors → Measures vehicle speed
Buzzer → Real-time alerting system

Key Features:
No GPS or cloud dependency
Real-time local alerts
Cost-effective and easily deployable
Works in all environments

# 💻 System Requirements
Hardware:
Ultrasonic Sensor (HC-SR04)
IR Sensor
Arduino UNO
Buzzer
Connecting wires & power supply

Software:
Arduino IDE

# 🧪 Coding & Testing Overview
1. Ultrasonic Distance Measurement
HC-SR04 emits pulses → Echo received → Distance calculated
Used to identify potholes based on abnormal depth readings.
2. Speed Detection
Two IR sensors placed at a known distance
Time difference used to calculate speed:
Speed=Time / Distance
3. Overspeed Alert
If speed > predefined limit → buzzer alerts the driver.

# 📊 Result Analysis
<img width="955" height="454" alt="image" src="https://github.com/user-attachments/assets/26e24e8c-6e1f-4660-b1ec-25d65a4c3b0f" />

<img width="1106" height="630" alt="image" src="https://github.com/user-attachments/assets/50cf525e-480f-498a-97b4-b15b41e3ce94" />





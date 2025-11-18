# Human-following-robot-
🤖 Autonomous human-following robot using ESP32, sensors, and OpenCV for real-time tracking.

🔗Project Link :
https://drive.google.com/file/d/1fgX5dcJnXLfjXahw6pFUcoh1_wiUEUPf/view?usp=drivesdk


📌 Overview :

This project is an autonomous human-following robot designed to detect, track, and follow a person in real time. It uses the ESP32 microcontroller, a combination of sensors, and OpenCV (for vision-based tracking) to maintain the robot’s movement behind the target.

The system is suitable for applications such as delivery robots, assistance robots, and mobility support systems.


🚀 Features :

🔍 Real-time human detection & tracking using OpenCV

📡 ESP32-based control system

📏 Distance sensing using Ultrasonic/IR/LiDAR sensors

🛞 Smooth movement using motor driver (L298N/L293D)

🔄 Automatic direction correction

🔋 Low-power, portable design


🧠 Working Principle :

1. The camera module captures video frames.


2. OpenCV identifies the human using color, shape, or Haar Cascade detection.


3. The ESP32 receives tracking data and adjusts robot movement.


4. Sensors measure distance to avoid collision.


5. Motors rotate to follow the person continuously.



🛠 Components Used :

ESP32 Development Board

Camera Module (ESP32-CAM / USB Camera)

Motor Driver (L298N / L293D)

DC Motors / Gear Motors

Ultrasonic Sensor (HC-SR04)

Battery Pack

Chassis & Wheels


🧩 Future Enhancements :

Add person-re-identification for accuracy

Improve obstacle avoidance

Add GPS navigation support

Integrate voice commands


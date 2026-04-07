# motion-detection-alarm-microbit
A simple and effective motion detection system using a PIR sensor and Micro:bit. When motion is detected, the system triggers a buzzer alarm, making it useful for basic security applications.

📌 Project Overview
---------------------------------------------
This project uses a PIR (Passive Infrared) sensor to detect human motion. When movement is detected, the Micro:bit processes the signal and activates a buzzer to alert the user.

🛠️ Components Required
---------------------------------------------
BBC Micro:bit
PIR Motion Sensor
Buzzer
Jumper Wires
USB Power Supply

🔗 Tinkercad Simulation
👉 Live Project Link:

⚙️ Working Principle
---------------------------------------------
PIR sensor detects infrared radiation (human motion)
Sensor sends signal to Micro:bit (Pin input)
Micro:bit processes the signal
If motion detected → Buzzer ON
If no motion → Buzzer OFF

🔌 Pin Connections
---------------------------------------------
Component.  Micro:bit Pin
PIR VCC.     3V
PIR GND.     GND
PIR OUT.     Pin 0
Buzzer (+).  Pin 2
Buzzer (-).  GND

📊 Applications
---------------------------------------------
🏠 Home security system
🚪 Intruder alert system
🏫 Classroom/demo project
🏢 Office monitoring

🔮 Future Enhancements
---------------------------------------------
📱 Send alerts to mobile (IoT upgrade)
🔊 Replace buzzer with speaker (voice alert)
📡 Add GSM/WiFi module
📷 Integrate camera for surveillance
🧠 Learning Outcomes

Sensor interfacing
Digital input/output handling
Embedded system basics
Real-time event detection

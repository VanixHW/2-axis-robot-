2-Axis Robotic System with OLED Eyes (Arduino Uno)
Overview
This project builds a dual-axis robotic system controlled by an Arduino Uno, featuring servo-driven movement and expressive OLED eyes. The OLED display animates blinking and eye movements, while the servo motors enable lifelike head motion. The setup is ready for Bluetooth control, allowing further interaction.

Features
🎭 Expressive OLED Eyes with blinking animation

🕹 Dual-Axis Head Movement (servo-based motion)

📡 Wireless Control (optional Bluetooth commands)

🔄 Idle Behavior for natural motion and reactions

Hardware Components
Arduino Uno

128x64 SPI OLED Display (SSD1306)

Two Servo Motors (X and Y axis)

Bluetooth Module (Optional)

Power Supply (5V regulated)

Prototype Board & Connectors

Wiring & Pin Assignments
Component	Arduino Uno Pin
OLED SCK	8
OLED MOSI	9
OLED DC	11
OLED RST	10
OLED CS	12
Servo Y (Up/Down)	2
Servo X (Left/Right)	3
⚡ Ensure proper SPI and PWM connections for smooth operation.

Installation & Usage
Clone the Repository:

bash
git clone [https://github.com/yourusername/2-Axis-Robot-Arduino.git
cd 2-Axis-Robot-Arduino](https://github.com/VanixHW/2-axis-robot-)
Flash the Firmware: Upload the servo and OLED control code using Arduino IDE.

Power & Test: Watch the robot blink, move randomly, and react to commands.

License
This project is licensed under MIT, allowing for modifications and contributions.

Possible Enhancements
Add Bluetooth Control for direct movement commands

Integrate Sound or Voice Feedback

Refine Eye Animations for more expressions

# Digital-Code-Lock-System
Here is a clean, professional, and descriptive README.md style description for your GitHub repository. It’s structured to make your project look polished and easy for others (or your future self) to follow.

🔐 ESP8266 Digital Code Lock System
A secure, DIY electronic locking system powered by the ESP8266 (NodeMCU). This project uses a matrix keypad for PIN entry, an I2C LCD for user feedback, and a relay module to control a high-voltage solenoid door bolt.

🚀 Features
Secure PIN Entry: 4-digit master code validation.

Visual Feedback: 16x2 I2C LCD displays status messages ("Access Granted", "Invalid Code").

Privacy Mode: Masks input characters with * on the display.

Auto-Lock: Automatically re-engages the lock after a customizable delay.

Hardware Efficiency: Utilizes the ESP8266's GPIOs to handle an 8-pin keypad and I2C communication simultaneously.

🛠️ Hardware Requirements
Microcontroller: ESP8266 (NodeMCU or Wemos D1 Mini).

Input: 4x4 Matrix Keypad.

Output: 16x2 LCD with I2C Backpack.

Actuator: 12V Solenoid Lock + 5V Relay Module.

Power: External 12V DC supply (to power the lock and ESP8266 via regulator).

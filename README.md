# Mini Soccer Bot

A compact, Bluetooth-controlled soccer-playing robot built using Arduino Nano. This project demonstrates real-time motor control and servo-based kicking via a mobile app.

## Features
- Bluetooth control using HC-05 module
- Movement: forward, backward, left, right, stop
- Servo-controlled kicking mechanism
- Adjustable motor speed using PWM
- Compact 15x15 cm chassis suitable for mini soccer fields

## Components
- Arduino Nano  
- L298N Motor Driver  
- HC-05 Bluetooth Module  
- N20 DC Motors (300 RPM)  
- MG90 Servo Motor  
- 900mAh Li-Po Battery  

## Code Functions
- Serial commands (`1`–`9`) control motor direction and servo angle
- Speed is dynamically adjusted via PWM
- Includes forward, reverse, timed turning, and kicking logic

## Setup Instructions
1. Connect components according to the circuit diagram.
2. Upload the Arduino code using the Arduino IDE.
3. Pair the HC-05 module with your phone.
4. Use any Bluetooth controller app to send numeric commands.

## Known Issues
- Occasional Bluetooth disconnections
- Limited battery life
- Arduino Nano memory constraints for advanced features

## Future Improvements
- Add sensors or computer vision for ball tracking
- Upgrade communication to Wi-Fi or ESP-NOW
- Implement autonomous behavior using AI/ML



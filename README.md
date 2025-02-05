## Voice and Gyro Controlled Home Automation
Overview
The Voice and Gyro Controlled Home Automation project demonstrates a smart home system where appliances can be controlled using both voice commands and smartphone gestures. This project integrates Arduino, Bluetooth communication, and Firebase for real-time control through a custom Android app developed in Java.

Features
Voice-based control for turning appliances on and off.
Gesture-based control using the smartphone's gyroscope sensor.
Real-time appliance state updates through Firebase integration.
Wireless communication between the Android app and Arduino using Bluetooth.
Components Used
Hardware
Arduino Uno: Microcontroller for processing commands.
HC-05 Bluetooth Module: Enables wireless communication.
Relay Module: Used to control home appliances.
Power Supply: Provides power to the Arduino and relays.
Software
Android App: Developed in Java for user interaction.
Firebase: Used for real-time database management.
Arduino IDE: For writing and uploading Arduino code.
Project Architecture
Android App: The app provides two modes: Voice control and Gyro control. It connects to Firebase for real-time updates.
Arduino Module: Receives commands via Bluetooth from the app, controls the relays, and updates Firebase.
Firebase Integration: Maintains a real-time database for synchronized appliance control and status updates.
How to Use
Hardware Setup:

Connect the Bluetooth module to the Arduino Uno.
Wire the appliances to the relay module.
Power up the Arduino system.
App Installation:

Install the custom Android app on a smartphone.
Pair the smartphone with the HC-05 Bluetooth module.
Operation:

Launch the app and connect to the Bluetooth module.
Use voice commands (e.g., "Turn on the light") or gestures to control appliances.
Monitor real-time updates through Firebase.
Project Challenges
Synchronizing Firebase updates with app and Arduino actions.
Calibrating gyroscope sensors for accurate gesture control.
Ensuring stable Bluetooth communication over distances.
Future Scope
Integration with IoT platforms like Google Assistant or Alexa for smart assistant control.
Switching from Bluetooth to Wi-Fi for broader range communication.
Enhancing the Android app's UI for better user experience.
Contributors
[Your Name]
[Group Member 2]
[Group Member 3]
[Group Member 4]

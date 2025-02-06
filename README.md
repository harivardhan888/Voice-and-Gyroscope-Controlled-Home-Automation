# Voice and Gyro Controlled Home Automation
## Overview
The Voice and Gyro Controlled Home Automation project demonstrates a smart home system where appliances can be controlled using both voice commands and smartphone gestures. This project integrates Arduino, Bluetooth communication, and Firebase for real-time control through a custom Android app developed in Java.

### Feature
1. Voice-based control for turning appliances on and off.
2. Gesture-based control using the smartphone's gyroscope sensor.
3. Real-time appliance state updates through Firebase integration.
4. Wireless communication between the Android app and Arduino using Bluetooth.

### Hardware
Arduino Uno: Microcontroller for processing commands.
HC-05 Bluetooth Module: Enables wireless communication.
Power Supply: Provides power to the Arduino and relays.

### Software
Android App: Developed in Java for user interaction.
Firebase: Used for real-time database management.
Arduino IDE: For writing and uploading Arduino code.

### Project Architecture
Android App: The app provides two modes: Voice control and Gyro control. It connects to Firebase for real-time updates.
Arduino Module: Receives commands via Bluetooth from the app, controls the relays, and updates Firebase.
Firebase Integration: Maintains a real-time database for synchronized appliance control and status updates.

### Hardware Setup:

Connect the Bluetooth module to the Arduino Uno.
Power up the Arduino system.

### Operation:
Launch the app and connect to the Bluetooth module.
Use voice commands (e.g., "Turn on the light") or gestures to control appliances.
Monitor real-time updates through Firebase.

### Project Challenges
Synchronizing Firebase updates with app and Arduino actions.
Calibrating gyroscope sensors for accurate gesture control.
Ensuring stable Bluetooth communication over distances.

### Future Scope
Integration with IoT platforms like Google Assistant or Alexa for smart assistant control.
Switching from Bluetooth to Wi-Fi for broader range communication.
Enhancing the Android app's UI for better user experience.

## Contributors
1. K. Hari Vardhan Reddy
2. M. Dolananda phanisharma
3. P. Akshitha


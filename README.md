# Smart Traffic Light System

## Description
An IoT-based Smart Traffic Light System designed to manage vehicular traffic efficiently using NodeMCU, Blynk App, and IC 74HC595. The system allows automatic light looping, manual control, and adjustable green light timers through a mobile app interface.

## Features
- 🔁 **Automatic Light Looping**: Simulates real-world signal behavior.
- 📱 **Manual Control via Blynk App**: Enables manual override of traffic lights.
- ⏱️ **Green Light Timer**: Users can set green light duration through the app.

## Technologies Used
- NodeMCU (ESP8266)
- Arduino IDE
- Blynk IoT App
- IC 74HC595 (Shift Register)
- LEDs (Red, Yellow, Green)
- Jumper wires and Breadboard

## Installation

### Hardware Setup
1. Connect LEDs to IC 74HC595 and control it using NodeMCU.
2. Power the NodeMCU via USB.
3. Ensure Wi-Fi connectivity for NodeMCU.

### Software Setup
1. Install the **Arduino IDE**.
2. Add ESP8266 board to the IDE via Board Manager.
3. Install **Blynk** and **Shift Register** libraries.
4. Upload the code to NodeMCU via Arduino IDE.
5. Set up the Blynk project with buttons or sliders for manual control and timer.

## How to Use
1. Power the hardware and ensure NodeMCU is connected to Wi-Fi.
2. Open the Blynk app and connect it to your project.
3. Use:
   - **Auto Mode**: Lights loop in a fixed sequence automatically.
   - **Manual Mode**: Tap buttons to switch individual lights.
   - **Timer Control**: Adjust the green light duration as needed.

## Contributor
Simranjeet Kaur, Tanveer Singh , Roshni 



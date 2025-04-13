# The Smart Garden - Automated Plant Care System

A fully automated irrigation system for plant care powered by IoT and sensors, built with the ESP8266 microcontroller. The system is remotely managed via the Blynk app and integrates sensors to monitor and adjust environmental conditions such as soil moisture.

# Features

- **Remote Management**: Control and monitor the irrigation system remotely through the Blynk mobile app, making it easy to manage your garden anytime and anywhere.
- **Soil Moisture Monitoring**: Uses a soil moisture sensor to monitor the water content in the soil and adjust irrigation accordingly.
- **Cross-Device Compatibility**: The app works seamlessly across multiple devices for a user-friendly experience.
- **Automatic Irrigation**: The system is designed to automatically activate irrigation when the soil moisture falls below a set threshold.

# Technologies Used

- **ESP8266**: A low-cost Wi-Fi microcontroller used to connect the system to the internet.
- **Blynk App**: A mobile app for creating interfaces to control and monitor hardware remotely.
- **Soil Moisture Sensor**: Measures the water content in the soil to trigger irrigation when necessary.
- **Realtime Database**: Stores data on environmental conditions and user actions for real-time monitoring.
- **Programming Languages**: C/C++ for development and integration of the system.

# Getting Started

## Prerequisites

- **ESP8266 Module**
- **Blynk App**: Download the Blynk app from the App Store or Google Play.
- **Soil Moisture Sensor**
- **Arduino IDE**: For programming the ESP8266 module.

## Installation

### Install Blynk App:

1. Create an account and set up a new project in the Blynk app.
2. Choose the ESP8266 device type.
3. Get the authentication token from the app and keep it safe.

### Set Up the ESP8266:

1. Connect your ESP8266 to your computer.
2. Install the necessary drivers and add the ESP8266 board to Arduino IDE.

## Upload Code:

1. Download the source code from this repository.
2. Replace the **Blynk authentication token** and **Wi-Fi credentials** in the code.  
   Example:
   ```cpp
   // Replace with your Blynk token and Wi-Fi credentials
   char auth[] = "YourAuthToken";
   char ssid[] = "YourWiFiSSID";
   char pass[] = "YourWiFiPassword";
   ```

## Connect the Sensors:

Wire the soil moisture sensor to the ESP8266 as per the wiring diagram.

## Test the System:

Once the system is set up, use the Blynk app to monitor the environmental conditions and test the automatic irrigation functionality.

# Usage

- **Control Irrigation**: Adjust watering manually or set it to auto mode based on soil moisture levels.
- **Data Logging**: All readings are stored in the Realtime Database for easy access and tracking.

## License

This project is open-source and available under the MIT License.

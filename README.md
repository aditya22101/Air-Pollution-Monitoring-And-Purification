# Air-Pollution-Monitoring-And-Purification
Author's Name
1. Aditya Raj 2. Om Prakash Patel

Welcome to the Air Pollution Monitoring and Purification System project using ESP32 and Blynk! This project focuses on utilizing the ESP32 microcontroller and Blynk platform to monitor air quality and control air purification systems, enhancing environmental health and quality of life.

Project Overview
This system combines real-time air quality monitoring with advanced filtration technologies to address both indoor and outdoor air pollution. It provides actionable insights through data collection and user alerts, improving overall environmental health.

To clone this repository to your local machine, use the following command:

```bash
git clone https://github.com/yourusername/your-repository.git
```
Features
Real-Time Air Quality Monitoring: Measures pollutants such as particulate matter (PM2.5 and PM10), carbon monoxide (CO), and ozone (O3) using ESP32-compatible sensors.
Data Logging: Collects and logs data for analysis.
Air Purification Control: Interfaces with air purifiers to activate and adjust settings based on air quality data.
User Alerts: Sends notifications when pollutant levels exceed safe thresholds via Blynk.
Components
ESP32 Board: The central microcontroller for the project.
Sensors:
Particulate Matter Sensor: Measures PM2.5 and PM10 levels.
Carbon Monoxide Sensor: Measures CO levels.
Ozone Sensor: Measures O3 levels.
Air Purifier: Controlled via relays or other interfaces.
LCD Display (optional): Displays real-time air quality data.
Buzzer/LEDs (optional): Provides alerts.
Relay Module: Controls the air purifier.
Blynk App: For monitoring and controlling the system remotely.
Installation
Hardware Setup
Connect Sensors: Connect the particulate matter sensor, CO sensor, and ozone sensor to the ESP32 board according to the sensor datasheets.
Connect LCD Display (if used): Attach the LCD display to the ESP32 for real-time data visualization.
Set Up Relay Module: Connect the relay module to control the air purifier.
Connect Buzzer/LEDs (if used): Wire the buzzer or LEDs for alert notifications.
Software Installation

Open the Arduino IDE: Load the sketch from the src directory.
Configure Blynk:
Install the Blynk library through the Arduino Library Manager.
Obtain your Blynk authentication token from the Blynk app.
Set up Blynk’s virtual pins and project settings as needed.
Configuration
Adjust Thresholds: Modify sensor thresholds and relay control settings in the Arduino sketch file.
Upload Code: Upload the code to the ESP32 board using the Arduino IDE.
Usage
Power On: Turn on the ESP32 and sensors.
Monitor Data: The LCD (if used) will display real-time air quality readings. Data is also logged to the serial monitor.
Control Purification: The relay module will activate the air purifier based on sensor data. Adjust purifier settings via the Blynk app if necessary.
Receive Alerts: The buzzer or LEDs (if used) will activate when pollutant levels are high. Blynk will also send notifications.
Code
The Arduino sketch is located in the src directory and includes:

Sensor initialization and reading code.
Data logging and display logic.
Air purifier control and alert mechanisms.
Data Analysis
Use the serial monitor to view real-time data.
Export data from the Blynk app for further analysis or reporting.
Contact
For questions or support, please contact [Aditya Raj] at [aditya22101@iiitnr.edu.in].

Feel free to adjust the details and instructions according to your specific project setup and requirements.









Feel free to adjust the content to better suit your specific project needs or details.

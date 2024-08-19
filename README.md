# Air-Pollution-Monitoring-And-Purification
Author's Name
1. Aditya Raj 2. Om Prakash Patel


Addressing air pollution effectively requires a combination of monitoring, technological innovation, policy-making, and public awareness. Each component plays a role in reducing pollution and protecting health and the environment.
Welcome to the Air Pollution Monitoring and Purification System project! This project aims to monitor and improve air quality through a combination of real-time data collection, advanced filtration technologies, and actionable insights. The system is designed to address both indoor and outdoor air pollution, ensuring a healthier environment and better quality of life.

Welcome to the Air Pollution Monitoring and Purification System project using Arduino! This project focuses on using Arduino-based sensors to monitor air quality and control air purification systems to improve environmental health. This guide provides information on setting up and using the system effectively.

Features
Real-Time Air Quality Monitoring: Measures pollutants such as particulate matter (PM2.5 and PM10), carbon monoxide (CO), and ozone (O3) using Arduino-compatible sensors.
Data Logging: Collects and logs data for analysis.
Air Purification Control: Interfaces with air purifiers to activate and adjust settings based on air quality data.
User Alerts: Sends notifications when pollutant levels exceed safe thresholds.
Components
Arduino Board: Arduino Uno, Mega, or any compatible board.
Sensors:
Particulate Matter Sensor: For PM2.5 and PM10 measurements.
Carbon Monoxide Sensor: For CO levels.
Ozone Sensor: For O3 measurements.
Air Purifier: Can be controlled via relays or other interfaces.
LCD Display: For showing real-time air quality data (optional).
Buzzer/LEDs: For alerts (optional).
Relay Module: To control the air purifier.
Installation
Hardware Setup:

Connect the particulate matter sensor, CO sensor, and ozone sensor to the Arduino board according to the sensor datasheets.
Connect the LCD display to the Arduino (if using).
Set up the relay module to control the air purifier.
Wire the buzzer or LEDs for alerts (if using).
Software Installation:

Clone the repository: git clone <repository-url>
Open the Arduino IDE.
Load the sketch from the src directory.
Configuration:

Adjust the sensor thresholds and relay control settings in the Arduino sketch file.
Upload the code to the Arduino board using the Arduino IDE.
Usage
Monitoring:

Power on the Arduino and sensors.
The LCD (if used) will display real-time air quality readings.
Data is logged to the serial monitor for analysis.
Purification:

The relay module will activate the air purifier based on the sensor data.
Adjust the purifier settings as needed.
Alerts:

The buzzer or LEDs (if used) will activate to alert when pollutant levels are high.
Code
The Arduino sketch is located in the src directory. This file includes:
Sensor initialization and reading code.
Data logging and display logic.
Air purifier control and alert mechanisms.
Data Analysis
Use the serial monitor to view real-time data.
Export data for further analysis or reporting.



Contact
For questions or support, please contact [Aditya Raj] at [aditya22101@iiitnr.edu.in].

Feel free to adjust the content to better suit your specific project needs or details.
